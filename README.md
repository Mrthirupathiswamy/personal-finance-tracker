# personal-finance-tracker
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Personal Finance Tracker</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h2>Personal Finance Tracker</h2>
  <form id="financeForm">

    <!-- Income Section -->
    <fieldset>
      <legend><h3>Income</h3></legend>
      <label>Salary: <input type="number" name="salary" required></label><br>
      <label>Freelancing: <input type="number" name="freelancing"></label><br>
      <label>Passive Income: <input type="number" name="passive_income"></label><br>
    </fieldset>

    <!-- Expenses Section -->
    <fieldset>
      <legend><h3>Expenses</h3></legend>

      <!-- Housing -->
      <h4>🏠 Housing</h4>
      <label>Rent/Mortgage: <input type="number" name="rent"></label><br>
      <label>Utilities: <input type="number" name="utilities"></label><br>
      <label>Maintenance: <input type="number" name="maintenance"></label><br>

      <!-- Food -->
      <h4>🍽️ Food</h4>
      <label>Groceries: <input type="number" name="groceries"></label><br>
      <label>Dining Out: <input type="number" name="dining_out"></label><br>

      <!-- Transportation -->
      <h4>🚗 Transportation</h4>
      <label>Transportation: <input type="number" name="transportation"></label><br>
      <label>Fuel/Maintenance: <input type="number" name="vehicle_maintenance"></label><br>

      <!-- Family & Children -->
      <h4>👨‍👩‍👧 Family & Kids</h4>
      <label>Education: <input type="number" name="education"></label><br>
      <label>Childcare: <input type="number" name="childcare"></label><br>

      <!-- Healthcare -->
      <h4>🏥 Healthcare</h4>
      <label>Healthcare: <input type="number" name="healthcare"></label><br>
      <label>Insurance: <input type="number" name="insurance"></label><br>

      <!-- Utilities -->
      <h4>📶 Bills & Utilities</h4>
      <label>Internet and Mobile Bills: <input type="number" name="internet_mobile"></label><br>

      <!-- Lifestyle -->
      <h4>🎉 Lifestyle</h4>
      <label>Entertainment: <input type="number" name="entertainment"></label><br>
      <label>Subscriptions: <input type="number" name="subscriptions"></label><br>
      <label>Clothing: <input type="number" name="clothing"></label><br>
      <label>Personal Care: <input type="number" name="personal_care"></label><br>

      <!-- Essentials -->
      <h4>🧴 Essentials</h4>
      <label>Household Supplies: <input type="number" name="household_supplies"></label><br>

      <!-- Finance & Savings -->
      <h4>💰 Finance</h4>
      <label>Loan EMIs: <input type="number" name="loan_emis"></label><br>
      <label>Savings and Investments: <input type="number" name="savings_investments"></label><br>
      <label>Emergency Fund: <input type="number" name="emergency_fund"></label><br>

      <!-- Misc -->
      <h4>🔧 Miscellaneous</h4>
      <label>Miscellaneous Expenses: <input type="number" name="miscellaneous"></label><br>
    </fieldset>

    <!-- Liabilities Section -->
    <fieldset>
      <legend><h3>Liabilities</h3></legend>
      <label>Loans: <input type="number" name="loans"></label><br>
      <label>Credit Cards: <input type="number" name="credit_cards"></label><br>
      <label>EMIs: <input type="number" name="emis"></label><br>
    </fieldset>

    <!-- Budget Goals -->
    <fieldset>
      <legend><h3>Budgets & Goals</h3></legend>
      <label>Monthly Spending Target: <input type="number" name="monthly_spending_target"></label><br>
      <label>Saving Goal: <input type="number" name="saving_goal"></label><br>
    </fieldset>

    <br><button type="submit">Submit</button>
  </form>

  <div id="suggestions" style="margin-top:20px;"></div>

  <!-- JavaScript logic stays the same -->
</body>
</html>

/* General Page Styling */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 40px;
    background-color: #0b1120;
    color: #f4f4f4;
  }
  
  /* Heading Styles */
  h2 {
    color: #00ffcc;
    font-size: 2em;
    margin-bottom: 20px;
  }
  
  h3 {
    color: #ffebcd;
    margin-top: 30px;
    font-size: 1.3em;
  }
  
  /* Form Label and Input Styling */
  form label {
    display: block;
    margin-bottom: 10px;
    font-weight: 500;
  }
  
  input[type="number"] {
    padding: 8px;
    margin-left: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
    outline: none;
    background-color: #f9f9f9;
    color: #333;
    width: 200px;
  }
  
  /* Button Styling */
  button {
    background-color: #00c26e;
    color: white;
    padding: 12px 24px;
    margin-top: 20px;
    border: none;
    border-radius: 8px;
    font-size: 1em;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  
  button:hover {
    background-color: #019f5a;
  }
  
  /* Suggestions Section */
  #suggestions {
    background-color: #1c2331;
    padding: 20px;
    margin-top: 30px;
    border-radius: 10px;
    color: #d0d0d0;
    box-shadow: 0 4px 12px rgba(0, 255, 200, 0.1);
  }
  
  #suggestions h3 {
    color: #00e6d2;
  }
  


css


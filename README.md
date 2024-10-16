# Html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EMI Calculator</title>
  <link rel="stylesheet" href="emi.css">
</head>
<body>
  <div class="container">
    <h2>EMI Calculator</h2>
    <div class="input-group">
      <label for="loanAmount">Loan Amount (₹):</label>
      <input type="number" id="loanAmount" placeholder="Enter loan amount">
    </div>
    <div class="input-group">
      <label for="interestRate">Interest Rate (%):</label>
      <input type="number" id="interestRate" placeholder="Enter interest rate">
    </div>
    <div class="input-group">
      <label for="loanTerm">Loan Term (months):</label>
      <input type="number" id="loanTerm" placeholder="Enter loan term">
    </div>
    <button onclick="calculateEMI()">Calculate EMI</button>
    <div id="result"></div>
  </div>
  <script src="emi.js"></script>
</body>
</html>

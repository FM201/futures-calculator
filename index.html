!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Futures Position Size Calculator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 400px;
      margin: 50px auto;
      padding: 20px;
      border-radius: 10px;
      background-color: #f3f3f3;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h2 {
      text-align: center;
    }
    label {
      display: block;
      margin-top: 15px;
    }
    input, select, button {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      font-size: 16px;
    }
    #result {
      margin-top: 20px;
      font-size: 18px;
      text-align: center;
      color: green;
    }
  </style>
</head>
<body>
  <h2>Futures Contract Position Size Calculator</h2>

  <label for="contract">Select Contract:</label>
  <select id="contract">
    <option value="MNQ">MNQ (Micro Nasdaq)</option>
    <option value="NQ">NQ (Nasdaq)</option>
    <option value="MES">MES (Micro S&P)</option>
    <option value="ES">ES (S&P)</option>
  </select>

  <label for="risk">How much do you want to risk (in $)?:</label>
  <input type="number" id="risk" placeholder="e.g. 100" />

  <label for="stopLoss">Stop Loss in Points:</label>
  <input type="number" id="stopLoss" placeholder="e.g. 5" />

  <button onclick="calculateContracts()">Calculate Contracts</button>

  <div id="result"></div>

  <script>
    const futuresData = {
      MNQ: 2.0,
      NQ: 20.0,
      MES: 5.0,
      ES: 50.0
    };

    function calculateContracts() {
      const contract = document.getElementById("contract").value;
      const risk = parseFloat(document.getElementById("risk").value);
      const slPoints = parseFloat(document.getElementById("stopLoss").value);
      const resultDiv = document.getElementById("result");

      if (isNaN(risk) || isNaN(slPoints) || slPoints <= 0 || risk <= 0) {
        resultDiv.innerHTML = "⚠️ Please enter valid numbers for risk and stop loss.";
        resultDiv.style.color = "red";
        return;
      }

      const valuePerPoint = futuresData[contract];
      const riskPerContract = valuePerPoint * slPoints;
      const contracts = Math.floor(risk / riskPerContract);

      resultDiv.style.color = "green";
      resultDiv.innerHTML = `➡ You should trade <strong>${contracts}</strong> contract(s) of ${contract} to stay within $${risk.toFixed(2)} risk.`;
    }
  </script>
</body>
</html>

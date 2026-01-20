
<!DOCTYPE html>
<html>
<head>
    <title>Semen Analysis Fertility Assessment</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; background-color: #f9f9f9; }
        .container { max-width: 500px; margin: auto; padding: 20px; background: #fff; border: 1px solid #ccc; border-radius: 8px; }
        h2 { text-align: center; color: #007bff; }
        label { font-weight: bold; }
        input { width: 100%; padding: 8px; margin: 6px 0; border: 1px solid #ccc; border-radius: 4px; }
        button { width: 100%; padding: 10px; background-color: #007bff; color: white; border: none; border-radius: 4px; cursor: pointer; font-size: 16px; }
        button:hover { background-color: #0056b3; }
        .result { margin-top: 15px; padding: 10px; font-weight: bold; text-align: center; border-radius: 4px; font-size: 18px; }
        .normal { background-color: #28a745; color: white; }
        .reduced { background-color: #ffc107; color: black; }
        .infertile { background-color: #dc3545; color: white; }
        .tips { margin-top: 20px; font-size: 14px; color: #555; }
    </style>
</head>
<body>
    <div class="container">
        <h2>Semen Analysis Assessment Tool</h2>
        <label>Volume (mL):</label>
        <input type="number" id="volume" step="0.1">
        
        <label>Sperm Concentration (million/mL):</label>
        <input type="number" id="concentration">
        
        <label>Total Sperm Count (million):</label>
        <input type="number" id="totalCount">
        
        <label>Progressive Motility (%):</label>
        <input type="number" id="progressive">
        
        <label>Total Motility (%):</label>
        <input type="number" id="motility">
        
        <label>Morphology (% normal forms):</label>
        <input type="number" id="morphology">
        
        <button onclick="assessInfertility()">Assess Fertility</button>
        
        <div id="result" class="result"></div>
        
        <div class="tips">
            <strong>WHO Reference Values:</strong><br>
            Volume ≥ 1.5 mL | Concentration ≥ 15 million/mL | Total Count ≥ 39 million<br>
            Progressive Motility ≥ 32% | Total Motility ≥ 40% | Morphology ≥ 4%<br><br>
            <strong>Interpretation:</strong><br>
            ✅ Normal Fertility: All parameters normal<br>
            ⚠ Reduced Fertility: One or more parameters slightly low<br>
            ❌ Possible Infertility: Severe abnormality in any key parameter<br>
        </div>
    </div>

    <script>
        function assessInfertility() {
            let volume = parseFloat(document.getElementById('volume').value);
            let concentration = parseFloat(document.getElementById('concentration').value);
            let totalCount = parseFloat(document.getElementById('totalCount').value);
            let progressive = parseFloat(document.getElementById('progressive').value);
            let motility = parseFloat(document.getElementById('motility').value);
            let morphology = parseFloat(document.getElementById('morphology').value);

            // WHO Reference Values
            const MIN_VOLUME = 1.5;
            const MIN_CONCENTRATION = 15;
            const MIN_TOTAL_COUNT = 39;
            const MIN_PROGRESSIVE = 32;
            const MIN_TOTAL_MOTILITY = 40;
            const MIN_MORPHOLOGY = 4;

            // Severe thresholds for possible infertility
            const SEVERE_CONCENTRATION = 5;
            const SEVERE_TOTAL_COUNT = 20;
            const SEVERE_PROGRESSIVE = 20;
            const SEVERE_MORPHOLOGY = 1;

            let resultText = "";
            let resultClass = "";

            if (volume >= MIN_VOLUME &&
                concentration >= MIN_CONCENTRATION &&
                totalCount >= MIN_TOTAL_COUNT &&
                progressive >= MIN_PROGRESSIVE &&
                motility >= MIN_TOTAL_MOTILITY &&
                morphology >= MIN_MORPHOLOGY) {
                
                resultText = "✅ Normal Fertility Potential";
                resultClass = "normal";
            } else if (concentration < SEVERE_CONCENTRATION ||
                       totalCount < SEVERE_TOTAL_COUNT ||
                       progressive < SEVERE_PROGRESSIVE ||
                       morphology < SEVERE_MORPHOLOGY) {
                
                resultText = "❌ Possible Infertility - Needs Clinical Correlation";
                resultClass = "infertile";
            } else {
                resultText = "⚠ Reduced Fertility Potential";
                resultClass = "reduced";
            }

            let resultDiv = document.getElementById('result');
            resultDiv.textContent = resultText;
            resultDiv.className = "result " + resultClass;
        }
    </script>
</body>
</html>

# simple_interest
<!DOCTYPE html>
<html>
    <head>
        <title>Web App-Simple Interest Calculator</title>
    <script src="script.js"></script>
    <link rel="stylesheet" href="style.css">
    </head>
    <body>
        
        <div class="maindiv">
        <h1>Simple Interest Calculator</h1>

        Amount <input type="number"  id="principal" onchange="validateAmount()">  <br/>
        Rate <input type="range" id="rate" min="1" max="20" step="0.25" value="10.25" onchange="getSliderValue()"><span id="rateSpan">10.50%</span>  <br/>
        No. of Years  
        <select name="years" id="years">
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
            <option value="5">5</option>
            <option value="6">6</option>
            <option value="7">7</option>
            <option value="8">8</option>
            <option value="9">9</option>
            <option value="10">10</option>
          </select><br/>

        <button onclick="compute()">Compute Interest</button><br/>
        <span id="result"></span><br>
        <span id="result"></span>
        <footer>&#169; Everyone Can Get Rich.
            The calculator belongs to Riya Pimprikar
        </footer>
    </div>
    </body>
</html>

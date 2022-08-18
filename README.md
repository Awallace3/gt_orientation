# Instructions

1. Open the following link for online editor or use your own!
 [codepen.io](https://codepen.io/pen/)
2. Copy the text below by clicking the clipboard button on top right corner and
   past into codepen.io's HTML tab

```
<div>
<script>
    function computePi(){
    let pi_guess = 0
    let n = 100;
    let cirlcePoints = 0;
    let squarePoints = 0;
    let n1 = 0;
    let n2 = 0;
    let dis = 0
    
    // START WRITING CODE HERE
    
    
    
    
    // END WRITING CODE 
    
    pi_guess = pi_guess.toFixed(16)
    let output = "Pi estimate:\n" + pi_guess + "\nPi:\n" + Math.PI
    document.getElementById("pi_guess").innerHTML = pi_guess
    document.getElementById("pi").innerHTML = Math.PI
    return output
}
</script>
    <button id="btn" onclick="computePi()">
        Calculate Pi with available points!
    </button>
    </br>
    <text>Guess Pi: 
        <b id='pi_guess'></b>
    </text>
    </br>
    <text>Pi actual: 
        <b id='pi'></b>
    </text>
</div
```

# Acknowledgements
More information on generating Pi from a Monte Carlo algorithm can be found [here](https://blogs.sas.com/content/iml/2016/03/14/monte-carlo-estimates-of-pi.html)


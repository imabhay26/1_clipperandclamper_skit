<html>

<head>

<title>Quiz Questions And Answers</title>

</head>

<body background="https://i.pinimg.com/originals/83/a5/9b/83a59b0d654dd1f0478a4c61a52d7391.jpg">

<p style="text-align:center;"><font size="10" color="sky blue" face="Arabic Typestting"> <b>QUIZ </b></font></br>
</br></p>

<p>

<form name="quiz">
<font size="4" color="white">
<p>

<b>Question 1.

<br>1.	In a positive clipper, the diode conducts when<br></b>

<blockquote>

<input type="radio" name="q1" value="Vin < Vref">Vin < Vref<br>

<input type="radio" name="q1" value="Vin = Vref">Vin = Vref<br>

<input type="radio" name="q1" value="Vin > Vref">Vin > Vref<br>

</blockquote>

<p><b>

<hr>

Question 2.

<br>What happens if the input voltage is higher than reference voltage in a positive clipper?<br></b>

<blockquote>

<input type="radio" name="q2" value="Output voltage = Reference voltage">Output voltage = Reference voltage<br>

<input type="radio" name="q2" value="Output voltage = DC Positive voltage">Output voltage = DC Positive voltage<br>

<input type="radio" name="q2" value=" Output voltage = Input voltage">Output voltage = Input voltage<br>

</blockquote>

<p><b>

<hr>

Question 3.

<br>3.	Diode in small signal positive half wave rectifier circuit acts as<br></b>

<blockquote>

<input type="radio" name="q3" value="Ideal diode">Ideal diode<br>

<input type="radio" name="q3" value="Clipper diode">Clipper diode<br>

<input type="radio" name="q3" value="Clamper diode">Clamper diode<br>

</blockquote>

<p><b>

<hr>

Question 4.

<br>4.	One that clips positive part of voltage is known as<br></b>

<blockquote>

<input type="radio" name="q4" value="current regulator">current regulator<br>

<input type="radio" name="q4" value="clipper">clipper<br>

<input type="radio" name="q4" value="voltage regulator">voltage regulator<br>

</blockquote>

<p><b>

<hr>

Question 5.

<br>A circuit that removes positive or negative parts of waveform is called <br></b>

<blockquote>

<input type="radio" name="q5" value="clamper">clamper <br>

<input type="radio" name="q5" value="clipper">clipper<br>

<input type="radio" name="q5" value="diode clamp">diode clamp <br>

</blockquote>

<p><b>

<hr>

Question 6.

<br> The clipping level in op-amp is determined by<br></b>

<blockquote>

<input type="radio" name="q6" value="supply voltage">AC supply voltage<br>

<input type="radio" name="q6" value="Control voltage">Control voltage<br>

<input type="radio" name="q6" value="Reference voltage">Reference voltage<br>

</blockquote>

<p><b>

Question 7.

<br>Half wave voltage multiplier can provide any degree of voltage multiplication by cascading diodes and capacitors.<br></b>

<blockquote>

<input type="radio" name="q7" value="only doubler">only doubler<br>

<input type="radio" name="q7" value="only tripler">only tripler <br>

<input type="radio" name="q7" value="any multiplication ">any multiplication <br>

</blockquote>

<p><b>

<hr>

Question 8.

<br>In most electronic circuits, it is best to select the smallest possible level of current by keeping total supply current to a<br></b>

<blockquote>

<input type="radio" name="q8" value="minimum">minimum<br>

<input type="radio" name="q8" value="maximum">maximum<br>

<input type="radio" name="q8" value="no change">no change<br>

</blockquote>

<p><b>

<hr>

Question 9.

<br>4.	A clamper circuit<br>
1. adds or subtracts a dc voltage to a waveform <br>
2. does not change the waveform <br>
3. amplifies the waveform<br>
 Which are correct? <br>
<br></b>

<blockquote>

<input type="radio" name="q9" value="1,2">1,2<br>

<input type="radio" name="q9" value="1,2,3">1,2,3<br>

<input type="radio" name="q9" value="1,3">1,3<br>

</blockquote>

<p><b>

<hr>

Question 10.

<br>A circuit that adds positive or negative dc voltage to an input sine wave is called <br></b>

<blockquote>

<input type="radio" name="q10" value="clamper">clamper<br>

<input type="radio" name="q10" value="clipper">clipper<br>

<input type="radio" name="q10" value="diode clamp">diode clamp<br>

</blockquote>

<p><b>



<input type="button"value="Grade Me"onClick="getScore(this.form);">

<input type="reset" value="Clear"><p>

Number of score out of 10 = <input type= text size 10 name= "mark">

Score in percentage = <input type=text size=10 name="percentage"><br>

</form>

<p>

<form method="post" name="Form" onsubmit="" action="">

</form>

</body>

<script>

var numQues = 10;

var numChoi = 3;

var answers = new Array(10);

answers[0] = "Vin = Vref";

answers[1] = "Output voltage = Reference voltage";

answers[2] = "Ideal diode";

answers[3] = "clipper";

answers[4] = "clipper";

answers[5] = "Reference voltage";

answers[6] = "any multiplication ";

answers[7] = "no change";

answers[8] = "1,2";

answers[9] = "clamper";


function getScore(form) {

var score = 0;

var currElt;

var currSelection;

for (i=0; i<numQues; i++) {

currElt = i*numChoi;

answered=false;

for (j=0; j<numChoi; j++) {

currSelection = form.elements[currElt + j];

if (currSelection.checked) {

answered=true;

if (currSelection.value == answers[i]) {

score++;

break;

}

}

}

if (answered ===false){alert("Do answer all the questions, Please") ;return false;}

}

var scoreper = Math.round(score/numQues*100);

form.percentage.value = scoreper + "%";

form.mark.value=score;

}

</script>
</font>
</html>

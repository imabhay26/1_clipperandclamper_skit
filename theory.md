<p><strong><u>Theory</u></strong></p>
<p><strong>Clipper:</strong></p>
<p>Clippers, limiters or clipping circuits make use of non-linear properties of diode, that is the diode conducts the current in the forward direction and does not conduct in the reverse direction. These circuits are primarily are wave shaping circuits. They clip or remove a certain portion of AC voltage applied to the input of the circuit. Clipping circuit is used to select for transmission that part of an arbitrary waveform which lies above or below some reference level. Clipping circuits are also referred to as voltage limiters.</p>
<p>Clamping circuit preserves shape of the waveform while clipping circuit does not preserve the shape of the waveform. Clipping circuit uses some reference level. Waveform above or below this reference level is clipped. Clipping circuits are also known as the voltage limiter or an amplitude limiter or slicers.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p>
<p><strong>Positive Diode Clipper</strong></p>
<p>In a positive clipper, the positive half cycles of the input voltage will be clipped out. A biased clipper comes in handy when a small portion of positive or negative half cycles of the signal voltage is to be removed. When a small portion of the positive half cycle is to be removed, it is called a biased positive&nbsp; clipper.</p>
<p>In a biased clipper, when the input signal voltage is positive, When the input signal voltage is positive but does not exceed battery the voltage &lsquo;V&rsquo;, the diode &lsquo;D&rsquo; remains reverse-biased and the input signal appears across the output. When during the positive half cycle of input signal, the signal voltage becomes more than the battery voltage V, the diode D is forward biased and so diode conducts. The output voltage is equal to &lsquo;V+0.7V&rsquo; and stays at &lsquo;V+0.7V&rsquo; as long as the magnitude of the input signal voltage is greater than the magnitude of the battery voltage, &lsquo;V&rsquo;. When during the negative half cycle of input signal, the signal voltage becomes more than the battery voltage V, the diode D is reverse biased and so the diode is behaves as an open switch. Thus the entire negative half cycle appears across the load, as illustrated by output waveform .Thus a biased positive clipper removes input voltage when the input signal voltage becomes greater than the battery voltage</p>
<p><strong>Design Calculation:</strong></p>
<p>If the circuit (Fig 5.1)is in forward biased then apply the KVL in given circuit and find out the value of&nbsp; battery voltage V</p>
<p>Let us :Si diode V<sub>D</sub>=0.7V, V<sub>O</sub>=4V, V<sub>I</sub>=5 V</p>
<p>Where: V<sub>D</sub>=Cut in voltage of the diode</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;V<sub>o</sub>=output voltage</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;V<sub>I</sub>=input voltage</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;V=Battery voltage</p>
<p>V<sub>0</sub>-V<sub>D</sub>-V=0</p>
<p>4-0.7-V=0</p>
<p>V=3.3 V</p>
<p>So we&nbsp; apply the battery of 3.3 V for the maximum 4 V output at the positive half cycle and in the negative half cycle the output are same as input that is -5V.</p>
<p><strong>Clamper:</strong></p>
<p>Clamping circuits are used to change DC level (average level) of the signal which adds or subtracts DC value to the signal. In clamping, the shape of waveform remains same only offset value (DC level) will change. Positive clamping adds a positive DC level in the signal while negative clamping adds a negative DC level in the signal. The Capacitor is widely used in the clamping circuit. Typical clamping waveforms of the sinusoidal signal are shown below for positive clamping and negative clamping.</p>
<p>Clamping circuit is used in video amplifier of television receiver to restore DC level of video signal to preserve the overall brightness of the scene. Clamping circuit is also used in offset control of a function generator. Zero offsets means no DC value is added in the AC signal.</p>
<p>The circuit will be called a positive clamper , when the signal is pushed upward by the circuit. When the signal moves upward, as shown in figure (a), the negative peak of the signal coincides with the zero level. The circuit will be called a negative clamper, when the signal is pushed downward by the circuit. When the signal is pushed on the negative side, as shown in figure (b), the positive peak of the input signal coincides with the zero level.</p>
<p><strong>Design Calculation:</strong></p>
<p>Let us:</p>
<p>Input voltage : 10 Volt peak to peak or 5 sin 2&pi;t</p>
<p>Required output voltage:2 V (peak)to -8V(peak)</p>
<p>So First, it is required to calculate the voltage of the biased battery in the circuit,</p>
<p>Apply the KVL in Circuit:</p>
<p>V<sub>in</sub>-V<sub>c</sub>-V<sub>1</sub>=0</p>
<p>The maximum voltage is V<sub>m</sub> then equation is</p>
<p>Or V<sub>m</sub>-V<sub>c</sub>-V<sub>1</sub>=0</p>
<p>V<sub>c</sub>=V<sub>m</sub>-V<sub>1</sub>------------------(1)</p>
<p>Apply the KVL in output circuit</p>
<p>V<sub>in</sub>-V<sub>c</sub>-V<sub>o</sub>=0&hellip;&hellip;&hellip;&hellip;&hellip;..(2)</p>
<p>Put equation (1) to equation(2)</p>
<p>V<sub>in</sub>-V<sub>m</sub>+V<sub>1</sub>=V<sub>o</sub></p>
<p>If V<sub>in</sub>=0 then V<sub>o</sub>=-V<sub>m</sub>+V<sub>1</sub></p>
<p>If V<sub>in</sub>=V<sub>m</sub> then V<sub>o</sub>=V<sub>1</sub>&hellip;&hellip;&hellip;&hellip;&hellip;..(3)</p>
<p>If V<sub>in</sub>=-V<sub>m</sub> then V<sub>o</sub>=-2V<sub>m</sub>+V<sub>1</sub>&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;&hellip;..(4)</p>
<p>From equation (3) If V<sub>0</sub>=2 V then We get V<sub>1</sub>=2 V</p>

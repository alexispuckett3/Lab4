# Lab 4 Go Big: Operational Amplifiers

* Hannah Markwell
* Alexis Puckett

February 8, 2024

## Project Summary:

In this lab the goal was to learn the importance and use of operational amplifiers (Op Amps). The importance of this is to be able to build amplifier and signal conditioning circuits as well as be able to understand the usage of Op Amps such as their benefits and drawbacks. In order to test this, a series of circuits were constructed. The variables that were used and tested included an LM741 Op Amp and a 1kOhm trimmer potentiometer. We used these variables as others, such as a variety of resistors, to create different Inverting Op Amp circuits, voltage follower circuits, integrating Op Amp, and differentiating Op Amp in order to observe the gain in each circuit. These steps and measurements allowed us to better understand these circuits and learn more about Op Amps. 

## Design/Methods:

For this lab we needed:
* A bread board 
* Two DC Power supplies (DCPS): Global Specialties 1403
* Digital Multi-meter (DMM): Fluke 87
* A Function Generator: Global Specialties 2001A
* An Oscilloscope: Tektronix TDS 2012
* Resistors with resistances of 1k&Omega;, 4.7k&Omega;, 8.2k&Omega;, two 68k&Omega;, 150k&Omega;, 270k&Omega;, 270k&Omega;, 330k&Omega;, and 1.5M&Omega;
* A capacitor of 0.1&mu;F
* An LM741 Op Amp
* A 1k&Omega;, a 10k&Omega;, and a 100k&Omega; trimmer potentiometer

We began by measuring the actual resistances and capacitances of the resistors and capacitors we used throughout this lab. Below are the measured values. 

| Nominal Value| Actual Value |
|:---:|---|
| 68 k&Omega;   | 66.8 k&Omega;     |
| 68 k&Omega;   | 66.8 k&Omega;     |
| 150 k&Omega;  |  148.1 k&Omega;   |
| 270 k&Omega;  | 271.5 k&Omega;    |
| 330 k&Omega;  |  337.2 k&Omega;   |
| 1.5 M&Omega;  |  1.5 M&Omega;     |
| 1 k&Omega;    |  0.986 k&Omega;   |
| 4.7 k&Omega;  |  4.599 k&Omega;   |
| 8.2 k&Omega;  |  8.07 k&Omega;    |
| 0.1 &mu;F     |  0.1023 &mu;F     |

We ended up only using one potentiometer for the first circuit. We used the 10k&Omega; which had a measured resistance of 9.86k&Omega;.

### Part One:

_Circuit One_: Unity Gain Inverting Op Amp

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/1-4.png">
</p>

Build the above unity gain inverting op amp with the 10k&Omega; potentiometer on the bread board. Connect to the two DCPS. While changing the resistance of the potentiometer, measure the Vo and the Vi at the labeled points in the circuit using the DMM. Swing the potentiometer from low to high resistance while recording the Vo and Vi values. We show our measured values and a plot of the measured value in our results.

_Circuit Two_: Moderate Gain Inverting Op Amp

Next, we constructed a moderate gain inverting op amp using different resistance values (8.2 k&Omega; and 330 k&Omega;) and connected it to two DCPS.

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/2-4.png">
</p>

Instead of using a potentiometer and the DMM to measure Vo and Vi values, we connected this circuit to the function generator and oscilloscope. We plotted Vi in channel one and Vo in channel two. From the oscilloscope, we could then measure and calculate the gain of the circuit. 

_Circuit Three_: High Gain Inverting Op Amp

Next. build a high gain inverting op amp on the bread board by using the 1k&Omega; and 1.5M&Omega; resistors. Connect this circuit to the DCPS along with the function generator and oscilloscope to measure and calculate the gain. 

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%203%20lab%204%20drawing.png">
</p>

### Part Two:

_Circuit Four_: Voltage Follower

Build the voltage follower circuit in the bread board pictured below. Connect the circuit to the two DCPS, the function generator, and the oscilloscope. 

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%204%20lab%204%20drawing.png">
</p>

Check to see that the input and output voltage are the same. Then, increase the frequency to see find what the frequency limit is for the 741 op amp. 

_Circuit Five_: Integrating Op Amp
 
Next, build the integrating op amp displayed below on the bread board. 

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/5-4.png">
</p>

Connect the circuit to the two DCPS, the function generator, and the oscilloscope. Change the shape of the waves along with the frequency using the function generator to observe what happens. 

_Circuit Six_: Differentiating Op Amp

Finally, create the differentiating op amp displayed below. 

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/6-4.png">
</p>

Connect the circuit to the two DCPS, the function generator, and the oscilloscope. Once again, change the shape of the waves and frequency to observe what happens to Vo and Vi. 

## Results:


### Part One:

_Circuit One_:

Measured Vi VS Vo Values:
| Vi (Volts) | Vo (Volts)|
|:---:|---|
| -12.82 | 12.77   |
| -13.1  | 13.06   |
| -13.27 |  13.24  |
| -13.79 | 13.75   |
| -14.13 |   14.09 |
| -11.24 |  11.21  |
| -10.47 |   10.43 |
| -9.89  |  9.87   |
| -8.63  |  8.61   |

| Expected Gain (Calculated) | Actual Gain (Measured) |
|:---:|---|
|  1 |   0.997  |


_Circuit Two_:

Oscilloscope Reading of Circuit Two:
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%201%20lab%204.png">
</p>

| Expected Gain (Calculated) | Actual Gain (Measured) |
|:---:|---|
|  40.24 |    8.33 |

Although these values differ from each other, they make sense because 15V is not enough voltage to reach a gain of 40.24 in this circuit.

_Circuit Three_:

Oscilloscope Reading of Circuit Three:
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/3-4.png">
</p>

| Expected Gain (Calculated) | Actual Gain (Measured) |
|:---:|---|
|  1500 |    21.969 |

### Part Two:

_Circuit Four_:

The input (Vi) and output (Vo) voltages were seen to be the same. 

Vi=12.8V
Vo=12.8V

This shows that the gain=1 because there is no change between the input and output voltages in this op amp circuit. 

Increase the frequency to find out and record what the frequency limit is for the 741 op amp. 

Oscilloscope Reading of Voltage Follower Circuit:
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%204%20lab%204.png">
</p>
We can see from the oscilloscope that there is no change between Vi and Vo, the waves overlap. 


_Circuit Five_:

We changed the frequency and voltage to see what would happen. As frequency increases, Vo decreases and Vi stays the same around 12.2V. As the frequency decreases, Vo increases and Vi decreases. As the voltage supplied by the voltage source decreases, both Vo and Vi decrease. As the voltage supplied increases, both Vo and Vi increase.
 
10kHz Oscilloscope Reading:
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%205%20lab%204%2010kHz.png">
</p>

Sine Wave Oscilloscope Reading:
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%205%20lab%204%20sine.png">
</p>
The integral of sin is -cos, which is seen in this image.

Square Wave Oscilloscope Reading:
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%205%20lab%204%20square.png">
</p>
The integral of a square is a triangular wave, which is seen here as Vi is a square while Vo is a triangle. 

Triangle Wave Oscilloscope Reading:
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%205%20lab%204%20triangle.png">
</p>
The integral of a triangle wave is a squiggle/segmented parabolas. We can see here that Vi is a triangular wave which is then integrated into a squiggly wave. 

_Circuit Six_:

Sine Wave Oscilloscope Reading:
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%206%20lab%204%20sine.png">
</p>
This op amp circuit makes Vo the derivative of Vi. In this image, Vi is a sine wave and Vo is the derivative of sine, cosine. 

Square Wave Oscilloscope Reading:
<p align="center">
  <img src="">
</p>
The derivative of a square wave is an impulse.

Triangle Wave Oscilloscope Reading:
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%206%20lab%204%20triangle.png">
</p>
The derivative of a triangular wave is a rectangular wave as seen in the relationship between Vi and Vo. 

How do these show it is differentiating?
## Discussion Questions:

### Part One:

**Compare the performance of each amplifier circuit to its expected theoretical performance with**
**regard to gain.**

Amplifying circuits 1-3 did not meet their expected theoretical performance with regard to gain. Circuit 1 was very close with only a 0.003 difference between the expected gain of 1 and the measured gain of 0.997. However, as the expected gain increased between circuits, the circuits were not able to keep up and meet these gains. Circuits 2 and 3 measured values of gains were lower than their expected values. Circuit 3 has the biggest difference between its expected gain value of 1500 and its measured gain value of 21.969. This is because we were not able to supply enough voltage to this circuit for the output voltage to differ from the input voltage by that degree. 

**Comment on the limits of op amp circuits with respect to maximum output voltage.**

We can see that these op amps are not ideal when we analyzed circuit two. In circuit two we used the DMM at one point to see that Vo reached a maximum voltage of 14.26, even though Vi continued to change as we changed the resistance in the potentiometer. This shows us that Vo maxed out at this point and that our op amp was saturated. 

Additionally, 15V was not sufficient to reach the expected gain value. We needed to supply more voltage to these circuits to get closer to the gain.

**Are the LM741 op amps symmetric i.e. does the positive voltage performance equal the**
**negative voltage performance?**

Yes, the positive voltage performance is equal to the negative voltage performance. This is because the Op Amp is a dual power supply Op Amp.

### Part Two:

**Did the integrating and differentiating circuits perform the mathematical operations expected?**
**Explain**

Yes, the integrating and differentiating circuits performed the mathematical operations that we expected. We observed a sin wave when integrating the circuit. This is supported due to the fact that the integral of sine is cosine. When the circuit was differentiated we observed a square graph which is the derivative and is the slope of the waved graph.


## Conclusions:

By the end of this lab, the better understanding of Op Amps was obtained and learned. On top of this the learning about the benefits and drawbacks of Op Amps were also obtained and learned. By using a unity gain, moderate gain, high gain inverting Op Amp circuits, as well as a voltage follower circuit, integrating Op Amp circuit, and differentiating Op Amp circuit we were able to form a better understanding of how gain can change due to resistance, current and voltage that are passing through the differing circuits.  
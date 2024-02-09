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

Circuit One: Unity Gain Inverting Op Amp

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/1-4.png">
</p>

Build the above unity gain inverting op amp with the 10k&Omega; potentiometer on the bread board. Connect to the two DCPS. While changing the resistance of the potentiometer, measure the Vo and the Vi at the labeled points in the circuit using the DMM. Swing the potentiometer from low to high resistance while recording the Vo and Vi values. We show our measured values and a plot of the measured value in our results.

Circuit Two: Moderate Gain Inverting Op Amp

Next, we constructed a moderate gain inverting op amp using different resistance values (8.2 k&Omega; and 330 k&Omega;) and connected it to two DCPS.

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/2-4.png">
</p>

Instead of using a potentiometer and the DMM to measure Vo and Vi values, we connected this circuit to the function generator and oscilloscope. We plotted Vi in channel one and Vo in channel two. From the oscilloscope, we could then measure and calculate the gain of the circuit. 

Circuit Three: High Gain Inverting Op Amp

Next. build a high gain inverting op amp on the bread board by using the 1k&Omega; and 1.5M&Omega; resistors. Connect this circuit to the DCPS along with the function generator and oscilloscope to measure and calculate the gain. 

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%203%20lab%204.png">
</p>

### Part Two:

Circuit Four: Voltage Follower

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%204%20lab%204.png">
</p>

Circuit Five: Integrating Op Amp
 
<p align="center">
  <img src="https://github.com/hrma240/Lab-3-attempt-3/blob/main/circuit%201%20redo%20lab%204.jpg">
</p>

Circuit Six: Differentiating Op Amp

<p align="center">
  <img src="https://github.com/hrma240/Lab-3-attempt-3/blob/main/circuit%201%20redo%20lab%204.jpg">
</p>

## Results:


### Part One:

Circuit One:

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
|   |     |


Circuit Two:

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%201%20lab%204.png">
</p>

| Expected Gain (Calculated) | Actual Gain (Measured) |
|:---:|---|
|   |     |

Circuit Three:

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%203%20lab%204.png">
</p>

| Expected Gain (Calculated) | Actual Gain (Measured) |
|:---:|---|
|   |     |

### Part Two:

Circuit Four:

<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%204%20lab%204.png">
</p>

Circuit Five:

10kHz
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%205%20lab%204%2010kHz.png">
</p>

Sine Wave
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%205%20lab%204%20sine.png">
</p>

Square Wave
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%205%20lab%204%20square.png">
</p>

Triangle Wave
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%205%20lab%204%20triangle.png">
</p>

Circuit Six:

Sine Wave
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%206%20lab%204%20sine.png">
</p>

Square Wave
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/Circuit%206%20lab%204%20square.png">
</p>

Triangle Wave
<p align="center">
  <img src="https://github.com/hrma240/Lab-4/blob/main/circuit%206%20lab%204%20triangle.png">
</p>

## Discussion Questions:

### Part One:

**Compare the performance of each amplifier circuit to its expected theoretical performance with**
**regard to gain.**

**Comment on the limits of op amp circuits with respect to maximum output voltage.**

**Are the LM741 op amps symmetric i.e. does the positive voltage performance equal the**
**negative voltage performance?**


Yes, the positive voltage performance is equal to the negative voltage performance. 

### Part Two:

**Did the integrating and differentiating circuits perform the mathematical operations expected?**
**Explain**


Yes, the integrating and differentiating circuits performed the mathematical operations that we expected. We observed a sin wave when integrating the circuit. This is supported due to the fact that the integral of sine is cosine. When the circuit was differentiated we observed a square graph which is the derivative and is the slope of the waved graph.


## Conclusions:


By the end of this lab, the better understanding of Op Amps was obtained and learned. On top of this the learning about the benefits and drawbacks of Op Amps were also obtained and learned. By using a unity gain, moderate gain, high gain inverting Op Amp circuits, as well as a voltage follower circuit, integrating Op Amp circuit, and differentiating Op Amp circuit we were able to form a better understanding of how gain can change due to resistance, current and voltage that are passing through the differing circuits.  
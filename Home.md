# Lab 4 Go Big: Operational Amplifiers

* Hannah Markwell
* Alexis Puckett

February 8, 2024

## Project Summary:

## Design/Methods:

For this lab we needed:
* A bread board
* Two DC Power supplies (DCPS)
* A Function Generator
* An Oscilloscope
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
  <img src="https://github.com/hrma240/Lab-3-attempt-3/blob/main/circuit%201%20redo%20lab%204.jpg">
</p>

Build the above unity gain inverting op amp with the 10k&Omega; potentiometer on the bread board. Connect to the two DCPS. While changing the resistance of the potentiometer, measure the Vo and the Vi at the labeled points in the circuit using the DMM. Swing the potentiometer from low to high resistance while recording the Vo and Vi values. We show our measured values and a plot of the measured value in our results.

Circuit Two: Moderate Gain Inverting Op Amp

Next, we constructed a moderate gain inverting op amp using different resistance values (8.2 k&Omega; and 330 k&Omega;) and connected it to two DCPS.

<p align="center">
  <img src="https://github.com/hrma240/Lab-3-attempt-3/blob/main/circuit%201%20redo%20lab%204.jpg">
</p>

Instead of using a potentiometer and the DMM to measure Vo and Vi values, we connected this circuit to the function generator and oscilloscope. We plotted Vi in channel one and Vo in channel two. From the oscilloscope, we could then measure and calculate the gain of the circuit. 

Circuit Three: High Gain Inverting Op Amp

Next. build a high gain inverting op amp on the bread board by using the 1k&Omega; and 1.5M&Omega; resistors. Connect this circuit to the DCPS along with the function generator and oscilloscope to measure and calculate the gain. 

<p align="center">
  <img src="https://github.com/hrma240/Lab-3-attempt-3/blob/main/circuit%201%20redo%20lab%204.jpg">
</p>

### Part Two:

Circuit Four: Voltage Follower

<p align="center">
  <img src="https://github.com/hrma240/Lab-3-attempt-3/blob/main/circuit%201%20redo%20lab%204.jpg">
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

Circuit Two:

Circuit Three:

### Part Two:

Circuit Four:

Circuit Five:

Circuit Six:

## Discussion Questions:

### Part One:

Compare the performance of each amplifier circuit to its expected theoretical performance with
regard to gain.

Comment on the limits of op amp circuits with respect to maximum output voltage.

Are the LM741 op amps symmetric i.e. does the positive voltage performance equal the
negative voltage performance?

### Part Two:

Did the integrating and differentiating circuits perform the mathematical operations expected?
Explain

## Conclusions:


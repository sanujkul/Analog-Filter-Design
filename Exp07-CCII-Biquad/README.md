# EXP 7: Current-mode biquad using a

# current conveyor (CC II+)

# (Lab Report by Sanuj Kulshrestha, 2017UEC2053, ECD07, Semester 6)

## AIM:

**1. Verify that the circuit shown in Figure 2 realizes a low pass, bandpass and high pass**
    **filter as follows:**
       **a. Low pass: i1 = i3 = 0, i2 = iin**
       **b. Band pass: i1 = i2 =0, i3 = iin**
       **c. High pass: i1 = -i2 and i3 = i1(R1/R2)(1 + C2/C1)
2. Discuss Limitations of the circuit
3. Comment upon if this is the only single CCII/single CFOA circuit which can realise**
    **an Universal filter?
4. Find out by searching the literature if there is any similar circuit known which can**
    **realise universal filter using a single CCII/CFOA in voltage mode i.e inputs and**
    **output both being voltages rather than currents?**


## 1. SPICE ANALYSIS

### a. LOW PASS

**Observation:**

1. At DC, Mag = -60.08 dB
2. At freq = 111 KHz, Mag = -63.08dB
3. Therefore, 3 db BW = 111 KHz
4. At 225 KHz, Magnitude is equal to -
    64dB, hence there is drop of 4dB from
    that of voltage at DC.


### b. BAND PASS

### Observations:

1. Centre frequency = 217 kHz
2. Left -3dB freq = 68 kHz
3. Right -3db freq = 68 kHz
4. BW = 603 kHz


### c. HIGH PASS

**Observations:**

1. 3dB cutoff frequency = 420 KHz


**Limitations of the circuit:**

1. For High pass response, there is too much dependencies among current sources.
2. Not adjustable filter parameters.
3. No feedback.

**Comment upon if this is the only single CCII/single CFOA circuit which can realise an
Universal filter?**
No this is not the only single CCII/single CFOA based Universal filters. Some of other
examples can be found in:

1. SUN, Y .-CH., HE, Y .-G. (2003) Active filters using single current conveyor.
2. Sharma, R. K., & Senani, R. (2004). _Universal current mode biquad using a single_
    _CFOA. International Journal of Electronics._
3. Sharma, R. K., & Senani, R. (2004). _On the Realization of Universal Current Mode_
    _Biquads Using a Single CFOA. Analog Integrated Circuits and Signal Processing._
    (This paper has 8 Current mode universal filters using single CFOA)

**Find out by searching the literature if there is any similar circuit known which can realise
universal filter using a single CCII/CFOA in voltage mode i.e inputs and output both being
voltages rather than currents?**

1. Kaçar, F., & Yeşil, A. (2009). _Voltage mode universal filters employing single_
    _FDCCII. Analog Integrated Circuits and Signal Processing._
    (This paper has 4 Voltage mode universal biquads using single Fully
    Differencial CCII)
2. Chen, H.-P. (2009). _Single CCII-based voltage-mode universal filter. Analog_
    _Integrated Circuits and Signal Processing_



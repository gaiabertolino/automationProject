# Fundamentals of Automatic Control: System Analysis and Control Design

#### Keywords

`Automatic Control`, `Linear Time-Invariant Systems`, `Transfer Function`, `Laplace Transform`, `System Stability`, `BIBO Stability`, `Time Response`, `Frequency Response`, `Bode Diagram`, `Control Design`, `MATLAB`.

This project focuses on the **analysis and control design of linear time-invariant (LTI) continuous-time systems**, combining theoretical derivations with numerical and graphical validation. The objective is to study the dynamic behavior of a system starting from its **time-domain response**, derive the corresponding **transfer function**, and design a **feedback control strategy** that satisfies given static and dynamic specifications.

The project covers both **time-domain analysis** (impulse, step, and ramp responses) and **frequency-domain analysis** (Bode diagrams), culminating in the design of a **simple-structure controller** enhanced with a **lead (anticipatory) compensator** to meet constraints on steady-state error, resonance peak, and bandwidth.

This project was developed as part of the coursework exam for the *Fundamentals of Automatic Control* course during the academic year **2020/2021**. 

---

### Key Features

* **LTI System Analysis**: Complete characterization through transfer functions, poles, and zeros
* **Stability Analysis**: BIBO stability verification via pole location
* **Time-Domain Responses**: Impulse, step, and ramp response computation and interpretation
* **Frequency-Domain Analysis**: Construction and discussion of Bode magnitude and phase diagrams
* **Control Design**: Design and validation of a lead compensator to meet performance specifications
* **MATLAB Validation**: Numerical and graphical verification using Control System Toolbox functions

---

### Project Structure

* **System Modeling**

  * Derivation of the **transfer function** from the system’s time response using Laplace transforms
  * Identification of **poles**, **zeros**, and system order

* **Time-Domain Analysis**

  * Computation of **free evolution modes** from pole decomposition
  * Analysis of **impulse response**, **step response**, and **ramp response**
  * Evaluation of steady-state values using the **Final Value Theorem**
  * Detection of phenomena such as **counter-phase response** and divergent ramp behavior

* **ARMA Modeling**

  * Derivation of a possible **ARMA (input–output) model** equivalent to the obtained transfer function

* **Frequency-Domain Analysis**

  * Manual and analytical construction of **Bode diagrams**
  * Identification of cutoff frequencies, resonance effects, and asymptotic approximations
  * Comparison between approximate and exact frequency responses

* **Control Design and Compensation**

  * Design of a **simple-structure controller** to ensure zero steady-state error to a step input
  * Static gain tuning to limit output error under load disturbances
  * Design of a **lead compensator** to satisfy:

    * Resonance peak ( M_r \leq 3 ) dB
    * Bandwidth ( 6 \leq \omega_{bw} \leq 13 ) rad/s
  * Verification of closed-loop stability and performance via Bode and frequency response plots
---

### Report

* **Technical Report (Italian)**:

  * Step-by-step theoretical derivations and analytical reasoning
  * Extensive graphical results for both time and frequency responses
  * Detailed control design procedure with ex-ante and ex-post validation

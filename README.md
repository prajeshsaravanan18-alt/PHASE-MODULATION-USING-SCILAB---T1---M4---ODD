# PHASE-MODULATION-USING-SCILAB---T1---M4---ODD


## Aim
To implement and analyze Phase Modulation (PM) using Scilab.

## Apparatus Required
1. **Software:** Scilab environment
2. **Hardware:** Personal Computer

---

## Theory
Phase Modulation (PM) is a technique where the phase of the carrier wave is varied in proportion to the instantaneous amplitude of the input signal (message signal). Unlike Frequency Modulation (FM), where the frequency is varied, in Phase Modulation, the phase angle of the carrier wave changes with the amplitude of the message signal.

### Mathematical Representation
The general form of a Phase Modulated signal $s(t)$ is given by:

$$s(t) = A_c \cos(2\pi f_c t + k_p m(t))$$

Where:
* $A_c$ : Amplitude of the carrier wave
* $f_c$ : Carrier frequency
* $m(t)$ : Message signal, typically $m(t) = A_m \cos(2\pi f_m t)$
* $k_p$ : Phase deviation sensitivity (in radians/volt)

---

## Algorithm
1. **Initialize Parameters:**
   * Define carrier amplitude ($A_c$), carrier frequency ($f_c$), message frequency ($f_m$), sampling frequency ($f_s$), and phase sensitivity ($k_p$).
2. **Generate Time Axis:**
   * Create a time array $t$ with suitable sampling steps over the signal duration.
3. **Generate Message Signal:**
   * Compute the message signal vector $m(t)$ using the cosine function.
4. **Generate Carrier Signal:**
   * Compute the unmodulated carrier signal vector $c(t) = A_c \cos(2\pi f_c t)$.
5. **Generate PM Signal:**
   * Compute the phase-modulated signal $s(t) = A_c \cos(2\pi f_c t + k_p m(t))$.
6. **Plot the Signals:**
   * Use Scilab's plotting commands (`subplot`, `plot`, `xtitle`, `xgrid`) to display message, carrier, and modulated signals.

---
## PROGRAM
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/72e2a698-b9db-4b6a-a164-4fb158fdc825" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/118ec81d-4249-4d82-a89f-ff3e6711020d" />

## TABULATION

<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/ed206bd8-7878-4f18-840f-3690f0227059" />

## CALCULATION
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/72f4daf9-e1f6-4190-a064-7abf34f2b9f3" />

## MODEL GRAPH
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/4ed60cb5-f354-4e74-b641-ba433912de98" />
## MARK SPLIT UP

<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/f3dbf4b4-6da0-49e8-8331-083720bce050" />

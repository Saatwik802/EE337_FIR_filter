# Low-Pass Digital FIR Filter  
**Course Project:** Microprocessors Lab (Apr 2024)  
**Guide:** Prof. Nikhil Karamchandani, Department of Electrical Engineering, IIT Bombay  

## Project Overview  
This project implements an **8-tap low-pass digital FIR (Finite Impulse Response) filter** with a **cutoff frequency of 2000 Hz**.  
The project was carried out as part of the *Microprocessors Lab* course, focusing on both **algorithm design** and **embedded implementation**.  

The complete workflow involved:
1. **Design & Testing** in Python (to verify filter coefficients and frequency response).  
2. **Embedded Implementation** in C (running on an **8051 microcontroller**).  
3. **PC–Microcontroller Communication** over USB-UART to send input samples and receive filtered output.  

---

## Features  
- **8-tap FIR filter** with pre-computed coefficients stored in microcontroller memory.  
- **2000 Hz cutoff frequency** designed for low-pass behavior.  
- **Python-based testing environment** for verification before hardware deployment.  
- **Real-time filtering** using 8051 microcontroller on Pt-51 board.  
- **Serial communication** with PC via USB-UART interface.

# Convolutional-Code-using-Viterbi-Algorithm

This project implements **convolutional encoding and decoding** using the **Viterbi algorithm** in MATLAB. The main focus is on both **hard decision** and **soft decision** decoding approaches. All the code is written in a MATLAB `.mlx` live script file.

## 📚 Overview

Convolutional coding is a key forward error correction technique used in digital communication systems. This project simulates the complete process of:

- Encoding random messages using convolutional codes
- Transmitting over a noisy channel
- Decoding using the Viterbi algorithm
- Comparing hard and soft decision decoding
- Analyzing performance metrics and bit error rates

## 🧪 Case Studies

Three configurations were tested to observe performance differences:

1. **Rate R = 1/2**, Constraint Length Kc = 3  
2. **Rate R = 1/3**, Constraint Length Kc = 4  
3. **Rate R = 1/3**, Constraint Length Kc = 6

## 🛠️ Features

- ✅ General **encoding function** for any generator polynomial and rate  
- ✅ **Hard decision decoding** using the Viterbi algorithm  
- ✅ **Soft decision decoding** with improved performance over noisy channels  
- ✅ Bit error rate (BER) comparison between input and decoded messages  
- ✅ Customizable parameters for encoding rate, constraint length, and noise level

## 📁 Files Included


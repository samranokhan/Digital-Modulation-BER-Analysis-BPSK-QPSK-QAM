📡 BER Performance Analysis of Digital Modulation Schemes using MATLAB & Simulink
📌 Project Overview

This project presents a comparative performance analysis of common digital modulation techniques — BPSK, QPSK, 16-QAM, and 64-QAM — in terms of Bit Error Rate (BER) under an Additive White Gaussian Noise (AWGN) channel.

The system is implemented and simulated using MATLAB & Simulink, and constellation diagrams are analyzed to study the effect of noise on different modulation orders.

🎯 Objectives

To analyze and compare the BER performance of:

BPSK

QPSK

16-QAM

64-QAM

To visualize constellation diagrams under noisy conditions

To study the trade-off between data rate and noise immunity

To validate theoretical concepts of digital communication through simulation

🧠 Modulation Techniques Used
🔹 BPSK (Binary Phase Shift Keying)

1 bit per symbol

Highest noise immunity

Lowest BER

Used in highly noisy channels

🔹 QPSK (Quadrature Phase Shift Keying)

2 bits per symbol

Good balance between data rate and reliability

Widely used in wireless systems

🔹 16-QAM

4 bits per symbol

Higher data rate

Moderate BER performance

🔹 64-QAM

6 bits per symbol

Very high data rate

Requires high SNR due to noise sensitivity

🛠 Tools & Technologies

MATLAB

Simulink

Digital Communication Toolbox

AWGN Channel

Constellation Diagram Analyzer

Error Rate Calculation Block

⚙️ System Model (Simulink)

Each modulation scheme consists of:

Random Integer Generator

Modulator (BPSK / QPSK / QAM)

AWGN Channel

Demodulator

Error Rate Calculation

Constellation Diagram Visualization

📊 Results & Observations

BPSK shows the lowest BER due to maximum symbol spacing

QPSK offers improved data rate with low BER

16-QAM provides higher throughput at the cost of increased BER

64-QAM achieves the highest data rate but is highly sensitive to noise

As the modulation order increases, BER increases, while noise immunity decreases.

📈 Performance Comparison
Modulation	Bits/Symbol	Noise Immunity	BER	Data Rate
BPSK	1	Very High	Lowest	Low
QPSK	2	High	Low	Medium
16-QAM	4	Medium	Moderate	High
64-QAM	6	Low	Highest	Very High
🌐 Applications

Wireless Communication Systems

4G / 5G Cellular Networks

Wi-Fi (IEEE 802.11)

Satellite Communication

Digital Broadcasting
👨‍🎓 Author

Samran Nawar Khan
Electrical Engineering (Communication Systems)
Semester Project – Digital Communication

🔑 Keywords

BPSK QPSK QAM 16QAM 64QAM BER Digital Modulation
MATLAB Simulink Wireless Communication Signal Processing

⭐ Note

This project is intended for academic learning and simulation purposes and demonstrates practical implementation of digital modulation techniques studied in communication systems.

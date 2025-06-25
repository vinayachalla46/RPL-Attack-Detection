# RPL-Attack-Detection

#Overview
This project focuses on the Prediction and Detection of RPL-based Attacks in IoT networks using Cooja Simulator, Wireshark, and Machine Learning techniques. It simulates RPL routing protocol vulnerabilities and applies anomaly detection to identify malicious behavior within the network.

#Objective
Simulate RPL attacks (Blackhole, Version Number Increase Attack, Decreased Rank Attack) in Contiki OS using Cooja.

Capture and convert simulation logs using Wireshark to generate CSV datasets.

Analyze and visualize the network behavior using MATLAB.

Apply Autoencoder and Isolation Forest algorithms for attack detection.

Evaluate using performance metrics: Latency, Delay, Throughput, Jitter, and PDR.

#Technologies Used
Category	Tools/Tech Stack
Simulation	Cooja (Contiki OS)
Data Capture	Wireshark
Data Processing	Python, CSV conversion
Visualization	MATLAB
ML Algorithms	Autoencoder, Isolation Forest
Metrics Evaluation	Python, MATLAB

#Simulated Attacks
Attack Type	Description
Blackhole Attack	Malicious node drops all packets instead of forwarding them.
Version Number Increase	Node artificially increases version number to attract traffic.
Decreased Rank Attack	Node advertises lower rank to become a preferred parent.

#Results
Successfully detected anomalies with high accuracy.

Autoencoder performed well in capturing deviations.

Visualizations showed clear impact of attacks on:

Throughput

Packet Delivery Ratio

Network Delay

Jitter

#How to Use
Clone the Repository:
git clone https://github.com/yourusername/RPL-Attack-Detection.git
cd RPL-Attack-Detection
Run Simulations:
Open .csc files in Cooja to simulate different attacks.
Capture Traffic:
Use Wireshark to convert .pcap to .csv.
Run ML Detection:
cd ml_models
python autoencoder_model.py
View Results:
Plots and detection metrics will be stored in results/.

#References
Contiki OS Documentation

IEEE Papers on RPL vulnerabilities

Wireshark & Cooja tutorials

Scikit-learn & TensorFlow for ML implementation

#Author
Vinaya Challa
B.Tech Final Year, CSE
Contact: http://www.linkedin.com/in/vinaya-challa-899a44253 | vinayachalla4632@gmail.com

#License
This project is open-source and available under the MIT License.

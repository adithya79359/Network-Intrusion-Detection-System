# Network Intrusion Detection System

A Python-based **Network Intrusion Detection System (NIDS)** designed to capture and analyze network traffic and help identify suspicious or anomalous network activity.

The project uses **Scapy** for packet capture and Python data-science and machine-learning libraries for traffic analysis.

## 📌 Project Overview

A Network Intrusion Detection System monitors network traffic to identify potentially suspicious activities.

This project captures live network packets and extracts useful information such as:

* Source IP address
* Destination IP address
* Network protocol
* Packet size
* TCP traffic
* UDP traffic

The captured network information can then be processed and analyzed for abnormal network behavior.

## 🚀 Features

* Real-time network packet capture
* Source and destination IP identification
* TCP packet detection
* UDP packet detection
* Packet size monitoring
* Network traffic analysis
* Data processing using Pandas and NumPy
* Machine learning support using Scikit-learn
* Network data visualization using Matplotlib

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Scapy**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**

## 📦 Required Libraries

Install the required Python libraries using:

```bash
pip install scapy pandas numpy scikit-learn matplotlib
```

For Jupyter Notebook, you can also run:

```python
!pip install scapy pandas numpy scikit-learn matplotlib
```

## 🖥️ Windows Requirement

Scapy requires a packet capture driver to capture network packets on Windows.

Install **Npcap** before running the packet-sniffing section of the project.

During Npcap installation, enabling **WinPcap API-compatible Mode** may help with Scapy compatibility.

Depending on your Windows configuration, Jupyter Notebook or the terminal may also need to be run with administrator privileges for packet capture.

## 📂 Project Structure

```text
Network-Intrusion-Detection-System/
│
├── Network_Intrusion_Detection_System.ipynb
├── README.md
├── .gitignore
└── LICENSE
```

## ⚙️ How to Run

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Open the project folder

```bash
cd Network-Intrusion-Detection-System
```

### 3. Install dependencies

```bash
pip install scapy pandas numpy scikit-learn matplotlib
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```text
Network_Intrusion_Detection_System.ipynb
```

Run the notebook cells sequentially.

## 📡 Packet Capture

The project uses Scapy to capture network packets.

A basic packet capture includes information such as:

```text
Source IP -> Destination IP Protocol Packet Size
```

Example:

```text
192.168.1.5 -> 142.250.183.206 TCP 66
142.250.183.206 -> 192.168.1.5 TCP 1500
192.168.1.5 -> 8.8.8.8 UDP 74
```

This information provides the foundation for analyzing network communication patterns.

## 🔄 Workflow

```text
Network Traffic
      ↓
Packet Capture
      ↓
Feature Extraction
      ↓
Data Processing
      ↓
Traffic Analysis
      ↓
Anomaly / Suspicious Activity Detection
      ↓
Visualization
```

## 🎯 Objective

The main objective of this project is to understand how network traffic can be captured, processed, and analyzed using Python and machine-learning techniques.

The project also provides practical experience with:

* Computer Networks
* Cybersecurity
* Packet Analysis
* Python Programming
* Data Analysis
* Machine Learning

## ⚠️ Disclaimer

This project is intended for **educational and cybersecurity learning purposes only**.

Only capture or analyze network traffic on systems and networks that you own or have explicit permission to monitor.

## 🔮 Future Improvements

Possible future improvements include:

* Real-time intrusion alerts
* Detection of different attack categories
* Improved machine-learning models
* Network traffic dashboard
* Live traffic visualization
* Automatic logging of suspicious packets
* Model performance evaluation
* Exporting intrusion reports
* Web-based monitoring interface

## 📄 License

This project is licensed under the **MIT License**.

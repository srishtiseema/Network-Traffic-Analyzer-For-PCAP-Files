# Network-Traffic-Analyzer-For-PCAP-Files
Network Traffic Analyzer for PCAP Files is a tool that analyzes captured network packets to monitor traffic and detect anomalies. It extracts details like IPs, ports, and protocols to provide insights, helping in troubleshooting, security analysis, and identifying suspicious network behavior.

# 🚀 Features
Analyze network traffic from PCAP files
Calculate total bandwidth usage
Visualize protocol distribution
Identify top communicating IP addresses
Detect potential port scanning activities

# Future Enhancements
Graph-based visualization for IP traffic patterns
Advanced metrics: latency, packet loss, throughput, jitter, network utilization, and error rates

# Installation
Clone the repository
Navigate to the project directory:
cd network-traffic-analyzer

# Install dependencies:
pip install -r requirements.txt

# Usage

Run the following command to analyze a PCAP file:
python Network_traffic_analyzer.py <path_to_pcap_file> <port_scan_threshold>

Replace <path_to_pcap_file> with your file path and <port_scan_threshold> with the desired threshold for port scan detection.



# Acknowledgments
- Scapy for packet processing
- Pandas for data analysis
- Matplotlib for visualization

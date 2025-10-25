\# AI Traffic Analyzer



\*\*Owner:\*\* Juan Sebastián Balcero De La Roche  

\*\*Timeline:\*\* Week 1 (Oct 19 – 25, 2025)  

\*\*Goal:\*\* Build an AI-assisted network-traffic analyzer that detects suspicious patterns (port scans, abnormal bursts) using machine learning.



\## Phase 1 – Data Capture + CSV Export

\- Capture network traffic with Wireshark  

\- Export traffic to CSV  

\- Prepare features: source IP, dest IP, protocol, port, length, timestamp  

\- Feed the data into ML models in Phase 2



\### Current Status (Oct 24 2025)

\- ✅ Repo initialized  

\- ✅ Folder structure created (`data/`, `src/`, `notebooks/`)  

\- ✅ Wireshark ready for capture



\### Next Steps

1\. Capture baseline traffic (`normal\_traffic\_oct24.pcapng`)  

2\. Export CSV (`normal\_traffic\_oct24\_raw.csv`)  

3\. Write Python parser (`src/parse\_pcap.py`)  

4\. Train simple model in Phase 2




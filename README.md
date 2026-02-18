# Net-Sentinel-lightweight-IDS
A Python rule-based Intrusion Detection System for small networks.
# NET-SENTINEL
### Lightweight Rule-Based Intrusion Detection System for Small Networks

A lightweight, rule-based Intrusion Detection System (IDS) designed for resource-constrained environments such as Raspberry Pi and small office networks.

Built using Python, Scapy, Flask, and iptables.

## 📌 Project Overview

NET-SENTINEL is a lightweight intrusion detection and response system developed to protect small networks against high-volume traffic attacks such as Distributed Denial of Service (DDoS).

Unlike enterprise IDS solutions that require powerful hardware and complex configurations, NET-SENTINEL focuses on:

- Low CPU and memory usage
- Simple threshold-based detection logic
- Human-readable alerts
- Real-time dashboard monitoring
- Automatic IP blocking using iptables
- Lightweight CSV-based logging

The system was developed and tested in a controlled virtual environment simulating real-world attack conditions.

## 🎯 Why I Built This

This was my first cybersecurity engineering project during my Computer Networks and Cybersecurity degree.

The goal was to explore how effective intrusion detection systems could be implemented on low-resource hardware such as Raspberry Pi, while maintaining usability for non-technical users.

This project demonstrates:

- Network traffic analysis
- Threshold-based detection design
- Real-time alert generation
- Incident response simulation
- Performance optimization under constrained resources

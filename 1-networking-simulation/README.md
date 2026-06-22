# Networking Simulation Project

## Overview
This project involves the end-to-end design, implementation, and performance analysis of an enterprise-scale core network using a redundant 4-router mesh topology. It focuses on foundational network engineering, dynamic routing, and deep packet behavior under stress.

## Key Objectives
- Engineer a scalable IP schema utilizing Variable Length Subnet Masking (VLSM).
- Deploy and verify a dynamic OSPF (Area 0) routing infrastructure across a multi-node backbone.
- Analyze Layer-3 packet fragmentation behavior across mismatched MTU boundaries.

## Contents
- `project-report.pdf` - Full project report including routing tables, configurations, and fragmentation math logs.
- ['diagrams/'](./diagrams//) - Network topology diagrams and structural visualizations.

## Technologies Used
- Cisco IOS Routing & Switching
- OSPF (Open Shortest Path First)
- Network Simulators (e.g., Cisco Packet Tracer / GNS3)

## Results/Findings
Successfully established a fault-tolerant diamond routing topology with predictable path costs. Fragmentation stress-testing validated proper IPv4 header adjustments—specifically tracking 'More Fragments' (MF) flags and offset calculations—across 1400, 700, and 300-byte MTU limits.

## Course Information
- Course: COS372
- University: [Your University]
- Date: [Month, Year]

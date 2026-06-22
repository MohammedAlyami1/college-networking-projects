# VPC Networks Project

## Overview
The architectural design and deployment planning of a highly available, secure, and production-ready enterprise public cloud infrastructure utilizing a multi-tier Virtual Private Cloud (VPC).

## Key Objectives
- Architect a multi-tier network segmenting public-facing edge resources from private application and database layers.
- Implement robust perimeter security using stateful and stateless traffic controls.
- Design secure outbound internet transit pathways for isolated subnets.

## Contents
- `vpc-documentation.pdf` - Full project report detailing IP CIDR allocations, routing pathways, and security definitions.
- `configurations/` - Architectural visual blueprints and resource maps.

## Technologies Used
- Cloud Infrastructure as a Service (IaaS)
- Virtual Private Cloud (VPC) Routing
- Network Access Control Lists (NACLs) & Security Groups
- NAT Gateways & Bastion Hosts

## Results/Findings
Designed a highly resilient, Multi-Availability Zone architecture. The implementation ensures strict zero-trust boundaries where backend databases are completely shielded from public access, relying on precise Security Group rules and managed NAT gateways for secure operational maintenance.

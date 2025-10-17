# Name: Nandavelan SPS

# Reg no: 212223060182


# CASE-STUDY-

Case Study Title: Resource Allocation and Cost Optimization in an OpenStack Private Cloud

Case Overview:

ABC Cloud Services runs a private cloud using OpenStack to host virtual machines (VMs) for internal development, testing, and production workloads. Their cloud infrastructure comprises:

5 Compute Nodes, each with:
64 vCPUs
256 GB RAM
2 TB SSD storage
OpenStack Services Deployed:
Nova (Compute)
Neutron (Networking)
Cinder (Block Storage)
Glance (Image Management)
Keystone (Identity)
Horizon (Dashboard)
Heat (Orchestration)

They are considering expanding their cloud but want to first evaluate current capacity usage, VM density, and cost efficiency. The goal is to calculate whether their resource usage aligns with business needs and how to optimize it.

Case Study Questions – OpenStack Calculation in Cloud Computing

1. Resource Utilization:

Based on the current infrastructure, what is the total available compute capacity in terms of:
Total vCPUs
Total RAM
Total storage

2.Storage Allocation:

Given 10 TB of total block storage across the cloud, how many VMs can be supported if:
a) Each VM is allocated 100 GB block storage
b) Snapshot storage consumes 20% extra on average

**SOLUTIONS:**

# CASE-STUDY-

Case Study Title: Resource Allocation and Cost Optimization in an OpenStack Private Cloud

Case Overview:

ABC Cloud Services runs a private cloud using OpenStack to host virtual machines (VMs) for internal development, testing, and production workloads. Their cloud infrastructure comprises:

5 Compute Nodes, each with:
64 vCPUs
256 GB RAM
2 TB SSD storage
OpenStack Services Deployed:
Nova (Compute)
Neutron (Networking)
Cinder (Block Storage)
Glance (Image Management)
Keystone (Identity)
Horizon (Dashboard)
Heat (Orchestration)

They are considering expanding their cloud but want to first evaluate current capacity usage, VM density, and cost efficiency. The goal is to calculate whether their resource usage aligns with business needs and how to optimize it.

Case Study Questions – OpenStack Calculation in Cloud Computing

1. Resource Utilization:

Based on the current infrastructure, what is the total available compute capacity in terms of:
Total vCPUs
Total RAM
Total storage

2.Storage Allocation:

Given 10 TB of total block storage across the cloud, how many VMs can be supported if:
a) Each VM is allocated 100 GB block storage
b) Snapshot storage consumes 20% extra on average

**SOLUTIONS:**
 ### Problem 1:

 A company uses AES-256 encryption to secure its data before
 uploading it to the cloud. It takes 0.05 seconds to encrypt 1 MB of data.

 Q: How long will it take to encrypt 2 TB of data before upload?

 Solution:

 • 1 TB = 1024 GB
 • 1 GB = 1024 MB
 • 2 TB = 2 × 1024 × 1024 MB = 2,097,152 MB
 • Time per MB = 0.05 seconds
 • Total Time = 2,097,152 × 0.05 = 104,857.6 seconds (≈ 29.13 hours)

 ### Problem 2:
 
 A VM is allocated 8 vCPUs, but only uses 5.5 vCPUs on average.

Q: What is the CPU utilization efficiency?

 Solution:

 • Allocated vCPUs = 8
 • Used vCPUs = 5.5
 • Efficiency = (5.5 / 8) × 100 = 68.75%
 
### Problem 3:

 A cloud server has a maximum bandwidth of 1 Gbps, but during peak
 hours it only uses 600 Mbps.
 
 Q: What is the network throughput efficiency?
 
 Solution:
 
 • Max bandwidth = 1000 Mbps
 • Used bandwidth = 600 Mbps
 • Efficiency = (600 / 1000) × 100 = 60%
 
### Problem 4:

 Two cloud setups process the same workload:
 Setup A uses 500W for 2 hours.
 Setup B uses 300W for 3.5 hours.
 
Q: Which setup is more energy-efficient?

 Solution:
 
 • Setup A: 500W × 2h = 1000 Wh
 • Setup B: 300W × 3.5h = 1050 Wh
 • More efficient setup = Setup A
 
### Problem 5:

 CPU Utilization Efficiency
 A physical server has 16 cores and each VM uses 2 cores. CPU
 utilization is optimal at 75%.
 
 Q: What is the maximum number of VMs that can be efficiently
 hosted?
 
 Solution:
 
 • Total cores = 16
 • Optimal utilization = 75% of 16 = 12 cores
 • Each VM uses 2 cores
 • Max VMs = 12 / 2 = 6 VMs

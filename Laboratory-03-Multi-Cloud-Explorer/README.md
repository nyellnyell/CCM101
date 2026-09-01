
# Laboratory 03: Multi-Cloud Explorer

## Checkpoint 7 – Linux Server Investigation

### System System Information

1. **Operating System:**
   * **Command:** `cat /etc/os-release`
   * **Details:** Ubuntu 22.04 LTS (or your KillerCoda OS output)

2. **CPU Information:**
   * **Command:** `lscpu`
   * **Details:** [Insert CPU Model, e.g., AMD EPYC / Intel Xeon, x Core(s)]

3. **Memory Information:**
   * **Command:** `free -h`
   * **Details:** [Insert Total RAM, e.g., 4.0Gi Total, X.XGi Used, X.XGi Free]

4. **Disk Space:**
   * **Command:** `df -h`
   * **Details:** [Insert Root `/` Disk Size, e.g., 30Gi Total, X.XGi Used]

---

### Terminal Output Screenshots

![Linux Terminal Investigation](screenshots/linux-investigation.png)


---

### Cloud Migration Analysis

**Question:** *If this Linux server were migrated to the cloud, which AWS, Azure, and GCP services could host it?*

If this Linux server instance were migrated to the cloud as an Infrastructure-as-a-Service (IaaS) virtual machine, it could be hosted on the following services:

* **Amazon Web Services (AWS):** **Amazon EC2 (Elastic Compute Cloud)** — An Amazon Machine Image (AMI) running Linux (such as Ubuntu or Amazon Linux) can be launched on an EC2 instance type matching the server's CPU and RAM specifications, using Elastic Block Store (EBS) for persistent storage.
* **Microsoft Azure:** **Azure Virtual Machines** — A Linux-based Azure VM (e.g., Ubuntu Server instance) configured with matching vCPUs, RAM, and Azure Managed Disks for storage.
* **Google Cloud Platform (GCP):** **Google Compute Engine (GCE)** — A Compute Engine VM instance running a Linux OS image tailored with custom or standard machine types matching the hardware resources.

# Laboratory 02: Build the Cloud Infrastructure Blueprint

## Mission Overview
In this laboratory activity, an investigation of cloud infrastructure components was conducted using a cloud-hosted Linux server environment provided by KillerCoda. Core hardware and software system specifications were inspected, basic infrastructure components were mapped to public cloud service abstractions (AWS, Azure, GCP), and technical documentation was authored within a structured GitHub portfolio repository.

## Objectives
* Identify and explain the major physical and virtual components of cloud infrastructure.
* Investigate Linux system properties, hardware metrics, and network interfaces using cmmand-line diagnostic tools.
* Differentiate core cloud service categories: compute, storage, networking, and identity management.
* Compare equivalent infrastructure offerings from major cloud vendors (AWS, Azure, GCP).
* Construct clear technical documentation using standard Markdown formatting.

## Cloud Infrastructure Components
* **Compute:** Processing nodes and runtime memory units (CPUs and RAM) responsible for executing application logic and system tasks.
* **Storage:** Non-volatile block, object, and file storage systems used to persist operating system images, application code, and user data.
* **Networking:** Digital communication channels, IP interfaces, subnets, and routing rules that connect client endpoints with backend server workloads.
* **Identity and Access Management (IAM):** Authentication and authorization framework that controls access permissions across cloud resources.

## Tools Used
* **KillerCoda Playground:** Cloud-hosted Linux terminal environment.
* **Linux CLI Utilities:** System inspection tools (`cat`, `uname`, `lscpu`, `free`, `df`, `ip`).
* **GitHub:** Portfolio repository hosting and version control.
* **Diagramming Tool (Excalidraw / Draw.io / Figma):** Visual cloud architecture diagram creator.

## Linux Commands Executed
* `hostname`: Retreived the system network hostname.
* `cat /etc/os-release`: Displayed detailed Linux operating system distribution information.
* `uname -r`: Printed the active Linux kernel release version.
* `lscpu`: Queried detailed CPU architecture, core count, and processor model specifications.
* `free -h`: Examined total, used, and available system RAM memory.
* `df -h`: Inspected disk volume capacities, storage utilization, and filesystem mount points.
* `ip a`: Listed network interface configurations, MAC addresses, and assigned IP addresses.

## Skills Learned
* Inspecting virtualized hardware resources within cloud-hosted Linux nodes using terminal utilities.
* Mapping low-level system properties to abstract public cloud service offerings across AWS, Azure, and GCP.
* Structuring technical engineering documentation and reports using Git and Markdown.

## Challenges Encountered
* Distinguishing between virtualized cloud hardware allocations and physical host hardware parameters during Linux terminal inspection.
* Formatted multi-column comparison tables and Markdown layouts for clear presentation in GitHub documentation.

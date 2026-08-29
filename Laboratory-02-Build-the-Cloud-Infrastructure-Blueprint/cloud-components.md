# Cloud Infrastructure Components Analysis

## 1. Compute Resources
* **Description & Purpose:** Compute resources consist of the physical or virtualized processing units (CPUs) and primary system memory (RAM) responsible for running software instructions and managing application state.
* **Importance in Cloud Computing:** Compute forms the core execution layer of cloud workloads, enabling dynamic scaling (horizontal or vertical) to match changing traffic requirements on demand.
* **Relation to KillerCoda Environment:** Represented by the single-core **Intel Xeon E312xx CPU** and **1.9 GiB RAM** (`Mem: 1.9Gi`) observed during system investigation.

## 2. Storage Resources
* **Description & Purpose:** Storage resources provide non-volatile persistence for operating system files, databases, application assets, and application logs across execution cycles[cite: 1].
* **Importance in Cloud Computing:** Decouples persistent state from transient compute instances, enabling stateless compute scaling without data loss.
* **Relation to KillerCoda Environment:** Observed via the primary virtual block storage device **`/dev/vda1`** (19 GiB capacity formatted as `ext4`) mounted on root (`/`), along with virtual memory file systems like `tmpfs`[cite: 1].

## 3. Networking Resources
* **Description & Purpose:** Networking resources establish communication paths, subnets, IP routing tables, and interface bindings between client applications, external users, and backend microservices[cite: 1].
* **Importance in Cloud Computing:** Enables isolated Virtual Private Clouds (VPCs), safe cross-node communication, load balancing, and network perimeters.
* **Relation to KillerCoda Environment:** Identified through the active network interfaces: loopback (`lo`), primary network interface **`enp1s0`** (IP `172.30.1.2/24`), and the virtual bridge interface **`docker0`** (`172.17.0.1/16`)[cite: 1].

## 4. Operating System
* **Description & Purpose:** The operating system acts as an abstraction bridge between hardware components and application software, scheduling processes and allocating system memory[cite: 1].
* **Importance in Cloud Computing:** Serves as the base environment for container runtimes, hypervisors, and cloud application deployments.
* **Relation to KillerCoda Environment:** Provided by **Ubuntu 24.04.4 LTS (Noble Numbat)** running Linux Kernel **`6.8.0-138-generic`** inside the sandbox[cite: 1].

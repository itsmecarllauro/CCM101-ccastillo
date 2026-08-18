# Cloud Infrastructure Components

## Compute Resources
**Purpose:** Compute resources provide the processing power needed to run applications and services. In this Linux environment, the CPU (1 core, Intel Xeon E312xx) serves as the compute resource that executes all commands and processes.
**Importance in Cloud Computing:** Compute resources are the foundation of cloud services — they run virtual machines, containers, and applications that businesses depend on.
**Relation to KillerCoda:** The KillerCoda playground itself runs as a virtual machine with allocated CPU resources, simulating a real cloud compute instance.

## Storage Resources
**Purpose:** Storage resources hold data, files, and system information persistently, even after a program stops running.
**Importance in Cloud Computing:** Storage is essential for saving user data, application files, and backups in the cloud, ensuring data is available whenever needed.
**Relation to KillerCoda:** The disk mounted as the root filesystem (`/dev/vda1`) represents the storage resource available in this environment, similar to how cloud providers offer block storage volumes.

## Networking Resources
**Purpose:** Networking resources allow communication between systems, users, and services over the internet or private networks.
**Importance in Cloud Computing:** Networking connects cloud resources to each other and to end users, enabling data transfer, remote access, and service availability.
**Relation to KillerCoda:** The assigned hostname and IP address in this playground represent the networking layer that allows the terminal session to communicate with KillerCoda's servers.

## Operating System
**Purpose:** The operating system manages hardware resources and provides an environment for running applications.
**Importance in Cloud Computing:** The OS is the platform on which cloud services are deployed — it manages compute, storage, and networking resources together.
**Relation to KillerCoda:** This environment runs Ubuntu 24.04, a common Linux distribution used in many real-world cloud deployments due to its stability and wide support.

# SailexOS Design Goals

---

* Microkernel architecture
* Objects in the OS are majority Rust objects
* Multi-User experience
* URIS
    * ex: Devices are located at dev://
    * ex: Processes are located at proc://
    * ex: File namespaces are located at file://

# 1.0 Requirements

---

* Boot on x86_64 hardware
* Able to display test and graphics via graphics adapter
* Networking implementation
* Command Line Interface
* Memory management
* Filesystem - *Looking at ext4*
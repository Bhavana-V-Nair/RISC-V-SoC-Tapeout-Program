# Week0 - Task0: Setup & Documentation

## 📌 Introduction
This task involves:
1. Creating a GitHub repository to track progress.
2. Documenting the summary of the provided video.
3. Installing the required tools inside an Ubuntu 20.04+ VM.

---

## 📝 Video Summary

The introductory video provided an overview of the RISC-V SoC Tapeout Program and explained the importance of documenting each step of the learning journey. It emphasized creating a GitHub repository to track progress week by week, using a clear folder structure for different tasks.

The session also highlighted the set of tools required for digital design and verification, such as **Yosys**, **Icarus Verilog**, **GTKWave**, **Ngspice**, **Magic**, and **OpenLANE**. Each tool plays a role in the end-to-end ASIC design flow—from synthesis to simulation and layout.

Additionally, the video guided participants on setting up a proper working environment using **Ubuntu 20.04+** in **VirtualBox**, with the necessary system specifications (6GB RAM, 50GB storage, 4 vCPUs). It stressed the importance of verifying tool installations by checking versions and capturing snapshots as proof.

Overall, the key message was:  
- Create and maintain a structured GitHub repo.  
- Install and verify essential EDA tools.  
- Document the process clearly with commands, outputs, and screenshots.  


---

## 🖥️ System Setup
- **OS**: Ubuntu 20.04 (running on Oracle VirtualBox)
- **RAM**: 6 GB  
- **CPU**: 4 vCPUs  
- **Disk**: 50 GB  

---

## 🔧 Tools to be Installed
- Yosys  
- Icarus Verilog (iverilog)  
- GTKWave  
- Ngspice  
- Magic  
- OpenLANE (with Docker)  

---

### ✅ Yosys
```bash
sudo apt update
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make build-essential clang bison flex libreadline-dev gawk tcl-dev libffi-dev git graphviz xdot pkg-config python3 libboost-system-dev libboost-python-dev libboost-filesystem-dev zlib1g-dev -y
make config-gcc
make
sudo make install
yosys --version
---
  GNU nano 8.3                                                                                        README.md                                                                                         Modified

Overall, the key message was:
- Create and maintain a structured GitHub repo.
- Install and verify essential EDA tools.
- Document the process clearly with commands, outputs, and screenshots.


---

##  M-%️ System Setup
- **OS**: Ubuntu 20.04 (running on Oracle VirtualBox)
- **RAM**: 6 GB
- **CPU**: 4 vCPUs
- **Disk**: 50 GB

---

##  M-' Tools to be Installed
- Yosys
- Icarus Verilog (iverilog)
- GTKWave
- Ngspice
- Magic
- OpenLANE (with Docker)

---

### ✅ Yosys
```bash
sudo apt update
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make build-essential clang bison flex libreadline-dev gawk tcl-dev libffi-dev git graphviz xdot pkg-config python3 libboost-system-dev libboost-python-dev libboost-filesystem-dev zlib1g-dev -y
make config-gcc
make
sudo make install
yosys --version
---


  GNU nano 8.3                                                                                        README.md                                                                                         Modified

Overall, the key message was:
- Create and maintain a structured GitHub repo.
- Install and verify essential EDA tools.
- Document the process clearly with commands, outputs, and screenshots.


---

##  M-%️ System Setup
- **OS**: Ubuntu 20.04 (running on Oracle VirtualBox)
- **RAM**: 6 GB
- **CPU**: 4 vCPUs
- **Disk**: 50 GB

---

##  M-' Tools to be Installed
- Yosys
- Icarus Verilog (iverilog)
- GTKWave
- Ngspice
- Magic
- OpenLANE (with Docker)

---

### ✅ Yosys
```bash
sudo apt update
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make build-essential clang bison flex libreadline-dev gawk tcl-dev libffi-dev git graphviz xdot pkg-config python3 libboost-system-dev libboost-python-dev libboost-filesystem-dev zlib1g-dev -y
make config-gcc
make
sudo make install
yosys --version
---


###✅ Icarus Verilog
```bash
sudo apt update
sudo apt install iverilog -y
iverilog -V


---
###✅ GTKWave
```bash
sudo apt update
sudo apt install gtkwave -y
gtkwave --version

---

###✅ Ngspice
```bash
wget https://sourceforge.net/projects/ngspice/files/ng-spice-rework/37/ngspice-37.tar.gz
tar -zxvf ngspice-37.tar.gz
cd ngspice-37
mkdir release && cd release
../configure --with-x --with-readline=yes --disable-debug
make
sudo make install
ngspice --version
cd ../..

---

###✅ Magic
```bash
sudo apt-get install m4 tcsh csh libx11-dev tcl-dev tk-dev libcairo2-dev mesa-common-dev libglu1-mesa-dev libncurses-dev -y
git clone https://github.com/RTimothyEdwards/magic
cd magic
./configure
make
sudo make install
magic -v
cd ..
----
^G Help          ^O Write Out     ^F Where Is      ^K Cut           ^T Execute       ^C Location      M-U Undo         M-A Set Mark     M-] To Bracket   M-B Previous     ◂ Back           ^◂ Prev Word
^X Exit          ^R Read File     ^\ Replace       ^U Paste         ^J Justify       ^/ Go To Line    M-E Redo         M-6 Copy         ^B Where Was     M-F Next         ▸ Forward        ^▸ Next Word


















^G Help          ^O Write Out     ^F Where Is      ^K Cut           ^T Execute       ^C Location      M-U Undo         M-A Set Mark     M-] To Bracket   M-B Previous     ◂ Back           ^◂ Prev Word
^X Exit          ^R Read File     ^\ Replace       ^U Paste         ^J Justify       ^/ Go To Line    M-E Redo         M-6 Copy         ^B Where Was     M-F Next         ▸ Forward        ^▸ Next Word


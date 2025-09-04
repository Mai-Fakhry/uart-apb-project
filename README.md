# UART with APB Wrapper

This project implements a **Universal Asynchronous Receiver-Transmitter (UART)** with an **AMBA APB (Advanced Peripheral Bus) interface** in Verilog HDL.  
It includes RTL design, verification testbenches, FPGA synthesis results, and project documentation.

---

## 📂 Repository Structure
- **`src/`** → RTL design files (Verilog)  
- **`dv/`** → Verification testbenches  
- **`fpga/`** → FPGA synthesis runs (Intel Quartus Prime)  
- **`docs/`** → Project report, diagrams, and documentation  

---

## 🛠️ Features
- **UART Transmitter** (8N1 format: start, 8 data bits, 1 stop bit)  
- **UART Receiver** with oversampling for reliability  
- **APB Wrapper** for register access and integration in SoC systems  
- **Self-checking Testbenches** for automated verification  
- Verified in **ModelSim** & synthesized using **Quartus Prime**  

---

## ✅ Verification & Results
- Functional verification with ModelSim testbenches  
- FPGA synthesis completed on Intel Quartus Prime  
- Timing and resource utilization reports included in `fpga/`  

---


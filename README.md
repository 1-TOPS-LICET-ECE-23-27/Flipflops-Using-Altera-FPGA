# **General HDL Project Procedure – Quartus Prime & Simulation Guide**

## 📝 **Project Title**
*FLIPFLOPS USING ALTERA FPGA*

## 📘 **Project Description**
*This project helps you to design flipflops using Altera FPGA and implement it in DE!-SoC Board*

---

## 🚀 **General Procedure for Any Quartus HDL Project**
These steps are **common for almost all projects**, whether it’s combinational, sequential, or FPGA-based.

### **1️⃣ Create a New Project**
- Open Quartus Prime
- Go to **File → New Project Wizard**
- Choose the project directory
- Enter the project name
- Finish project setup

---

### **2️⃣ Create Design File (HDL Source)**
- Go to **File → New → (Verilog/VHDL) File**
- Write your design code
- Save the file

*(Only code changes per project — procedure stays the same)*

---

### **3️⃣ Create Testbench File (For Simulation)**
- Go to **File → New → (Verilog/VHDL) File**
- Write the testbench to test your design
- Save the file

---

### **4️⃣ Add Required Files to the Project**
- Go to **Project → Add/Remove Files in Project**
- Add your design file(s)
- Add your testbench file (for simulation)

---

### **5️⃣ Compile the Project**
- Go to **Processing → Start Compilation**
- Wait for the compilation to finish without errors

This step is the same for all projects.

---

## 🧪 **Simulation Procedure (Any Simulation Tool)**
- Go to **Tools → Run Simulation Tool → RTL Simulation**
- Open your testbench
- Run simulation
- View waveforms to verify the logic

*(Waveform checking is common for all projects.)*

---

## 🔌 **(Optional) FPGA Pin Assignment**
Only required if the design is to be implemented on hardware.

- Go to **Assignments → Pin Planner**
- Map external signals (inputs/outputs) to physical FPGA pins
- Recompile
- Program the FPGA device

*(Only the pin names change — procedure stays the same.)*

---

## 📁 **Recommended Folder Structure**
```
📦 Project_Name
 ┣ 📜 design_file.sv / v / vhd
 ┣ 📜 testbench.sv / v / vhd
 ┣ 📁 output_files
 ┣ 📁 simulation
 ┗ 📜 README.md
```

---




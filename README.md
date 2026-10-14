# Hi, I'm Trần Văn Vinh 👋
**Embedded Software Engineer / Firmware Developer**

Final-year Electrical and Electronic Engineering student at PTIT. Focused on bare-metal firmware development, ARM Cortex-M architecture, real-time digital signal processing (DSP), and edge TinyML deployment.

- 📍 Location: Hanoi, Vietnam
- 🎓 Education: Posts and Telecommunications Institute of Technology (PTIT)
- 💼 Focus: Embedded C, Cortex-M3/M4, RTOS, Peripheral Drivers & On-Device ML
- 📬 Contact: [vinht7349@gmail.com](mailto:vinht7349@gmail.com) | [LinkedIn](https://linkedin.com/in/your-profile)

---

### 🛠 Tech Stack & Core Competencies

- **Languages:** Embedded C (Primary), C++, Assembly, Verilog HDL, Python, Bash
- **Hardware & Architectures:** ARM Cortex-M3/M4 (STM32F411, STM32F103, STM32F401), ESP32, RISC-V (RV32I)
- **Firmware Development:** Bare-metal register-level drivers, STM32 HAL/LL, CMSIS-DSP, FreeRTOS
- **Protocols & Interfaces:** UART, SPI, I2C, Dual I2S/DMA, CAN, ADC/PWM, MQTT, HTTP/WebSocket
- **Tools & Environments:** Keil µVision, PlatformIO, VS Code, Quartus Prime, ModelSim, Logic Analyzer, Git, Altium Designer

---

### 🚀 Featured Projects

#### 🔹 [Real-Time Acoustic Localization (DOA) & TinyML on STM32F411](https://github.com/TranVanVinh74/STM32F4-vs-INMP441)
- 4-microphone synchronized audio capture via Dual I2S and circular DMA at 16 kHz.
- Closed-form phase TDOA per frequency bin and azimuth histogram accumulation ($\text{MAE} < 4^\circ$).
- On-device TinyML classifier (1.7k parameters) filtering ambient noise from speech targets within an 11 ms real-time frame budget ($<43\,\text{KiB}$ SRAM, $355\,\text{mW}$).

#### 🔹 Smart Gas Monitoring & Real-Time Telemetry System
- Bare-metal STM32F103 firmware for continuous ADC gas sampling, local alarms, and automated emergency GSM calls via AT commands.
- Custom UART communication framing between STM32 and ESP32 for real-time WebSocket dashboard streaming.

#### 🔹 RISC-V (RV32I) Processor Core on FPGA
- Synthesized a 32-bit single-cycle/pipelined core from scratch using Verilog HDL.
- Implemented instruction decode, ALU operations, memory-mapped I/O, and custom UART peripheral verified via ModelSim testbenches.

---

### 📊 GitHub Activity

![Vinh's GitHub Stats](https://github-readme-stats.vercel.app/api?username=TranVanVinh74&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=TranVanVinh74&layout=compact&theme=tokyonight&hide_border=true)

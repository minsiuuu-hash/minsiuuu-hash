<div align="center">

# 안녕하세요, 정민수입니다.

**RTL 설계와 검증을 통해 신뢰할 수 있는 디지털 시스템을 만드는 엔지니어를 목표로 합니다.**

SystemVerilog 기반 RTL 설계부터 UVM 검증, RISC-V 프로세서, FPGA 영상 처리까지
직접 구현하고 검증하며 설계와 검증 역량을 쌓고 있습니다.

</div>

---

## About Me

* 디지털 회로 **RTL 설계 및 Verification Engineer**를 목표로 하고 있습니다.
* Verilog/SystemVerilog를 활용한 RTL 설계와 UVM 기반 기능 검증을 경험했습니다.
* RISC-V CPU, AMBA Bus, UART/SPI/I2C 등의 디지털 시스템과 통신 프로토콜을 구현했습니다.
* FPGA 기반 영상 처리 및 Hardware Accelerator 구현 경험을 보유하고 있습니다.
* 단순히 동작하는 RTL을 만드는 것에 그치지 않고, **신호 흐름과 내부 구조를 이해한 상태에서 검증하는 과정**을 중요하게 생각합니다.

---

## Tech Stack

### RTL & Verification

<p>
  <img src="https://img.shields.io/badge/SystemVerilog-CAD09D?style=flat-square&logoColor=black" alt="SystemVerilog" />
  <img src="https://img.shields.io/badge/Verilog-1B365D?style=flat-square&logoColor=white" alt="Verilog" />
  <img src="https://img.shields.io/badge/UVM-6B4F9E?style=flat-square&logoColor=white" alt="UVM" />
  <img src="https://img.shields.io/badge/RTL_Design-2E7D32?style=flat-square&logoColor=white" alt="RTL Design" />
  <img src="https://img.shields.io/badge/Functional_Coverage-B23A48?style=flat-square&logoColor=white" alt="Functional Coverage" />
</p>

### Programming

<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
</p>

### Tools & Platforms

<p>
  <img src="https://img.shields.io/badge/Xilinx_Vivado-E01F27?style=flat-square&logoColor=white" alt="Xilinx Vivado" />
  <img src="https://img.shields.io/badge/Vitis-EF5350?style=flat-square&logoColor=white" alt="Vitis" />
  <img src="https://img.shields.io/badge/Synopsys_VCS-5B2C6F?style=flat-square&logoColor=white" alt="Synopsys VCS" />
  <img src="https://img.shields.io/badge/Verdi-4A148C?style=flat-square&logoColor=white" alt="Verdi" />
  <img src="https://img.shields.io/badge/Basys3-1F6F8B?style=flat-square&logoColor=white" alt="Basys3" />
  <img src="https://img.shields.io/badge/PYNQ--Z2-D97706?style=flat-square&logoColor=white" alt="PYNQ-Z2" />
  <img src="https://img.shields.io/badge/Zybo_Z7--20-7D3C98?style=flat-square&logoColor=white" alt="Zybo Z7-20" />
  <img src="https://img.shields.io/badge/Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="NVIDIA Jetson" />
</p>

### Architecture & Protocols

<p>
  <img src="https://img.shields.io/badge/RISC--V_RV32I-283272?style=flat-square&logo=riscv&logoColor=white" alt="RISC-V RV32I" />
  <img src="https://img.shields.io/badge/AMBA_APB-00897B?style=flat-square&logoColor=white" alt="AMBA APB" />
  <img src="https://img.shields.io/badge/AXI4--Lite-00695C?style=flat-square&logoColor=white" alt="AXI4-Lite" />
  <img src="https://img.shields.io/badge/UART-455A64?style=flat-square&logoColor=white" alt="UART" />
  <img src="https://img.shields.io/badge/SPI-7B1FA2?style=flat-square&logoColor=white" alt="SPI" />
  <img src="https://img.shields.io/badge/I2C-C62828?style=flat-square&logoColor=white" alt="I2C" />
</p>

---

# Featured Projects

프로젝트를 통해 **RTL 설계 → 시뮬레이션 → 기능 검증 → FPGA 구현**까지의 흐름을 경험했습니다.

<table>
  <thead>
    <tr>
      <th align="center">분야<br>(Category)</th>
      <th align="center">프로젝트<br>(Project)</th>
      <th align="center">핵심 내용<br>(Key Details)</th>
      <th align="center">주요 기술<br>(Tech Stack)</th>
    </tr>
  </thead>

  <tbody>

```
<tr>
  <td align="center">
    <b>RTL Verification</b><br>
    <sub>기능 검증</sub>
  </td>
  <td>
    <a href="https://github.com/minsiuuu-hash/UVM">
      <b>UVM Verification Projects</b>
    </a>
  </td>
  <td>
    • RAM, UART, APB RAM, SPI, I2C DUT를 대상으로 UVM 검증 환경 구성<br>
    • Sequence → Driver → DUT → Monitor → Scoreboard 기반 검증 흐름 구현<br>
    • Functional Coverage를 활용하여 주요 입력 패턴 및 검증 진행 상태 확인<br>
    • Verdi를 활용한 Waveform 분석 및 오류 원인 추적
  </td>
  <td>
    <code>SystemVerilog</code><br>
    <code>UVM</code><br>
    <code>VCS</code><br>
    <code>Verdi</code><br>
    <code>Coverage</code>
  </td>
</tr>

<tr>
  <td rowspan="2" align="center">
    <b>CPU & SoC Architecture</b><br>
    <sub>프로세서 / Bus 설계</sub>
  </td>
  <td>
    <a href="https://github.com/minsiuuu-hash/RISCV-32I_MULTICYCLE_AMBA_APB">
      <b>RISC-V RV32I Multi-Cycle CPU with APB SoC</b>
    </a>
  </td>
  <td>
    • RV32I CPU를 FETCH / DECODE / EXECUTE / MEMORY / WRITE BACK 단계의 Multi-Cycle FSM으로 설계<br>
    • Single-Cycle 구조를 Multi-Cycle로 개선하여 Critical Path를 분리<br>
    • Clock Period를 약 <b>15.8 ns → 8.3 ns</b>로 단축<br>
    • APB Master 및 Address Decoder를 구현하여 GPO, GPI, GPIO, FND, UART Peripheral 연동<br>
    • Memory-Mapped I/O 기반 Processor–Peripheral 통신 구조 구현
  </td>
  <td>
    <code>RISC-V RV32I</code><br>
    <code>Verilog</code><br>
    <code>Multi-Cycle FSM</code><br>
    <code>AMBA APB</code><br>
    <code>Memory-Mapped I/O</code>
  </td>
</tr>

<tr>
  <td>
    <a href="https://github.com/minsiuuu-hash/RISCV-32I_SINGLECYCLE">
      <b>RISC-V RV32I Single-Cycle Processor</b>
    </a>
  </td>
  <td>
    • RISC-V RV32I ISA 기반 32-bit Single-Cycle CPU 설계<br>
    • Register File, ALU, Immediate Generator, Control Unit 및 Data Memory 구성<br>
    • R/I/S/B/J/U-Type 명령어와 Branch, Jump, Load/Store 기능 구현<br>
    • CPU Datapath와 Control Signal의 동작을 Simulation을 통해 검증
  </td>
  <td>
    <code>RISC-V RV32I</code><br>
    <code>Verilog</code><br>
    <code>RTL Design</code><br>
    <code>Vivado</code>
  </td>
</tr>

<tr>
  <td align="center">
    <b>FPGA AI Accelerator</b><br>
    <sub>Hardware AI</sub>
  </td>
  <td>
    <a href="https://github.com/minsiuuu-hash/CNN">
      <b>Log2 Quantization Based CNN FPGA Implementation</b>
    </a>
  </td>
  <td>
    • PyTorch에서 학습한 CNN 모델을 FPGA에서 동작 가능한 RTL 구조로 구현<br>
    • Log2 Quantization을 적용하여 Weight Multiplication을 Shift 연산으로 대체<br>
    • Convolution, Pooling, Fully Connected 연산을 Hardware 구조로 구현<br>
    • 정확도, 추론 시간 및 FPGA Resource 사용량을 비교하며 구조 최적화
  </td>
  <td>
    <code>Verilog</code><br>
    <code>PyTorch</code><br>
    <code>Log2 Quantization</code><br>
    <code>Vivado</code><br>
    <code>PYNQ-Z2</code>
  </td>
</tr>

<tr>
  <td rowspan="2" align="center">
    <b>FPGA System & Vision</b><br>
    <sub>영상 처리 / 시스템 통합</sub>
  </td>
  <td>
    <a href="https://github.com/minsiuuu-hash/team_project_dudeoji">
      <b>Whac-A-Mole FPGA Game</b>
    </a>
  </td>
  <td>
    • Basys3 FPGA 2대를 UART로 연결한 실시간 게임 시스템 구현<br>
    • OV7670 Camera 입력을 RGB/HSV 기반으로 처리하여 색상 및 위치 검출<br>
    • 6개 영역의 객체 위치를 판별하고 UART Packet으로 다른 FPGA에 전달<br>
    • VGA를 활용해 영상 처리 결과 및 시스템 동작을 실시간 디버깅<br>
    • 주요 RTL Module에 대해 Simulation 및 UVM 기반 기능 검증 수행
  </td>
  <td>
    <code>SystemVerilog</code><br>
    <code>UVM</code><br>
    <code>OV7670</code><br>
    <code>UART</code><br>
    <code>VGA</code><br>
    <code>Basys3</code>
  </td>
</tr>

<tr>
  <td>
    <a href="https://github.com/minsiuuu-hash/Smart_Factory_with_AMR">
      <b>Smart Factory with Autonomous AMR</b>
    </a>
  </td>
  <td>
    • FPGA, Jetson, Robot Arm, Autonomous Mobile Robot을 연동한 스마트 물류 자동화 시스템 구축<br>
    • Zybo Z7-20과 Camera를 활용한 실시간 영상 처리 및 객체 위치 검출<br>
    • Jetson 기반 AI Vision을 활용한 물체 분류 및 적재 위치 판단<br>
    • Robot Arm 및 AMR과 연동하여 물품 Pick → Transport → Place 과정 자동화
  </td>
  <td>
    <code>SystemVerilog</code><br>
    <code>Verilog</code><br>
    <code>C/C++</code><br>
    <code>Python</code><br>
    <code>Zybo Z7-20</code><br>
    <code>Jetson</code>
  </td>
</tr>

<tr>
  <td align="center">
    <b>Digital IP & Interface</b><br>
    <sub>통신 / 센서 제어</sub>
  </td>
  <td>
    <a href="https://github.com/minsiuuu-hash/UART_SR04-DHT11_STOPWATCH-WATCH">
      <b>UART & Sensor FPGA System</b>
    </a>
  </td>
  <td>
    • UART TX/RX 및 FIFO를 이용한 비동기 Serial Communication 구현<br>
    • HC-SR04 초음파 센서와 DHT11 온·습도 센서를 FPGA에서 직접 제어<br>
    • Stopwatch / Watch / Sensor 기능을 하나의 FPGA 시스템으로 통합<br>
    • FSM과 Clock Divider를 활용해 서로 다른 Timing Requirement를 갖는 모듈 제어
  </td>
  <td>
    <code>Verilog</code><br>
    <code>UART</code><br>
    <code>FIFO</code><br>
    <code>FSM</code><br>
    <code>Basys3</code>
  </td>
</tr>
```

  </tbody>
</table>

---

## RISC-V Design Evolution

RISC-V CPU를 기본 구조부터 Bus 기반 SoC까지 단계적으로 확장하며 설계했습니다.

```text
RISC-V RV32I Single-Cycle CPU
              │
              ▼
RISC-V RV32I Multi-Cycle CPU
              │
              ▼
Multi-Cycle CPU + AMBA APB
              │
              ▼
      APB Peripheral SoC
```

* **Single-Cycle**
  하나의 Clock Cycle 내에서 명령어를 수행하는 RV32I CPU 구조 구현

* **Multi-Cycle**
  명령어 실행을 여러 단계로 분리하고 FSM 기반 Control 구조로 개선

* **AMBA APB SoC**
  APB Master와 Peripheral을 추가하여 Memory-Mapped I/O 기반 SoC 구조로 확장

### Related Repositories

* [RISC-V RV32I Single-Cycle](https://github.com/minsiuuu-hash/RISCV-32I_SINGLECYCLE)
* [RISC-V RV32I Multi-Cycle](https://github.com/minsiuuu-hash/RISCV-32I_MULTICYCLE)
* [RISC-V RV32I Multi-Cycle + AMBA APB](https://github.com/minsiuuu-hash/RISCV-32I_MULTICYCLE_AMBA_APB)

---

## Currently

* UVM Sequence, Factory, Configuration, RAL 등 검증 환경의 재사용성을 학습하고 있습니다.
* Functional Coverage를 활용하여 검증 시나리오의 완성도를 높이는 방법을 학습하고 있습니다.
* RISC-V Processor와 AMBA Bus 기반 SoC 구조에 대한 이해를 확장하고 있습니다.
* RTL 구조를 이해한 상태에서 DUT의 기능을 검증하는 역량을 강화하고 있습니다.

---

## GitHub Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=minsiuuu-hash&amp;theme=github_dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=minsiuuu-hash&amp;theme=github" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=minsiuuu-hash&amp;theme=github" alt="정민수의 GitHub 활동 요약" />
  </picture>
</div>

---

<div align="center">

**RTL Design · Verification · FPGA**

꾸준히 배우고, 직접 구현하고, 검증한 결과로 성장하겠습니다.

</div>

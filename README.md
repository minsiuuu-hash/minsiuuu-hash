<div align="center">

# 안녕하세요, 정민수입니다.

**RTL 설계와 검증을 통해 신뢰할 수 있는 디지털 시스템을 만드는 엔지니어를 목표로 합니다.**

SystemVerilog 기반 RTL 설계부터 UVM 검증, RISC-V 프로세서, FPGA 영상 처리까지  
직접 구현하고 검증하며 배운 내용을 기록하고 있습니다.

제 GitHub에 방문해 주셔서 감사합니다.

</div>

---

## About Me

- 디지털 설계 및 검증 엔지니어 취업을 준비하고 있습니다.
- 동작하는 RTL을 만드는 것에 그치지 않고, 테스트 시나리오와 커버리지를 통해 설계를 검증하는 과정에 관심이 있습니다.
- 프로세서 구조, 버스 및 통신 프로토콜, FPGA 기반 영상 처리 프로젝트를 중심으로 경험을 쌓고 있습니다.
- 설계 의도와 검증 결과를 다른 사람이 이해할 수 있도록 문서화하는 습관을 중요하게 생각합니다.

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

## Featured Projects

아래 프로젝트는 모두 팀 프로젝트로 진행했으며, 저장소에 설계 및 검증 과정과 결과를 기록했습니다.

| 프로젝트 | 핵심 내용 | 기술 |
|---|---|---|
| [UVM Verification Projects](https://github.com/minsiuuu-hash/UVM) | RAM, UART, APB RAM, SPI, I2C를 대상으로 재사용 가능한 UVM 테스트벤치 구성 및 Scoreboard/Coverage 기반 검증 | SystemVerilog, UVM, VCS |
| [RISC-V RV32I Multi-Cycle CPU with APB](https://github.com/minsiuuu-hash/RISCV-32I_MULTICYCLE_AMBA_APB) | RV32I 멀티사이클 CPU에 APB Master와 주소 디코더를 연결하고 GPO, GPI, GPIO, FND, UART를 Memory-Mapped I/O로 구성 | SystemVerilog, RISC-V, AMBA APB |
| [CNN FPGA Implementation](https://github.com/minsiuuu-hash/CNN) | Log2 양자화와 Shift 연산으로 CNN을 RTL에 구현하고 정확도, 추론 시간, 자원 및 전력 사용량 비교 | Verilog, PyTorch, Vivado, PYNQ-Z2 |
| [Whac-A-Mole FPGA Game](https://github.com/minsiuuu-hash/team_project_dudeoji) | 두 대의 Basys3에서 카메라 색상 감지, UART 이벤트 전송, VGA 게임 로직을 구현하고 핵심 모듈을 UVM으로 검증 | SystemVerilog, UVM, UART, VGA, OpenCV |
| [Smart Factory with Autonomous AMR](https://github.com/minsiuuu-hash/Smart_Factory_with_AMR) | 자율주행 AMR, FPGA 실시간 영상 처리, Jetson AI, 로봇팔을 연동한 스마트 물류 자동화 시스템 구현 | SystemVerilog, Verilog, C/C++, Python, Vivado, Vitis, Zybo Z7-20 |
| [UART & Sensor System](https://github.com/minsiuuu-hash/UART_SR04-DHT11_STOPWATCH-WATCH) | UART, FIFO, 초음파 및 온습도 센서, 스톱워치와 시계를 하나의 FPGA 시스템으로 통합 | Verilog, SystemVerilog, Basys3 |

## Currently

- UVM 테스트벤치의 재사용성과 기능 커버리지 설계를 공부하고 있습니다.
- RISC-V 기반 프로세서와 AMBA 버스 구조에 대한 이해를 넓히고 있습니다.
- FPGA에서의 실시간 영상 처리와 하드웨어 가속 구현을 경험하고 있습니다.

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

읽어주셔서 감사합니다. 꾸준히 배우고, 직접 구현하고, 검증한 결과로 성장하겠습니다.

</div>

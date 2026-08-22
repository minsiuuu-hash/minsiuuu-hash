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
- SystemVerilog/Verilog 기반 RTL과 통신 IP를 설계하고 UVM으로 검증했습니다.
- RISC-V 및 AMBA 기반 SoC와 FPGA 영상 처리 시스템을 구현했습니다.

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

<table>
  <thead>
    <tr>
      <th align="center">분야</th>
      <th align="center">프로젝트</th>
      <th align="center">핵심 내용</th>
      <th align="center">주요 기술</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2" align="center"><strong>1. Hardware IP<br>&amp; Verification</strong></td>
      <td><a href="https://github.com/minsiuuu-hash/UVM"><strong>UVM Verification Projects</strong></a></td>
      <td>RAM, UART, APB RAM, SPI, I2C를 대상으로 재사용 가능한 UVM 테스트벤치를 구성하고 Scoreboard 및 Coverage 기반으로 검증</td>
      <td><code>SystemVerilog</code><br><code>UVM</code><br><code>VCS</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/minsiuuu-hash/UVM/tree/main/AXI"><strong>AXI4-Lite Communication IP &amp; SW Verification</strong></a></td>
      <td>GPIO, SPI, I2C, UART 주변장치를 AXI4-Lite Slave IP로 설계하고, Vitis C/HAL 소프트웨어와 UVM 테스트벤치를 통해 하드웨어·소프트웨어 연동 검증</td>
      <td><code>AXI4-Lite</code><br><code>Verilog/SystemVerilog</code><br><code>Vitis C</code><br><code>UVM</code></td>
    </tr>
    <tr>
      <td rowspan="3" align="center"><strong>2. CPU &amp; SoC<br>Architecture</strong><br><sub>RISC-V Processor Series</sub></td>
      <td><a href="https://github.com/minsiuuu-hash/RISCV-32I_SINGLECYCLE"><strong>RV32I Single-Cycle CPU</strong></a></td>
      <td>Harvard Architecture 기반 RV32I 데이터패스와 제어 장치를 설계하고, C 누적 합 프로그램의 실행 결과와 어셈블리 코드를 비교하여 동작 검증</td>
      <td><code>RV32I</code><br><code>SystemVerilog</code><br><code>Vivado</code><br><code>C</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/minsiuuu-hash/RISCV-32I_MULTICYCLE"><strong>RV32I Multi-Cycle CPU</strong></a></td>
      <td>명령어 실행을 Fetch, Decode, Execute, Memory, Write Back 단계로 분리하고 중간 레지스터와 FSM 기반 제어 구조 구현</td>
      <td><code>RV32I</code><br><code>SystemVerilog</code><br><code>Multi-Cycle FSM</code></td>
    </tr>
    <tr>
      <td><a href="https://github.com/minsiuuu-hash/RISCV-32I_MULTICYCLE_AMBA_APB"><strong>RV32I Multi-Cycle CPU with APB</strong></a></td>
      <td>Multi-Cycle CPU에 APB Master와 주소 디코더를 연결하고 GPO, GPI, GPIO, FND, UART를 Memory-Mapped I/O로 구성</td>
      <td><code>RV32I</code><br><code>SystemVerilog</code><br><code>AMBA APB</code><br><code>Memory-Mapped I/O</code></td>
    </tr>
    <tr>
      <td align="center"><strong>3. On-Device AI<br>&amp; Vision</strong></td>
      <td><a href="https://github.com/minsiuuu-hash/CNN"><strong>CNN FPGA Implementation</strong></a></td>
      <td>Log2 양자화와 Shift 연산으로 CNN을 RTL에 구현하고 정확도, 추론 시간, 자원 및 전력 사용량 비교</td>
      <td><code>Verilog</code><br><code>PyTorch</code><br><code>Vivado</code><br><code>PYNQ-Z2</code></td>
    </tr>
    <tr>
      <td align="center"><strong>4. FPGA System<br>Integration</strong></td>
      <td><a href="https://github.com/minsiuuu-hash/team_project_dudeoji"><strong>Whac-A-Mole FPGA Game</strong></a></td>
      <td>두 대의 Basys3에서 카메라 색상 감지, UART 이벤트 전송, VGA 게임 로직을 구현하고 핵심 모듈을 UVM으로 검증</td>
      <td><code>SystemVerilog</code><br><code>UVM</code><br><code>UART</code><br><code>VGA</code><br><code>OpenCV</code></td>
    </tr>
    <tr>
      <td align="center"><strong>5. Robotics &amp;<br>System Integration</strong></td>
      <td><a href="https://github.com/minsiuuu-hash/Smart_Factory_with_AMR"><strong>Smart Factory with Autonomous AMR</strong></a></td>
      <td>자율주행 AMR, FPGA 실시간 영상 처리, Jetson AI, 로봇팔을 연동한 스마트 물류 자동화 시스템 구현</td>
      <td><code>SystemVerilog</code><br><code>C/C++</code><br><code>Python</code><br><code>Vivado/Vitis</code><br><code>Zybo Z7-20</code></td>
    </tr>
    <tr>
      <td align="center"><strong>6. FPGA Peripheral<br>System</strong></td>
      <td><a href="https://github.com/minsiuuu-hash/UART_SR04-DHT11_STOPWATCH-WATCH"><strong>UART &amp; Sensor System</strong></a></td>
      <td>UART, FIFO, 초음파 및 온습도 센서, 스톱워치와 시계를 하나의 FPGA 시스템으로 통합</td>
      <td><code>Verilog</code><br><code>SystemVerilog</code><br><code>UART</code><br><code>FIFO</code><br><code>Basys3</code></td>
    </tr>
  </tbody>
</table>

## Currently

- **RTL Design:** 안정적인 디지털 시스템 설계를 위한 RTL 기본기를 다지고 있습니다.
- **UVM Verification:** 체계적이고 재사용 가능한 검증을 위한 UVM 기본기를 정리하고 있습니다.

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

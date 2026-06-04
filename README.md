<div align="center">

<a href="https://github.com/dhruvmittal41">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2800&pause=900&color=6AAED6&center=true&vCenter=true&width=820&height=50&lines=Hi%2C+I'm+Dhruv+Mittal+%E2%9A%A1;Bare-metal+Firmware+%C2%B7+SPI+%C2%B7+UART+%C2%B7+I2C+%C2%B7+RTOS;TinyML+%C2%B7+On-device+Inference+%C2%B7+Quantization;RTL+Design+%C2%B7+Verilog+%C2%B7+AI+Accelerators;Hardware-Software+Co-design+at+the+Edge" alt="Typing SVG" />
</a>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1e3a,100:6aaed6&height=140&section=header&reversal=false" width="100%"/>

</div>

---

## 〔 `whoami` 〕

```yaml
Engineer    : Dhruv Mittal
Degree      : B.Tech Electrical Engineering  [2nd Year]
Origin      : India  🇮🇳
Core        :
  ├─ Embedded Firmware    → bare-metal C/C++, drivers, FSMs, RTOS
  ├─ Edge ML / TinyML     → MCU inference, quantization, TF-Lite
  ├─ Chip & IC Design     → RTL, AI accelerator architecture
  └─ IoT + Full-Stack     → sensor systems + React/Node tooling
Now         : Bridging silicon and intelligence
Mission     : Design AI chips that compute at the absolute edge
Secret      : Reads datasheets for fun   // 0x01 = confirmed ✓
```

---

## 〔 `cat /proc/skills` 〕

<div align="center">

**Embedded & Hardware**

[![Skills](https://skillicons.dev/icons?i=c,cpp,arduino&theme=dark&perline=4)](https://skillicons.dev)
![Verilog](https://img.shields.io/badge/Verilog-0b1e3a?style=for-the-badge&logo=verilog&logoColor=6aaed6)
![RTOS](https://img.shields.io/badge/FreeRTOS-0b1e3a?style=for-the-badge&logo=freertos&logoColor=6aaed6)

**Edge ML & AI**

[![Skills](https://skillicons.dev/icons?i=python,tensorflow,pytorch&theme=dark&perline=4)](https://skillicons.dev)
![TF-Lite](https://img.shields.io/badge/TF--Lite-0b1e3a?style=for-the-badge&logo=tensorflow&logoColor=6aaed6)
![NumPy](https://img.shields.io/badge/NumPy-0b1e3a?style=for-the-badge&logo=numpy&logoColor=6aaed6)

**Systems & Web**

[![Skills](https://skillicons.dev/icons?i=js,ts,react,nodejs,express,postgres&theme=dark&perline=6)](https://skillicons.dev)

**Toolchain**

[![Skills](https://skillicons.dev/icons?i=git,github,linux,vscode,bash,vim&theme=dark&perline=6)](https://skillicons.dev)

</div>

---

## 〔 `./build --profile` 〕

```c
/* ================================================================
   ENGINEER PROFILE  ·  Rev 3.0  ·  @dhruvmittal41
   ================================================================ */
#include <stdio.h>
#include <stdint.h>

typedef enum { FIRMWARE, TINYML, RTL_DESIGN, IOT, FULLSTACK } Domain_t;

typedef struct {
    const char *name;
    const char *degree;
    Domain_t    focus[5];
    const char *stack[5];
    const char *mission;
    uint8_t     datasheet_reader;   /* 0x01 = yes */
} Engineer_t;

static const Engineer_t dhruv = {
    .name             = "Dhruv Mittal",
    .degree           = "B.Tech EE  (2nd Year)",
    .focus            = { FIRMWARE, TINYML, RTL_DESIGN, IOT, FULLSTACK },
    .stack            = { "C/C++", "Verilog", "Python", "TF-Lite", "React" },
    .mission          = "Design AI accelerator chips for edge inference",
    .datasheet_reader = 0x01                          /* confirmed */
};

int main(void) {
    printf("[BOOT]  Engineer : %s\n", dhruv.name);
    printf("[INIT]  Degree   : %s\n", dhruv.degree);
    printf("[RUN]   Mission  : %s\n", dhruv.mission);
    return 0;   /* no bugs, only undocumented features */
}
```

---

## 〔 `ls -la ./domains` 〕

| Domain | Work | Stack |
|:---|:---|:---|
| ⚙️ **Embedded Firmware** | Bare-metal C, SPI / I²C / UART drivers, RTOS tasks, FSMs | `C` `C++` `MPLAB` `Arduino` |
| 🧠 **Edge ML / TinyML** | On-device inference, model quantization, MCU deployment | `TF-Lite` `Python` `NumPy` |
| 🔲 **Chip & IC Design** | RTL design in Verilog, AI accelerator architecture & synthesis | `Verilog` `HDL` |
| 📡 **IoT Systems** | Sensor fusion, SD data logging, low-power design patterns | `C` `I²C` `SPI` `ADC` |
| 💻 **Full-Stack Tools** | React + Node backends that support and visualize hardware work | `JS` `React` `Express` `SQL` |

---

## 〔 `htop` 〕

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=dhruvmittal41&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0b1e3a&title_color=6aaed6&icon_color=6aaed6&text_color=c9e4ff" />
<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=dhruvmittal41&theme=midnight-purple&hide_border=true&background=0b1e3a&ring=6aaed6&fire=6aaed6&currStreakLabel=6aaed6" />

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dhruvmittal41&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0b1e3a&title_color=6aaed6&text_color=c9e4ff&langs_count=8" />

</div>

---

## 〔 `cat /sys/status` 〕

```
╔═══════════════════════════════════════════════════════════════╗
║                ◈  SILICON STATUS MONITOR  ◈                   ║
╠══════════════════════════╦════════════════════════════════════╣
║  Protocols               ║  SPI  ·  I²C  ·  UART  ·  GPIO     ║
║  ML Pipeline             ║  Train → Quantize → Compile → MCU  ║
║  HDL / RTL               ║  Design  ·  Simulation  ·  ✓       ║
║  Power Management        ║  Low-power architecture  ·  ✓      ║
║  RTOS Concepts           ║  Tasks  ·  Queues  ·  Semaphores   ║
║  Current Build           ║  Intelligence at the silicon edge  ║
╚══════════════════════════╩════════════════════════════════════╝
```

---

## 〔 `git log --all --graph` 〕

<div align="center">

[![Trophy](https://github-profile-trophy.vercel.app/?username=dhruvmittal41&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=10)](https://github.com/ryo-ma/github-profile-trophy)

<img src="https://github-readme-activity-graph.vercel.app/graph?username=dhruvmittal41&bg_color=0b1e3a&color=c9e4ff&line=6aaed6&point=ffffff&area=true&hide_border=true" width="98%"/>

</div>

---

## 〔 `ping --connect` 〕

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-dhruvmittal41-0d1117?style=for-the-badge&logo=github&logoColor=c9e4ff&labelColor=0b1e3a)](https://github.com/dhruvmittal41)
[![Gmail](https://img.shields.io/badge/Email-mittaldhruv41@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=c9e4ff&labelColor=0b1e3a)](mailto:mittaldhruv41@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0d1117?style=for-the-badge&logo=linkedin&logoColor=c9e4ff&labelColor=0b1e3a)](https://linkedin.com/in/dhruvmittal41)

<br/>

![Views](https://komarev.com/ghpvc/?username=dhruvmittal41&label=Profile+Views&color=6aaed6&style=flat-square&labelColor=0b1e3a)
![Focus](https://img.shields.io/badge/Focus-Edge_AI_%26_Embedded-6aaed6?style=flat-square&labelColor=0b1e3a)
![Status](https://img.shields.io/badge/Status-Building_at_the_Edge-6aaed6?style=flat-square&labelColor=0b1e3a)

</div>

---

<div align="center">

> *"The best abstraction is the one closest to the hardware."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6aaed6,100:0b1e3a&height=120&section=footer" width="100%"/>

</div>

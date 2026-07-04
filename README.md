<!-- ╔══════════════════════════════════════════════════════════════╗
     ║   DHRUV MITTAL  ·  github.com/dhruvmittal41                  ║
     ╚══════════════════════════════════════════════════════════════╝ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=220&section=header&text=Dhruv%20Mittal&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Computer%20Architecture%20%C2%B7%20Hardware%20Accelerators%20%C2%B7%20VLSI&descAlignY=58&descSize=18" width="100%"/>

<a href="https://github.com/dhruvmittal41">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2600&pause=800&color=6AAED6&center=true&vCenter=true&multiline=false&width=820&height=55&lines=%24+whoami+%E2%86%92+Electrical+Engineering+Undergrad;%24+cat+focus.log+%E2%86%92+Computer+Architecture+%C2%B7+RTL+%C2%B7+Accelerators;%24+grep+-r+%22attention%22+./research+%E2%86%92+Efficient+Transformer+HW;%24+echo+%24GOAL+%E2%86%92+Research+in+VLSI+%2F+CS+Architecture" alt="Typing intro" />
</a>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dhruvmittal41/dhruvmittal41/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dhruvmittal41/dhruvmittal41/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/dhruvmittal41/dhruvmittal41/output/github-snake.svg" width="100%"/>
</picture>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=dhruvmittal41&label=PROFILE+VISITS&color=6aaed6&style=for-the-badge&labelColor=0b1e3a)
![Focus](https://img.shields.io/badge/FOCUS-Computer_Architecture_%26_Accelerators-6aaed6?style=for-the-badge&labelColor=0b1e3a)
![Status](https://img.shields.io/badge/STATUS-Learning_%26_Building-6aaed6?style=for-the-badge&labelColor=0b1e3a)

</div>

---

## 〔 `> whoami` 〕

```yaml
Engineer    : Dhruv Mittal
Degree      : B.Tech Electrical Engineering  [Year 3]
Origin      : India  🇮🇳
Core        :
  ├─ Computer Architecture   → pipelines, memory hierarchy, ISA design
  ├─ Hardware Accelerators   → efficient HW for transformer attention
  ├─ RTL / Digital Design    → Verilog, SystemVerilog, synthesis
  └─ Systems Foundations     → digital logic, signals & systems
Interest    : Making attention mechanisms cheaper to compute in silicon
Stage       : Undergrad, coursework + independent projects in progress
Goal        : Research experience in VLSI / computer architecture labs
```

---

## 〔 `> cat /proc/skills` 〕

<div align="center">

**Hardware & RTL**

![Verilog](https://img.shields.io/badge/Verilog-0b1e3a?style=for-the-badge&logo=verilog&logoColor=6aaed6)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-0b1e3a?style=for-the-badge&logo=verilog&logoColor=6aaed6)
![Vivado](https://img.shields.io/badge/Xilinx_Vivado-0b1e3a?style=for-the-badge&logo=xilinx&logoColor=6aaed6)

**Foundations**

[![Core](https://skillicons.dev/icons?i=c,cpp,python&theme=dark&perline=3)](https://skillicons.dev)
![Digital Logic](https://img.shields.io/badge/Digital_Logic_Design-0b1e3a?style=for-the-badge&labelColor=0b1e3a&color=6aaed6)
![Comp Arch](https://img.shields.io/badge/Computer_Organization_%26_Architecture-0b1e3a?style=for-the-badge&labelColor=0b1e3a&color=6aaed6)
![Signals](https://img.shields.io/badge/Signals_%26_Systems-0b1e3a?style=for-the-badge&labelColor=0b1e3a&color=6aaed6)

**Toolchain**

[![Tools](https://skillicons.dev/icons?i=git,github,githubactions,linux,vscode,bash,vim&theme=dark&perline=7)](https://skillicons.dev)

</div>

---

## 〔 `> ls -la ./interests` 〕

| Area | What I'm Exploring |
|:---|:---|
| 🧮 **Hardware Accelerators** | Architectures for accelerating transformer attention computation — the core focus of my current independent work |
| 🏗️ **Computer Architecture** | Pipelining, memory hierarchy, and ISA-level design tradeoffs from coursework and self-study |
| 🔲 **RTL / Digital Design** | Implementing and simulating digital logic in Verilog/SystemVerilog, synthesis flows in Vivado |
| ⚡ **Efficient AI Hardware** | Reading up on how ML workloads map to hardware — where the bottlenecks are and how custom datapaths help |

> 📌 I'm currently building projects in this space — repos and writeups will be added here as they're completed, not before. No vaporware.

---

## 〔 `> ./build --profile` 〕

```c
/* ════════════════════════════════════════════════════════════════
   ENGINEER PROFILE  ·  Rev 1.0  ·  @dhruvmittal41
   ════════════════════════════════════════════════════════════════ */
#include <stdio.h>
#include <stdint.h>

typedef enum { COMP_ARCH, ACCELERATORS, RTL_DESIGN, FOUNDATIONS } Domain_t;

typedef struct {
    const char *name;
    const char *degree;
    Domain_t    focus[4];
    const char *stack[5];
    const char *interest;
    const char *goal;
} Engineer_t;

static const Engineer_t dhruv = {
    .name     = "Dhruv Mittal",
    .degree   = "B.Tech EE  (Year 3)",
    .focus    = { COMP_ARCH, ACCELERATORS, RTL_DESIGN, FOUNDATIONS },
    .stack    = { "Verilog", "SystemVerilog", "Vivado", "C/C++", "Python" },
    .interest = "Efficient hardware for transformer attention",
    .goal     = "Research role in VLSI / computer architecture",
};

int main(void) {
    printf("[BOOT]  %s  ·  %s\n", dhruv.name, dhruv.degree);
    printf("[FOCUS] %s\n", dhruv.interest);
    printf("[NEXT]  %s\n", dhruv.goal);
    return 0;
}
```

---

## 〔 `> htop` — live stats 〕

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=dhruvmittal41&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0b1e3a&title_color=6aaed6&icon_color=6aaed6&text_color=c9e4ff&include_all_commits=true&count_private=true" />
<img height="170" src="https://streak-stats.demolab.com?user=dhruvmittal41&theme=midnight-purple&hide_border=true&background=0b1e3a&ring=6aaed6&fire=6aaed6&currStreakLabel=6aaed6" />

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dhruvmittal41&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0b1e3a&title_color=6aaed6&text_color=c9e4ff&langs_count=8" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=dhruvmittal41&bg_color=0b1e3a&color=c9e4ff&line=6aaed6&point=ffffff&area=true&area_color=6aaed6&hide_border=true&custom_title=Commit%20Activity%20%C2%B7%20Last%2031%20Days" width="98%"/>

</div>

---

## 〔 `> ping --connect` 〕

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-dhruvmittal41-0d1117?style=for-the-badge&logo=github&logoColor=c9e4ff&labelColor=0b1e3a)](https://github.com/dhruvmittal41)
[![Gmail](https://img.shields.io/badge/Email-mittaldhruv41@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=c9e4ff&labelColor=0b1e3a)](mailto:mittaldhruv41@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0d1117?style=for-the-badge&logo=linkedin&logoColor=c9e4ff&labelColor=0b1e3a)](https://linkedin.com/in/dhruvmittal41)

</div>

---

<div align="center">

> *"Attention is expensive. Making it cheap in silicon is the fun part."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer" width="100%"/>

</div>

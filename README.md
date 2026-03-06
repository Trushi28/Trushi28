<!--
**Trushi28/Trushi28** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Bethu%20Trushi&fontSize=62&fontColor=ffffff&fontAlignY=38&desc=Systems%20%E2%80%A2%20Compilers%20%E2%80%A2%20ML%20%E2%80%A2%20Fullstack&descAlignY=60&descColor=a78bfa&animation=fadeIn" width="100%"/> </div> <br/> <div align="center">

### 👋 Hi there!

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=700&size=18&duration=2800&pause=1200&color=A78BFA&center=true&vCenter=true&random=false&width=680&lines=Building+bare-metal+OSes+in+Rust+%F0%9F%A6%80;97.5%25+accuracy+BERT+hybrid+pipeline+%F0%9F%A7%A0;LeetCode+1993+%E2%80%94+Top+2%25+globally+%F0%9F%94%A5;C%2FC%2B%2B+is+my+love+language+%F0%9F%92%9C)](https://git.io/typing-svg)

</div> <br/>

```rust
impl Trushi {
    fn new() -> Self {
        Self {
            role:     "CS undergrad @ CMR Engineering College (2027)",
            stack:    ["Rust", "x86-64 ASM", "PyTorch", "React", "Next.js"],
            crafting: "AstralOS — bare-metal x86-64 OS in Rust + Assembly",
            vibe:     "systems to silicon, kernel to cloud",
        }
    }
}

```

----------

<div align="center">

## 🛠 Skills

</div> <div align="center">

### ◈ Systems & Low-Level

[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)  ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white) ![x86-64 ASM](https://img.shields.io/badge/x86--64_Assembly-1a1a2e?style=for-the-badge&logo=assemblyscript&logoColor=a78bfa) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**OS dev · Compiler design · Memory allocators · Schedulers · Bare metal**

<br/>

### ◈ Machine Learning & AI

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**BERT · BiLSTM · CNN · NLP · Sentiment Analysis · Transformers**

<br/>

### ◈ Web & Fullstack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)  ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white) ![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
<br/>

### ◈ Databases & Cloud

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
</div>

----------

## 🌌 Flagship: AstralOS

> _A fully bootable bare-metal x86-64 OS written in Rust — from scratch_

```
ASTRAL OS v0.3.1  ·  BOOT LOG
──────────────────────────────────────────────────────────────────
 [OK]  Physical Memory    lock-free bitmap allocator · 4GB RAM
 [OK]  Virtual Memory     4-level page table + recursive mapping
 [OK]  Kernel Heap        100MB coalescing linked-list allocator
 [OK]  Slab Allocator     8 size classes · O(1) allocation
 [OK]  SMP Scheduler      O(1) priority dispatch · 5 classes
 [OK]  Userspace          Ring 3 · ELF loading · FPU state
 [OK]  Interrupts         APIC/IOAPIC · full context switching
 [OK]  Block Driver       VirtIO 1.0 · 128-descriptor virtqueues
 [OK]  PsychicFS          predictive FS · access pattern learning
 [OK]  Compositor         Wayland-inspired · Porter-Duff blending
 [OK]  Boot Target        BIOS + UEFI via Limine bootloader
──────────────────────────────────────────────────────────────────
 SYSTEM READY                                          AstralOS ▓

```

<div align="center">

`Rust Nightly` · `x86-64 ASM` · `Bare Metal` · `APIC/IOAPIC` · `VirtIO` · `ELF`

</div>

----------

## 🧠 ML Research: Sentiment Engine

```python
model = HybridSentimentEngine(
    backbone  = "BERT-base-uncased (110M parameters)",
    cnn       = "Multi-Scale CNN — kernels [3,4,5], up to 1024 filters",
    rnn       = "3-layer BiLSTM — 512 hidden units/direction",
    attention = "Self-Attention head",
    optimizer = "AdamW + OneCycleLR + FP16 mixed precision",
    data      = "13,028 samples — Abdallah Wagih + ISEAR datasets",
)

results = {
    "test_accuracy" : "97.5%",
    "f1_score"      : 0.9753,
    "tasks"         : ["Sentiment → Negative / Neutral / Positive",
                       "Emotion  → Joy, Sadness, Anger, Fear, Surprise, Neutral"],
    "inference"     : "~100–200ms on GPU  |  550MB production export",
}

```

----------

## ⚡ QISC — Quantum-Inspired Superposition Compiler

> _"The compiler that learns, adapts, and evolves with your code."_ _"Optimize for observed reality, not theoretical possibilities."_

Traditional compilers translate source → binary. One way. Done. **QISC rewrites the rules.** It introduces the **Living IR** — an Intermediate Representation that _mutates_, _learns from runtime profiles_, and _collapses_ into the single optimal binary for your actual workload. Think **Schrödinger's Compiler**: the optimal binary exists in superposition until observed through profiling.

```
Source Code --> Living IR  <-> Profile Data --> Evolved IR --> Optimal Binary
                   |               ^
                   └───────────────┘
                      feedback loop

```

**The Evolution Cycle**

```
Compilation 1:  Baseline  ──  100% IR change  ──  Collect profile
Compilation 2:  ████████  ──   80% IR change  ──  2x improvement
Compilation 3:  ███████   ──   30% IR change  ──  1.5x additional
Compilation 4:  ██        ──   10% IR change  ──  1.1x additional
Compilation 5:  ▏         ──    0% IR change  ──  CONVERGED ✓

```

**Standout features:**

-   🧬 **Living IR** — self-aware, adaptive, predictive, provably convergent
-   🎭 **Compiler Personality System** — `friendly`, `snarky`, `sage`, `cryptic` modes with pattern-aware roasts
-   🏆 **Achievement System** — _"Dragon Slayer"_ (O(n²) → O(n log n)), _"Cache Whisperer"_ (>99% hit rate)
-   🔗 **First-class pipelines** (`>>`) with lazy eval, stage fusion, and auto-parallelization
-   🧠 **Pragma intelligence** — `#pragma context:server/cli/embedded`, `optimize:latency/throughput/memory`
-   ✋ **Novel error handling** — `canfail` / `try` / `catch` / `fail` / `!` propagation
-   🔮 **Pattern matching** — `when` / `is` with value, range, and wildcard matching
-   🛡️ **Type system** — `auto` inference, `maybe` optionals, `const`, `typeof`, `sizeof`, `extend` blocks

```qisc
#pragma context:cli
#pragma compiler_personality:snarky
#pragma optimize:latency

proc fibonacci(int n) gives int {
    if n <= 1 { give n; }
    auto a = 0; auto b = 1;
    for int i = 2; i <= n; i++ {
        auto result = a + b;
        a = b; b = result;
        give result;
    }
}

// The compiler, upon seeing your O(n²) loop:
// "O(n²)? In 2026? Really?"

```

<div align="center">

![C11](https://img.shields.io/badge/Written_In-C11-00599C?style=for-the-badge&logo=c&logoColor=white) ![LLVM](https://img.shields.io/badge/Backend-LLVM_21-262D3A?style=for-the-badge&logo=llvm&logoColor=white) ![Version](https://img.shields.io/badge/Version-0.1.0-a78bfa?style=for-the-badge) ![Status](https://img.shields.io/badge/Status-Experimental-ff6347?style=for-the-badge)

_"Your code has reached its final form." — QISC, upon convergence_

</div>

----------

## 🏆 Competitive Programming

<div align="center"> <table> <tr> <td align="center" width="220px"> <br/>

**🟨 LeetCode**

# `2071`

_Top ~2% globally_

[![LeetCode](https://img.shields.io/badge/View_Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/KLSO6YHUdn/)

</td> <td align="center" width="220px"> <br/>

**🟦 CodeChef**

# `1642`

_3★ Rated_

[![CodeChef](https://img.shields.io/badge/View_Profile-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/route_vivid_14)

</td> </tr> </table>

> _Strong foundation in DSA, algorithmic thinking, and problem solving under pressure._

</div>

----------

## 📈 GitHub Stats

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=Trushi28&theme=tokyonight&hide_border=true&background=0D1117&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA)](https://github.com/Trushi28)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Trushi28&style=for-the-badge&color=a78bfa&label=PROFILE+VIEWS)

</div>

----------

## 🤝 Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-trushi--os-a78bfa?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-os-nu.vercel.app/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/trushi-bethu-879984335/) [![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:trushibethu@gmail.com)

<br/>

_"I write the kernel, design the language, train the model, and ship the product."_

</div> <br/> <div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/> </div>

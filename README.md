<div align="center">

<!-- Neural Network Animation -->
<img src="neural-network.svg" alt="Neural Network Inference → TimWood" width="900" />

<!-- Avatar -->
<img src="1.jpg" width="150" height="150" style="border-radius: 50%; border: 3px solid #2E86AB;" />


<!-- Dynamic Typing Animation -->
<p>
  <a href="https://github.com/Timwood0x10">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;size=14&amp;duration=3000&amp;pause=2000&amp;color=2E86AB&amp;center=true&amp;vCenter=true&amp;width=700&amp;lines=$+cat+/etc/timwood_0x10.conf;$+ROLE%3D%22Core+Developer+%26+Systems+Architect%22;$+LANGUAGES%3D%22Rust%2C+Go%2C+Zig%2C+C%2FC%2B%2B%2C+Python%22;$+FOCUS%3D%22Memory+Safety+%7C+Static+Analysis+%7C+AI+Infrastructure%22;$+echo+%22Track+what's+real.+Infer+what's+not.+Never+pretend.%22" alt="Terminal Animation" />
  </a>
</p>

<!-- Badges -->
<p>
  <img src="https://img.shields.io/github/followers/Timwood0x10?label=follow&amp;color=2E86AB&amp;style=for-the-badge&amp;logo=github" />
  <img src="https://komarev.com/ghpvc/?username=Timwood0x10&amp;color=2E86AB&amp;style=for-the-badge&amp;label=PROFILE+VIEWS" />
</p>

</div>

---

## 🧠 About Me

```rust
struct Developer {
    name: &'static str,
    identity: &'static str,
    focus: Vec<&'static str>,
    languages: Vec<&'static str>,
    philosophy: &'static str,
}

impl Developer {
    fn new() -> Self {
        Developer {
            name: "TimWood 0x10",
            identity: "Timwood0x10",
            focus: vec![
                "Memory Safety & Runtime Visualization",
                "Static Analysis & Compiler Tooling (LLVM)",
                "Neural Network Interpretability & Profiling",
                "High-Performance Agent Frameworks",
            ],
            languages: vec!["Rust", "Go", "Zig", "Python"],
            philosophy: "At the intersection of systems programming and AI, I explore the deep logic of code.
                         Never settling for 'it works' — I demand to understand why.",
        }
    }
}
```

Former Web3 engineer. Currently building **tools that understand memory** — because Valgrind doesn't know what `Arc<Rc<Box<...>>>` means, and someone has to fix that.

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Timwood0x10&amp;color=2E86AB&amp;style=for-the-badge&amp;label=PROFILE+VIEWS" alt="Profile Views" />
</p>

---

## 🏗️ Systems & Infrastructure

<table>
<tr>
<td width="50%" valign="top">

### 🔬 [memscope-rs](https://github.com/just-for-dream-0x10/memscope-rs)

**Rust runtime memory analysis tool**

Variable-level memory tracking that Valgrind and AddressSanitizer can't do.

- 🎯 7 detectors (leak, UAF, double-free, data race...)
- 📊 HTML interactive dashboard
- 🧵 Async task-level memory attribution
- 🔗 Arc/Rc clone detection & cycle detection
- ⚡ <5% tracking overhead, 4-thread super-linear scaling
- 📏 112K lines, 2,483 tests, 0 production panic

`Rust` `GlobalAlloc` `UTI-Engine` `Ownership-Graph`

</td>
<td width="50%" valign="top">

### 🔭 [OmniScope](https://github.com/just-for-dream-0x10/OmniScope)

**LLVM IR static safety analysis in Zig**

Static unsafe/FFI boundary analysis at the LLVM IR level.

- 🔍 Unsafe block boundary detection
- 🔗 FFI call chain tracing
- 🛡️ Safety-first analysis philosophy

`Zig` `LLVM-IR` `FFI` `Static-Analysis`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ [go-scheduler](https://github.com/TimWood0x10/go-scheduler)

**Minimal GPU scheduler for AI workloads**

Simple. Deterministic. Reliable.

- 🎯 Designed for inference workloads
- 📐 Deterministic scheduling
- 🚀 Minimal overhead

`Go` `GPU` `Scheduler` `AI`

</td>
<td width="50%" valign="top">

### 🌐 [ethermint](https://github.com/TimWood0x10/ethermint)

**EVM-compatible blockchain in Go**

Fork from Evmos, ported Tendermint to sei-tendermint.

- ⛓️ EVM compatibility layer
- 🔧 Tendermint consensus adaptation
- 📦 Full blockchain node

`Go` `EVM` `Tendermint` `Blockchain`

</td>
</tr>
</table>

---

## 🤖 AI & LLM

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [go-agent](https://github.com/just-for-dream-0x10/go-agent)

**Multi-agent framework in Go**

Custom agent framework with memory distillation and vector search.

- 🧠 Multi-agent orchestration
- 📝 Memory distillation with PGVector
- 🔍 Embedding-based retrieval
- 🔄 Multi-round reasoning loops

`Go` `AI-Agents` `PGVector` `Embedding`

</td>
<td width="50%" valign="top">

### 🎨 [StyleAgent](https://github.com/TimWood0x10/StyleAgent)

**AI-powered outfit recommendation system**

- 🧠 AI-based style analysis
- 👕 Outfit recommendation engine
- 📸 Image understanding pipeline

`Python` `AI` `Recommendation` `Computer-Vision`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📈 [predict](https://github.com/TimWood0x10/predict)

**Crypto currency Decision Engine**

- 📊 Market data analysis
- 🤖 ML-based prediction pipeline
- 💹 Trading signal generation

`Python` `ML` `Crypto` `Finance`

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

---

## 📚 Teaching & Visualization

<table>
<tr>
<td width="50%" valign="top">

### 📐 [Basic_math](https://github.com/just-for-dream-0x10/Basic_math)

**Interactive ML math visualization system**

32 interactive modules, 150+ Manim animations, 8 learning paths.

- 🎯 32 modules: linear algebra, optimization, DL, frontier
- 🎬 150+ Manim animation scenes
- 📊 Real-time parameter tuning & observation
- 🗺️ 133 concepts, 20-layer dependency graph
- 📐 Transformer parameter/FLOPs/memory calculators

`Python` `Streamlit` `Manim` `Math-Education`

</td>
<td width="50%" valign="top">

### 🏗️ [Transformer_explorer](https://github.com/just-for-dream-0x10/Transformer_explorer)

**Transformer & Mamba architecture visualization**

Math-driven deep learning architecture explainer with animations.

- 🎬 Manim animations: Encoder, Decoder, Cross Attention, RoPE
- 🐍 Mamba SSM: selective mechanism, discretization
- 🔬 Interactive: attention computation, softmax temperature
- 📊 Training: AdamW, BPE, mixed precision, loss analysis
- ⚡ Transformer vs Mamba complexity comparison

`Python` `Manim` `Streamlit` `Transformer`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔬 [Model_explorer](https://github.com/just-for-dream-0x10/Model_explorer)

**Neural network computation anatomy lab**

Layer-by-layer parameter, FLOPs and numerical computation analysis.

- 🔢 8 layer types: Conv2d, Linear, MHA, LSTM, Embedding...
- 📊 7 networks: ResNet, VGG, BERT, GPT-2, ViT...
- ⚡ Parameter/FLOPs/memory analysis with optimization tips
- 🏛️ Failure case museum: gradient vanishing, parameter explosion
- 🧬 Single neuron analysis: Sigmoid, Tanh, ReLU, LSTM, GRU

`Python` `Streamlit` `PyTorch` `Visualization`

</td>
<td width="50%" valign="top">

### 📖 [beginML](https://github.com/Timwood0x10/beginML)

**ML notes & tutorials**

Beginner-friendly machine learning learning materials.

- 📝 Comprehensive ML notes
- 🎯 From zero to practice
- 🌐 Interactive HTML format

`HTML` `Machine-Learning` `Education`

</td>
</tr>
</table>

---

## 📊 Stats

<table align="center" style="border: none;">
  <tr>
    <td align="center">
      <!-- CI-generated: GitHub Stats (contributions + repos) -->
      <img src="https://raw.githubusercontent.com/Timwood0x10/Timwood0x10/output/github-stats.svg" alt="GitHub Statistics" width="450" />
    </td>
    <td align="center">
      <!-- CI-generated: Top Languages -->
      <img src="https://raw.githubusercontent.com/Timwood0x10/Timwood0x10/output/top-languages.svg" alt="Top Languages" width="400" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <!-- Streak stats -->
      <img height="170" src="https://github-readme-streak-stats.herokuapp.com?user=Timwood0x10&amp;theme=tokyonight&amp;hide_border=true&amp;background=0d1117&amp;stroke=2E86AB&amp;ring=2E86AB&amp;fire=FD7E14&amp;currStreakLabel=c9d1d9&amp;sideLabels=c9d1d9&amp;dates=c9d1d9" />
    </td>
  </tr>
</table>

---

##  Contribution Graph

<p align="center">
  <a href="https://github.com/Timwood0x10">
    <img src="https://raw.githubusercontent.com/Timwood0x10/Timwood0x10/output/github-snake-dark.svg" alt="Snake Animation" style="max-width: 100%;" />
  </a>
</p>

---

## 🛠️ Tech Stack

<div align="center">

| Systems | AI & Data | Teaching |
|---------|-----------|----------|
| <img src="https://img.shields.io/badge/Rust-000000?style=flat&amp;logo=rust&amp;logoColor=white" /> | <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&amp;logo=go&amp;logoColor=white" /> | <img src="https://img.shields.io/badge/Zig-F7A41D?style=flat&amp;logo=zig&amp;logoColor=white" /> |
| <img src="https://img.shields.io/badge/LLVM-262D53?style=flat&amp;logo=llvm&amp;logoColor=white" /> | <img src="https://img.shields.io/badge/Python-3776AB?style=flat&amp;logo=python&amp;logoColor=white" /> | <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&amp;logo=docker&amp;logoColor=white" /> |
| <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&amp;logo=linux&amp;logoColor=black" /> | <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&amp;logo=tensorflow&amp;logoColor=white" /> | <img src="https://img.shields.io/badge/Manim-1C87C7?style=flat&amp;logoColor=white" /> |

</div>

---

## 💡 Philosophy

```bash
$ philosophy --query "what drives you"
> "In the world of 0x10, every line of code is an exploration.
>  From Rust's memory safety to Zig's low-level control,
>  From Transformer attention to LLVM instruction streams,
>  I believe: understand the foundations, then build the future.
>  Never settle for 'it works' — dig deeper."
```

> **Think boldly. Implement carefully. Question everything.**

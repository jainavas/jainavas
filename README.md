# Hi, I'm Jaime Navascués 👋

**Embedded Systems Engineer • Data Engineer**

42 Madrid graduate specializing in **low-level systems programming (C/C++)** and **data pipeline engineering (Python)**. Completed Common Core in 8 months (6% graduation rate), now pursuing **42 Outer Core - Data Engineering** track.

---

## 🎯 About Me

- 🎓 **42 Madrid** - Common Core completed in 8 months (6% graduation rate)
- 📚 **Currently**: 42 Outer Core (Data Engineering specialization)
- 💼 **Seeking**: Embedded Software Engineer (C/C++) OR Data Engineer roles
- 💻 **Core Stack**: C, C++, Python, SQL, Docker, Git
- 🌍 **Location**: Madrid, Spain 🇪🇸
- 🔗 **Portfolio**: [jainavas.me](https://jainavas.me)

---

## 🔧 Embedded Systems & Low-Level Programming

### ⚔️ [War](https://github.com/jainavas/war) - CoreWar Virtual Machine & Obfuscator
*42 Outer Core | NEW - January 2026*

Virtual machine implementation for CoreWar with advanced code obfuscation tools.

**Tech Stack**: C, Assembly, Python, ELF Binary Format

**Key Features**:
- 🖥️ **Virtual Machine**: Custom VM architecture for executing champion programs
- 🔐 **Code Obfuscator**: 100% reversible C source obfuscation tool (Python)
- 📊 **Visual Illegibility**: Uses confusing character combinations (O/0/l/1/I/_)
- 🛡️ **Protection System**: Preserves C keywords, stdlib, ELF structures, POSIX API
- 🔄 **Deterministic**: Reproducible obfuscation with seed parameter
- 📁 **Dual Mode**: Single-file and directory batch processing
- 🧪 **Zero Dependencies**: Pure Python 3 standard library

**Embedded Relevance**: Virtual machine design, low-level memory management, assembly language, binary format understanding, toolchain development.

---

### 🐚 [Minishell](https://github.com/jainavas/minishell) - Unix Shell Implementation ⭐ 1
*42 Common Core | Systems Programming*

Full-featured Bash-like shell with process management, pipelines, and built-in commands.

**Tech Stack**: C, Unix System Calls, Readline Library

**Key Features**:
- 🔄 **Process Control**: Fork/exec process creation and management
- 📡 **Pipelines**: Multi-command chaining with pipe operator (`|`)
- 📁 **Redirections**: Input (`<`), output (`>`), append (`>>`), heredoc (`<<`)
- 💲 **Variable Expansion**: Environment variables and exit status (`$?`)
- 🛠️ **Built-ins**: echo, cd, pwd, export, unset, env, exit
- 📊 **Signal Handling**: CTRL-C, CTRL-D, CTRL-\ (POSIX signals)
- 🧠 **Memory Safe**: Zero leaks (Valgrind validated)

**Embedded Relevance**: Process management, IPC mechanisms, signal handling, POSIX compliance (critical for embedded Linux systems).

---

### 🧵 [Philosophers](https://github.com/jainavas/philosophers) - Multithreading & Synchronization ⭐ 2
*42 Common Core | Dining Philosophers Problem*

Classical concurrency challenge implementing thread-safe resource sharing.

**Tech Stack**: C, POSIX Threads (pthread), Mutexes

**Key Features**:
- ⚡ **Real-time synchronization**: Mutex-based resource locking
- 🎯 **Deadlock prevention**: Fair resource acquisition strategy
- 📊 **Precise timing**: Microsecond-accurate state management (<10ms death detection)
- 🛡️ **Race condition handling**: Thread-safe logging and state updates
- 🔄 **Resource management**: Efficient fork (resource) allocation

**Embedded Relevance**: RTOS-style task management, critical section handling, timing constraints, essential for real-time embedded systems.

---

### 🎮 [Cub3D](https://github.com/jainavas/cub3d) - Real-Time 3D Raycasting Engine
*42 Common Core | Graphics Programming*

First-person 3D maze renderer using raycasting (Wolfenstein 3D-style).

**Tech Stack**: C, MinilibX (X11), Raycasting Algorithm, Linear Algebra

**Key Features**:
- 🎨 **Texture mapping**: Per-direction wall textures
- ⚡ **Real-time rendering**: 60 FPS without GPU acceleration
- 🧮 **Mathematical optimization**: Vector/matrix transformations
- 🎮 **Input handling**: Smooth keyboard controls with collision detection
- 🗺️ **Config parsing**: Custom `.cub` map format

**Embedded Relevance**: Real-time constraints, CPU-only graphics, memory efficiency (relevant for resource-constrained embedded displays).

---

### 🔀 [Push_swap](https://github.com/jainavas/pushswap) - Algorithm Optimization ⭐ 1
*42 Common Core | Sorting Algorithm Challenge*

Efficient integer sorting using limited stack operations.

**Tech Stack**: C, Algorithm Design, Complexity Analysis

**Key Features**:
- 📊 **Optimized sorting**: <700 operations for 100 integers, <5500 for 500
- 🧠 **Custom algorithm**: Hybrid approach (radix-inspired with chunk sorting)
- ⚡ **Performance**: O(n log n) average complexity
- 🔧 **Memory efficient**: Minimal heap allocation
- 📈 **Edge case handling**: Duplicates, overflow detection

**Embedded Relevance**: Algorithm optimization under resource constraints (critical for microcontroller environments).

---

## 📊 Data Engineering & Machine Learning

### 🌿 [Leaffliction](https://github.com/jainavas/leaffliction) - Computer Vision Pipeline
*42 Outer Core | 161 campus completions*

End-to-end ML pipeline for plant disease classification from leaf images.

**Tech Stack**: Python, TensorFlow/PyTorch, OpenCV, NumPy, Pandas

**Key Features**:
- 🔬 **Dataset analysis**: Statistical EDA with visualization
- 🔄 **Data augmentation**: Rotation, scaling, distortion for robustness
- 🧠 **Transfer learning**: Pre-trained CNN fine-tuning
- 📈 **>90% accuracy**: Production-ready validation metrics
- 🖼️ **Feature extraction**: Image preprocessing pipeline

**Data Engineering Relevance**: ETL pipeline design, data preprocessing at scale, model deployment workflow.

---

### 📊 [DSLR](https://github.com/jainavas/DSLR) - ML from Scratch
*42 Outer Core | Data Science & Logistic Regression*

Hogwarts house classification using logistic regression implemented from scratch.

**Tech Stack**: Python, NumPy, Pandas, Matplotlib

**Key Features**:
- 📈 **Statistical analysis**: Descriptive statistics (mean, std, quartiles) from scratch
- 📊 **Data visualization**: Histograms, scatter plots, pair plots
- 🧠 **Logistic regression**: Gradient descent optimization (no sklearn)
- 🎯 **Multi-class classification**: One-vs-all strategy
- 📉 **Feature correlation**: Discriminative feature identification

**Data Engineering Relevance**: Statistical computing, data exploration, ML fundamentals without black-box libraries.

---

### 🐍 [Learn2Slither](https://github.com/jainavas/Learn2Slither) - Reinforcement Learning
*42 Outer Core | Q-Learning Agent*

Snake game AI using Q-Learning and experience replay.

**Tech Stack**: Python, Q-Learning, Pygame

**Key Features**:
- 🤖 **Q-Learning agent**: State-action-reward training loop
- 🔄 **Experience replay**: Learn from successful trajectories
- 📊 **State compression**: Efficient state representation
- 📈 **Hyperparameter tuning**: Epsilon decay, learning rate optimization
- 🎮 **Visual training**: Real-time game visualization during training

**Data Engineering Relevance**: Training pipeline design, state management, performance metrics tracking.

---

### 🎮 [Transcendence](https://github.com/jainavas/transcendence) - Full-Stack Platform ⭐ 1
*42 Common Core Final | Success Rate: 7%*

Real-time multiplayer Pong with microservices architecture.

**Tech Stack**: TypeScript, Node.js (Fastify), SQLite, Docker, WebSockets

**Key Features**:
- 📊 **Database design**: Relational schema for users, matches, stats
- 📈 **Monitoring**: Grafana + Prometheus for metrics
- 🔄 **Real-time data**: WebSocket-based event streaming
- 🏆 **Analytics**: Leaderboards, statistics aggregation
- 🐳 **Infrastructure**: Docker Compose orchestration

**Data Engineering Relevance**: Database design, real-time data streaming, monitoring infrastructure, microservices.

---

## 🛠️ Technical Skills

### **Languages**
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-654FF0?style=flat&logo=assemblyscript&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

### **Embedded & Systems**
- **Concurrency**: POSIX Threads, Mutex, Semaphores
- **IPC**: Pipes, Signals, Shared Memory
- **System Calls**: Process management, File I/O
- **Virtual Machines**: Custom VM architecture, bytecode execution
- **Memory Management**: Manual allocation, leak prevention
- **Performance**: Real-time constraints, optimization
- **Assembly**: x86, ARM architectures

### **Data Engineering & ML**
- **Data Processing**: Pandas, NumPy, ETL pipelines
- **Machine Learning**: TensorFlow, PyTorch, Scikit-learn
- **Computer Vision**: OpenCV, Image preprocessing
- **Databases**: SQL (SQLite, PostgreSQL)
- **Monitoring**: Grafana, Prometheus

### **Tools & DevOps**
- **Containerization**: Docker, Docker Compose
- **Version Control**: Git, GitHub workflows
- **Build Tools**: Make, CMake
- **Debugging**: GDB, Valgrind, AddressSanitizer
- **Scripting**: Python, Bash

---

## 🔗 More Projects

Explore my full portfolio: [github.com/jainavas](https://github.com/jainavas?tab=repositories)

Notable mentions:
- **[Lem-in](https://github.com/jainavas/lem-in)** ⭐ 1 - Graph algorithms & flow optimization (C)
- **[Gomoku](https://github.com/jainavas/gomoku)** - AI game engine with minimax (C++)
- **[Pipex](https://github.com/jainavas/pipex)** - Unix pipe mechanism implementation (C)

---

## 📫 Let's Connect

I'm actively seeking opportunities as:
- 🔧 **Embedded Software Engineer** (C/C++) - RTOS, drivers, firmware, virtual machines
- 📊 **Data Engineer** - ETL pipelines, data infrastructure, ML deployment

💼 [LinkedIn]([https://linkedin.com/in/jai](https://www.linkedin.com/in/jaimenavascues-p/))  
🌐 [Portfolio](https://jainavas.me)

---

*Last updated: February 2026*

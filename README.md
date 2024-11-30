# Cache Coherence Simulator

This project simulates cache coherence mechanisms in a distributed system, providing an environment for understanding and testing coherence protocols.

---

## Getting Started

### Prerequisites
Before you begin, ensure you have the following installed on your system:
- **Git**: Download and install from [Git](https://git-scm.com/).
- **G++ Compiler**: Part of the GCC toolchain. Install via:
  - **Windows**: Install [MinGW](http://www.mingw.org/) and ensure `g++` is added to your PATH.
  - **Linux**: Use `sudo apt install g++`.
  - **MacOS**: Install via Xcode Command Line Tools: `xcode-select --install`.

---

### Steps to Clone, Compile, and Run

You can copy and paste the following commands as a single block to get started:

```bash
# Clone the repository
git clone https://github.com/AvikH08/Cache_Coherence.git

# Navigate to the project directory
cd Cache_Coherence

# Compile the project
g++ main.cpp Processor.cpp Cache.cpp Bus.cpp Directory.cpp MainMemory.cpp AddressUtils.cpp -o main

# Run the program (Windows)
.\main

# Run the program (Linux/MacOS)
./main

```
### For Windows
```bash
.\main
```
### For Linux/MacOS
```bash
./main
```


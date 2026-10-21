# Hi there, I'm Redan Ganim! 👋

## 🚀 About Me

I'm a **Software Engineer** with a B.Sc. in Software Engineering from Braude Academic College of Engineering, currently specializing in **Real-Time Embedded Systems** at Real Time College (rt-ed.co.il). I'm passionate about low-level programming, embedded systems, and building efficient, reliable software.

- 🎓 **Education**: B.Sc. in Software Engineering — Braude Academic College of Engineering
- 📚 **Specialization**: Real-Time Embedded Linux Program — Real Time College
- 📧 **Contact**: RedanGanim@gmail.com

---

## 🛠️ Technical Skills

### Programming Languages

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![Assembly](https://img.shields.io/badge/Assembly-525252?style=for-the-badge&logo=assemblyscript&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### Embedded & Systems

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Embedded C](https://img.shields.io/badge/Embedded_C-00599C?style=for-the-badge&logo=c&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white) ![ARM](https://img.shields.io/badge/ARM_Cortex--M-0091BD?style=for-the-badge&logo=arm&logoColor=white) ![GCC](https://img.shields.io/badge/GCC/GDB-A42E2B?style=for-the-badge&logo=gnu&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Technologies & Frameworks

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![JavaFX](https://img.shields.io/badge/JavaFX-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

### Core Competencies

- **Embedded C & Low-Level Programming**
- **ARM Cortex-M (STM32), DMA, UART / SPI / I2C / ADC**
- **Linux System Administration**
- **Networking & Protocols (UDP/Ethernet, lwIP)**
- **Real-Time Systems & Interrupt Handling**
- **Memory Management & Dynamic Allocation**
- **Bitwise Operations & Data Encoding**
- **Data Structures & Algorithms**
- **Object-Oriented Programming (C++ / Java)**
- **Database Design & Management**
- **Full-Stack Development**

---

## 📚 Real-Time Embedded Linux Program

**Real Time College (rt-ed.co.il)** — In Progress

A professional specialization program focused on embedded systems development, covering:

| Module                         | Status         |
|--------------------------------|----------------|
| 🐧 Linux System Administration | ✅ Completed   |
| ⚙️ Embedded C Programming      | ✅ Completed   |
| 🌐 Networking                  | ✅ Completed   |
| 🔩 ARM Embedded Systems        | ✅ Completed   |
| 🔧 Embedded C++ Programming    | ✅ Completed   |
| 🐧 Embedded Linux              | 🔄 In Progress |

---

## 🏆 Featured Projects

### 🔌 STM32F756 Peripheral Hardware Tester — ARM / Embedded C

**Client/Server Hardware Verification System | ARM Embedded Systems Final Project**

[View on GitHub](https://github.com/Redan1997/ARM-Project-stm32f756-hardware-tester)

- A Linux C command-line tool sends test commands over UDP/Ethernet to an STM32F756ZG board, which runs the test and returns pass/fail
- Tests Timer, UART, SPI, I2C and ADC, using DMA loopback between on-chip instances for UART, SPI and I2C
- Hardware CRC-32 verification for large buffers; ADC validated against the factory calibration value
- Bare-metal lwIP stack (no RTOS) with DHCP and a custom binary UDP protocol
- Linux client with automatic board discovery, persistent CSV test records and a Makefile build

*Technologies: C, STM32 HAL, lwIP, DMA, UART/SPI/I2C/ADC, UDP, STM32CubeIDE, GCC, Make*

---

### 🃏 Black-Jack Game — Embedded C

**Terminal-Based Game | Embedded C Final Project**

[View on GitHub](https://github.com/Redan1997/Black-Jack-Game-Project)

- Implemented a full Black-Jack game between a human player and a computer-controlled dealer
- Designed a custom card encoding system using bitwise operations on a single `uint8_t`
- Built singly linked lists from scratch for deck and hand management — no arrays
- Managed dynamic memory allocation and deallocation manually with zero memory leaks
- Followed strict embedded constraints: no global variables, individual allocation per card, pure bitwise I/O

*Technologies: C, Linked Lists, Bitwise Operations, Dynamic Memory Allocation*

---

### 🕹️ Real-Time DOS & XINU — Assembly 8086 & C

**Real-Time Game Engine | Score: 100**

[View on GitHub](https://github.com/Redan1997/Operating-systems-and-real-time)

- Engineered a complete real-time game engine under Turbo C & Assembly in real-mode DOS
- Implemented custom interrupt handlers (INT 8/9) for direct keyboard input
- Achieved 60+ FPS via direct VGA memory manipulation (0xB800)
- Designed a timer-based architecture with dynamic difficulty scaling under strict real-time constraints

*Technologies: Assembly 8086, C, Turbo C, XINU, Hardware Interrupts*

---

### 🐾 Vet Management System — C++

**Object-Oriented Design | C++14**

[View on GitHub](https://github.com/Redan1997/Vet-Management-System-Cpp)

- Abstract `Animal` base class with `Dog`, `Cat` and `Cow` subclasses, each overriding a pure virtual `check_health()`
- `Vet` implemented as a Singleton; `dynamic_cast` (RTTI) used to filter sick dogs
- Memory managed with `std::unique_ptr` (RAII) and const-correctness throughout
- Compiles with zero warnings under `-Wall -Wextra -Weffc++ -pedantic`

*Technologies: C++14, Inheritance, Polymorphism, Singleton, Smart Pointers*

---

### ➗ Quadratic Equation Class — C++

**Operator Overloading & Resource Management | C++14**

[View on GitHub](https://github.com/Redan1997/Quadratic-Equation-Cpp)

- Class that recalculates its roots automatically whenever a coefficient changes
- Operator overloading (`+`, `<<`) in member and friend forms
- Full Rule of Five with manual `new[]` / `delete[]` and no leaks; `noexcept` move operations
- Exception safety: throws `std::invalid_argument` on invalid state without leaking resources

*Technologies: C++14, Operator Overloading, Rule of Five, Exception Safety*

---

### 🏞️ Park Management System

**Full-Stack Java Application | Score: 93**

[View on GitHub](https://github.com/Redan1997/project-park_GoNature)

- Developed a comprehensive client-server system using OCSF framework
- Integrated MySQL database for efficient data management
- Created multiple user interfaces with JavaFX/Scene Builder
- Implemented secure authentication and CRUD operations
- Features: booking management, payment processing, visitor monitoring

*Technologies: Java, JavaFX, MySQL, OCSF Framework*

---

## 🌍 Languages

- **Arabic**: Native
- **Hebrew**: Fluent
- **English**: Proficient

---

## 🎯 Currently Looking For

I'm seeking **Embedded Software Engineer** or **Junior Systems Developer** roles where I can apply my low-level C programming, Linux, and networking skills in real-world embedded products. If you have an exciting opportunity or want to collaborate, feel free to reach out!

---

⭐️ From [Redan Ganim](https://github.com/Redan1997)

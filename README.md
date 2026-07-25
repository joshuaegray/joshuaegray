## Hi, I'm Josh 👋

I'm a third-year Computer Science major at the University of California, Santa Barbara graduating Fall 2027 with a strong interest in software engineering and computer architecture. I enjoy building systems from the ground up, having worked on full-stack applications, backend systems, and processor emulators.


Right now, I'm working as a Software Engineering Intern at UCSB, where I'm designing and building a [FAIR-compliance pipeline](https://github.com/UCSB-Library-Research-Data-Services/metadata-checker) to assess metadata quality for datasets published on Dataverse, UCSB's institutional academic repository system.

I'm also working as a Computer Architecture Researcher in the UCSB ArchLab with Professor Balkind. My research specifically focuses on hardware accelerators and the optimizations designed for their unique microarchitectures. We've implemented an ISA for OpenTPU as well as a generalized systolic-array optimization into Professor Balkind's new ISA-design framework [Isacomp](https://github.com/isacomp-project/isacomp).

LinkedIn: https://www.linkedin.com/in/joshuaegray/
Personal Website: https://joshuaegray.github.io/

## Experience

- Software Development Intern @ IBM (Incoming Fall 2026)
- Software Engineering Intern @ UCSB Library Research Data Services (Spring 2026-Present)
- Computer Architecture Researcher @ UCSB ArchLab (Fall 2025-Spring 2026)
- Full Stack Software Engineering Intern @ ConstructWise (Summer 2025)
- Frontend Developer + HCI Researcher @ Humanity Unleashed (Fall 2024)

## Projects

### Chip-8 Emulator
- [Repo](https://github.com/joshuaegray/chip8-emulator)
- A CHIP-8 Emulator built from the ground up in C++, including the CPU execution, memory management, timers, display, and keypad input. Check out the repo!

### SB Hacks 2026 Hardware Winner: Voice Controlled Robotic Arm

- [Repo](https://github.com/nathanqiuUCSB/RoboticArmHelper)
- Awarded best hardware hack at the 2026 UC Santa Barbara Hackathon
- Built a voice-controlled robotic arm that detects and manipulates real-world objects using computer vision
- Designed OpenCV-based visual feedback loops enabling autonomous navigation and target alignment in 3D space from a single camera
- Implemented FastAPI backend to route frontend audio input into motor control logic for robotic arm actuation
- Tech Stack: React, FastAPI, Python, Grok, OpenCV, LeRobot

### Pipelined MIPS CPU | CS154

Implemented a 5-stage pipelined MIPS processor using PyRTL, including pipeline registers, hazard detection, and forwarding logic to ensure correct execution of dependent instructions. Verified processor behavior through cycle-accurate simulation of custom assembly programs and debugging of pipeline execution.
- CPU pipeline design (IF, ID, EX, MEM, WB)
- Data hazard detection and pipeline stalling
- Forwarding to minimize pipeline stalls
- Hardware design and simulation using PyRTL

### FAIR Compliance Metadata Checker | UCSB Library Research Data Services

Building a production-level metadata validation tool for Dataverse, UCSB's 10+ petabyte institutional repository
- [Repo](https://github.com/UCSB-Library-Research-Data-Services/metadata-checker)
- Cut metadata processing time by 76% by designing a SQLite caching layer to avoid redundant API calls
- Architected a modular YAML-configurable translation engine mapping JSON metadata to DataCite XML,
eliminating hardcoded logic and enabling scalability with zero code changes
- Built a FastAPI/Jinja2 backend serving real-time validation reports using async httpx calls to keep request
handling non-blocking
- Secured Dataverse's external tool integration callback protocol using base64-encoded, scoped signed URLs to avoid direct handling of API credentials

### Two-Tier E-Commerce & Inventory System | CS174A

A Java/JDBC CLI application pair simulating a real-world online retail platform, built on an Oracle AI Database.
- Designed and implemented a normalized relational schema (11+ tables) on Oracle AI Database modeling products, customers, orders, inventory, and shipping.
- Enforced referential integrity via foreign keys, CHECK constraints, and regex-validated identifiers
- Built a full customer-facing shopping flow backed by parameterized, injection-safe JDBC queries against Oracle AI Database
- Built a manager dashboard for price/status overrides, order pruning, and monthly sales analytics (top products, top categories, top customers) via aggregate SQL queries
- Used JDBC transactions with explicit commit and rollback control to guarantee atomicity across multi-table operations

## Papers

[Creating a Cooperative AI Policymaking Platform through Open Source Collaboration](https://arxiv.org/abs/2412.06936)

## Skills 🛠️

- Languages: C/C++, Python, Java, JavaScript, MIPS assembly, C#, HTML, CSS, Verilog 
- Frameworks: React, Next.js, Django, FastAPI, Jinja2
- Developer Tools: Git, Linux, Bash, Postman, Claude Code, Makefiles, GDB, Valgrind, Neovim, VS Code 
- Databases and Cloud Tools: Supabase (PostgreSQL), SQLite, Oracle Cloud (Oracle AI Database)

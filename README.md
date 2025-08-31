# IPnetSolver v2.0.0

**IPnetSolver** is a command-line tool that automates **FLSM**, **VLSM**, **Supernetting**, and **IP/Decimal-to-Binary conversion**.
It also supports **/1 - /32 prefix** and it's useful for learning subnetting, supernetting, and binary conversion to save time and avoid manual errors.

---

## Features

- **FLSM (Fixed-Length Subnet Masking)**
- **VLSM (Variable-Length Subnet Masking)**
- **Supernetting**
- **IP & Decimal-to-Binary Converter**
- **Calculation Guide (NEW)**

---

## What’s New in v2.0.0

- **Colorized Output** using `colorama` - CLI isn’t boring anymore!
- **Calculation Guide Feature** - Type `'guide'` to learn subnetting, supernetting, and binary conversion
- **Rewritten Interface** — Includes ASCII art headers, clean sections, and logical flows
- **More Accurate Supernetting** - Better validation for overlaps, invalid alignments, and prefix gaps/overlaps
- **Clear Mode (`type 'q'`)** - Instantly clears past clutter

---

## Previous Versions

Looking for older versions of IPnetSolver before v2.0.0?

[Click here to browse the original versions (beta to v1.x.x) inside the Toolbox Repo](https://github.com/R3ym0nd0/Python-Resources/tree/main/MyToolBox/IPnetSolver)

> These were stored in a MyToolBox repository before this tool got its own dedicated repo.

---

##  Screenshots

### Main Menu (New UI)
![main_menu](https://github.com/user-attachments/assets/58c46245-0204-49de-9705-69ec830a0af4)

### Calculation Guide (Learn FLSM, VLSM, Supernetting & IP/Numbers to Binary)
![image](https://github.com/user-attachments/assets/7e005b06-9340-4d73-9bad-4bc0c965bc6c)

## FLSM Example
![flsm_example](https://github.com/user-attachments/assets/a8fd2aae-6cf5-4da0-9c05-33cbff7d6041)

## VLSM Example
![vlsm_example](https://github.com/user-attachments/assets/d5c5d788-775c-4ba0-b45a-24d0546c9699)

## Supernetting Example
![supernet_example](https://github.com/user-attachments/assets/c33dc5a8-37f2-40f2-8fd7-5947b1bacd25)

## IP Addresses/Whole Numbers to Binary Converter Example

![number_binary](https://github.com/user-attachments/assets/77966c0f-af6f-4ae5-a10c-ef086daa6a8c)

---

![ip_binary](https://github.com/user-attachments/assets/b7eee1c2-2b23-4dcc-9c8b-6839803fdf86)

---

## Use Cases

- Learning how subnetting works from scratch  
- Automate real-world subnetting and supernetting
- Convert IPs and numbers to binary for exams or scripts
- CLI-based tool for students, network engineers and pentesters

---

## How to Run

```bash
Make sure you are using Python 3.3+

# Clone the repository
git clone https://github.com/R3ym0nd0/IPnetSolver.git
cd IPnetSolver

# Install required modules
pip install colorama

# Run IPnetSolver
python ipnetsolver.py

# Lesson 2: CPU Fundamentals

## Objective

Understand what the CPU is, how it works, and why it matters in
cybersecurity.

## What is a CPU?

The **Central Processing Unit (CPU)** is the component that **fetches,
decodes, and executes instructions**. It does not decide whether a
program is good or malicious---it simply executes instructions.

## Real-Life Analogy

Imagine a chef in a restaurant.

-   Customer gives an order.
-   Chef follows the recipe.
-   Chef does not decide to cook something else.

Similarly, the CPU follows program instructions exactly.

## What is an Instruction?

An instruction is a command that tells the CPU to perform a task.

Examples: - Read data - Add two numbers - Display text - Open a file

## Main Components of a CPU

### 1. Control Unit (CU)

Coordinates CPU operations and directs other components.

### 2. Arithmetic Logic Unit (ALU)

Performs arithmetic and logical operations.

### 3. Registers

Very small and extremely fast memory locations inside the CPU used to
hold data currently being processed.

### 4. Cache Memory

Stores frequently used data close to the CPU for faster access than RAM.

## Memory Speed

Fastest → Slowest

1.  Registers
2.  Cache
3.  RAM
4.  SSD/HDD

## Fetch--Decode--Execute Cycle

1.  Fetch the instruction from memory.
2.  Decode the instruction.
3.  Execute the instruction.
4.  Repeat millions or billions of times every second.

## Example: Opening Notepad

1.  Double-click `notepad.exe`.
2.  Windows locates the executable on the SSD.
3.  The program is loaded into RAM.
4.  The CPU fetches and executes instructions.
5.  Windows creates a process.
6.  Notepad appears on the screen.

## Cybersecurity Relevance

The CPU executes both legitimate and malicious programs without knowing
the difference.

Security tools such as: - EDR - Antivirus - Sysmon

observe behaviour such as: - Process creation - File changes - Registry
changes - Network connections

to determine whether activity is suspicious.

## Hands-on Lab

1.  Open **Task Manager** (`Ctrl + Shift + Esc`).
2.  Select the **Performance** tab.
3.  Click **CPU**.
4.  Record:
    -   CPU model
    -   Number of cores
    -   Number of logical processors
    -   Current CPU utilisation

## Key Takeaways

-   The CPU executes instructions.
-   Instructions are processed using the Fetch--Decode--Execute cycle.
-   Registers and cache are much faster than RAM.
-   The CPU does not identify malware; security tools analyse behaviour.

## Quiz

1.  What is the primary role of the CPU?
2.  What is an instruction?
3.  What does the ALU do?
4.  Why are registers faster than RAM?
5.  Why can't the CPU distinguish malware from legitimate software?

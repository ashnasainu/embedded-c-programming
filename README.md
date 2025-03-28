# Embedded C Programming  

This repository contains fundamental Embedded C programs focused on microcontroller-based applications, including handling external interrupts and other embedded system concepts. It is intended for beginners and enthusiasts to understand and practice core Embedded C programming concepts.

## 📂 Repository Structure  

- **EXTERNAL INTERRUPT SWITCH** - Implementation of an external interrupt switch using embedded C in MPLAB.
- **TIMER 0_LED BLINKING** - Implementation of an LED blinking with timer 0 using embedded C in MPLAB.
- **LED MULTIPLEXING_TIMER INTERRUPT** - Implementation of an LED multiplexing with timer interrupt using embedded C in MPLAB.
- **UART (Universal Asynchronous Receiver-Transmitter)** - Implementation of UART communication with LED blinking using embedded C in MPLAB.


## 🔧 Getting Started  

### Prerequisites  
ss
- Microcontroller (PIC16F887)  
- MPLAB X IDE installed.  
- MPLAB XC8 Compiler.  
- PIC development board and necessary hardware components.  

### Compilation & Execution  

1. **Open MPLAB X IDE**  
   - Create a new project and select your target PIC microcontroller.  
   - Choose the **MPLAB XC8 Compiler**.  

2. **Add the Source Code**  
   - Copy and paste the C code into `main.c`.  
   - Configure the necessary registers for your external interrupt.  

3. **Build the Project**  
   - Click on **Build Project (F11)** to compile the code.  

4. **Flash the Code to the Microcontroller**  
   - Connect your programmer (e.g., PICkit 3/4).  
   - Click on **Make and Program Device (F5)** to upload the code.  

5. **Run & Test**  
   - Power on your microcontroller and verify the interrupt functionality.  

## 📜 License  

This project is open-source. Feel free to use and modify it as needed.  

# Insignia-Flex-NS-P89W6100-Drivers
Insignia Flex 8.9 inch Drivers. Follow Raed Me installation guide
Phase 1: The Foundation (Do These First)
These drivers map the core tracks on the motherboard. Until these are installed, Windows cannot even see your audio, battery, or touchscreen hardware.

MBI (Mailbox Interface / Sideband Fabric)

GPIO & GPIOVirtual (General Purpose Input/Output)

I2C (The main data bus—absolutely critical for everything else)

UART

Phase 2: Power & Core System
Now that the data pathways are open, activate the power management and system logic.

PMIC (Power Management IC)

BM (Battery Management)

PSS (Processor Support System)

TXEI (Trusted Execution Engine)

DPTF (Dynamic Platform & Thermal Framework)

👉 REBOOT THE TABLET NOW

Phase 3: Video & Performance
Graphics (Intel HD Graphics—this will instantly drop your CPU usage by enabling hardware acceleration for the desktop display)

Phase 4: Peripherals (Do These Last)
Only attempt these after Phase 1 and Phase 2 are fully active and the system has been rebooted. They depend entirely on those underlying buses to function.

Audio

Sensors

Camera

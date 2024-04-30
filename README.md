# PicoW-Ducky-Server
A Wireless keystroke injector.

![pico image](https://github.com/Master629/PicoW-Ducky-Server/assets/125476463/0efbedc9-9807-42a5-b591-0ce250ef1e07)


## Features

- Emulates USB Rubber Ducky functionality over Wi-Fi.
- Remote scripting and automation capabilities.
- Requires only one Microcontroller.
- Based on the [pico-ducky](https://github.com/dbisu/pico-ducky) project.
- Cost-effective, approximately $6-15.

## Getting Started

### Prerequisites

- Raspberry Pi Pico W.
- Micro-USB Cable.
- Basic Knowledge.

### Installation

1. **Reset The Pico**

   - Download the reset firmware from [flash_nuke.uf2](https://datasheets.raspberrypi.com/soft/flash_nuke.uf2)
   - While holding the BOOTSEL button on the Pico, plug in the USB cable to your computer.
   - When the RPI-RP2 drive shows up on your computer, copy the flash_nuke.uf2 file to the Pico
   - After the device reboots, follow the Install instructions below

2. **Install CircuitPython:**

   - Click [here](https://adafruit-circuit-python.s3.amazonaws.com/bin/raspberry_pi_pico_w/fr/adafruit-circuitpython-raspberry_pi_pico_w-fr-8.0.0.uf2) to download (Version 8.0.0).
   - Plug the device into a USB port while holding the boot button. It will show up as a removable media device named RPI-RP2.
   - Copy the downloaded (".uf2") file to the root of the Pico (RPI-RP2). The device will reboot and after a second or so, it will reconnect as CIRCUITPY.

3. **Install Pico Wifi Duck Files on the Pico:**
   - Download the release file from [here](https://github.com/Master629/PicoW-Ducky-Server/releases).
   - Unzip it.
   - While plugging in your Pico, copy and paste the files that you unzip onto the "CIRCUITPY" drive. (just copy all files in the zip file to the "CIRCUITPY" drive and replace any files if your computer asks you)
  


### Usage

1. Connect your Raspberry Pi Pico W to the target system using a good-quality USB cable.

2. Connect to the WiFi network created by the Pico; it's called **"PicoDuckySer"**, and its password is **"gethacked"**.

3. Open your browser and navigate to [192.168.4.1](http://192.168.4.1).

4. Write your script in the textarea and click on "RUN" .



# Digital-Level

**1. Wire OLED096 Display Module**
  - Connect the `VCC` to the `VSYS` pin on the pico
  - Connect the `GND` to the `GND` pin on the pico
  - Connect the `SCL` on the Display to physical pin `17` on the pico
  - Connect the `SDA` on the Display to physical pin `16` on the pico

**2. Wire the MPU6050 Module**
  - Connect the `VCC` pin on the module to the `VSYS` in on the pico
  - Connect the `GND` pin to a `GND` pin on the pico
  - Connect the `SCL` pin on the module to physical pin `20` on the pico
  - Connect the `SDA` pin on the module to physical pin `19` on the pico

**3. Download as install Micropython to your Raspberry Pi Pico**
  - Go to https://www.raspberrypi.com/documentation/microcontrollers/micropython.html and download micropython `.uf2`  file for your Pico
  - Plug in your Pico to your PC while holding the `Boot Sel` Button on the Pico. It should pop up as a storage device.
  - Drag and drop the `.uf2` file you downloaded into the pico.
  - Open Thonny and make sure you set the interperter to MicroPython (Raspberry Pi Pico). You may have to stop and restart the backend

**4. Download and upload to Raspberry Pi Pico via Thonny Python Editor**
  - Go to https://thonny.org/ and download the editor for you specific OS
  - Then Download and extract the files from this GitHub page to your PC
  - Open all the files in the main director and the `lib` folder in Thonny
  - Then got to the `View` tab and click `Files`
  - On the part where it says `This Computer`, Navigate to the file location you downloaded the repositories files to
  - Right click the files and `Upload to /`. Do that with `main.py` and the `lib` folder.

**5. Congradulations**
  - Once you have all the files copied over to the pico, unplug and replug the pico back into your PC and it should run automaticly
  - If you have any Questions or issues, be sure to create an issue and I will respond to the best of my ability. 

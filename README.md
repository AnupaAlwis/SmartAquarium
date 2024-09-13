# 🐠 Smart Aquarium

Welcome to the **Smart Aquarium** project! This custom-built aquarium uses advanced sensors and a machine learning model to automate various tasks and ensure the perfect environment for your fish. Whether you're looking to monitor water quality, automate feeding, or detect predators, this project has you covered!

## 🌟 Features

### 1. **Turbidity Level Sensor**
   - A custom-built sensor using a laser and LDR (Light Dependent Resistor) to measure the clarity of the water.
   - Alerts you when it's time to clean the aquarium based on historical turbidity data.

### 2. **Water Level Sensor & Auto Refill**
   - Monitors the water level to prevent it from dropping below a certain threshold.
   - Automatically activates a water pump to refill the aquarium when needed.

### 3. **Temperature Monitoring**
   - Uses a temperature sensor to monitor water conditions and ensure an optimal environment for your fish.
   - Displays real-time water temperature readings.

### 4. **Automatic Feeder**
   - Set custom feeding schedules to automatically feed your fish.
   - Customize the duration of feeding to ensure your fish get the right amount of food.

### 5. **Predator Detection**
   - A machine learning model running on a Raspberry Pi 4B detects potential predators in the vicinity.
   - Alerts you when a predator is present to ensure the safety of your fish.

## 🛠️ Hardware Components
- **Raspberry Pi 4B** for running the machine learning model.
- **Laser** and **LDR** for custom turbidity sensor.
- **Water level sensor** and **water pump** for automatic refilling.
- **Temperature sensor** for water condition monitoring.
- **Feeder motor** for automatic feeding.

## 📦 Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/smart-aquarium.git
   cd smart-aquarium

# Smart Footwear Landmine Detection System

## Overview

A wearable technology system designed to help soldiers detect landmines and receive real-time alerts, preventing accidental triggering in hazardous areas.

## Key Components

- **Footwear Sensors**:
  - **Metal Detector**: Detects metal objects using electromagnetic fields.
  - **Magnetic Resonance Sensor**: Identifies non-metallic or low-metal-content landmines.
- **GPS Module**:
  - Logs location data (latitude and longitude) when a landmine is detected.
- **Wristband Alert**:
  - Vibrates silently to alert the soldier without revealing their position.

## Operation

1. Sensors in the footwear continuously scan the ground.
2. Upon detecting a landmine, the GPS logs the location, and an alert is sent to the wristband.
3. The TTGO T-Call microcontroller processes the data and sends alerts to command centers via Bluetooth or satellite communication.

## Benefits

- Enhances safety by providing real-time detection of landmines.
- Supports soldiers with silent alerts and GPS tracking.
- Improves communication and reporting to command centers.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

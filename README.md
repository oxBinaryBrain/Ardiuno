# Arduino Home Automation Project

## Overview

Welcome to the Arduino Home Automation project! This project aims to create a home automation system using Arduino and Bluetooth technology. With this system, you can remotely control household appliances through a smartphone application, providing convenience and modernity to your home.

<img src="https://predictabledesigns.com/Arduino_Home_Automation_Tutorial_Fritzing_HiRes.jpg" alt="Arduino Home Automation" width="50%" height="50%">

## Features

- Remote control of appliances via Android smartphone.
- User-friendly smartphone application interface.
- Integration with Arduino board for efficient communication and control.
- Safe operation ensured through optoisolators and thyristors.

## Hardware Setup

To set up the hardware for this project, you'll need the following components:

- Arduino Board: Arduino Uno or Arduino Nano.
- Bluetooth Module: HC-05 or HC-06.
- Optoisolators: Ensure electrical isolation for safety.
- Thyristors (Triacs): Control AC loads like lights or fans.
- Loads: Connect appliances to the triacs for control.

<img src="https://example.com/hardware_setup.jpg" alt="Hardware Setup" width="50%" height="50%">

## Software Setup

The software setup involves:

1. Programming the Arduino board to receive Bluetooth commands and control loads accordingly.
2. Developing a GUI application for Android smartphones to send ON/OFF commands to Arduino via Bluetooth.

<img src="https://example.com/software_setup.jpg" alt="Software Setup" width="50%" height="50%">

## Getting Started

1. Connect the hardware components based on the provided circuit diagram.
2. Upload the Arduino code to the board (`arduino_code.ino`).
3. Pair the Bluetooth module with an Android smartphone.
4. Install and run the Android app (`home_automation_app.apk`) on the smartphone.
5. Use the app to send commands and remotely control connected loads.

## Safety Considerations

- Ensure proper insulation and wiring to prevent electrical hazards.
- Use components with appropriate ratings to handle load requirements safely.
- Implement safety features in the software to prevent unintended activations.

## Future Enhancements

Here are some ideas for future enhancements:

- Expand system capabilities with scheduling features.
- Integrate sensors for automation based on environmental conditions.
- Improve user interface and functionality of the Android app.

## Contributors

- [oxBinaryBrain](https://github.com/oxBinaryBrain) - Project lead and main contributor.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Project was displayed in the Innovative club of Presidency University at Bengaluru.
- Note: This was a mini project conducted in the 2nd semester of my engineering, so small working prototype was also created and tested.

## Feedback and Support

For any issues or feedback, please open an [issue](https://github.com/oxBinaryBrain/arduino-home-automation/issues) or contact the project maintainer.

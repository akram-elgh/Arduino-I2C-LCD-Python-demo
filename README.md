# Arduino I2C LCD Python Demo

This project demonstrates how to control an I2C LCD display connected to an Arduino using the PyFirmata library.

## Prerequisites

Before running this project, make sure you have the following:

- Arduino board
- I2C LCD display
- Python installed on your computer
- PyFirmata library installed (`pip install pyfirmata`)
- python 3.7 (PyFirmata works better with python 3.7)
- The following Arduino libraries installed:
  - LiquidCrystal_I2C
  - Wire
  - Firmata

## Connection Diagram

- Gnd pin of the LCD to Gnd of the Arduino
- Vcc pin of the LCD to 5V of the Arduino
- SDA pin of the LCD to A4 of the Arduino
- SCL pin of the LCD to A5 of the Arduino

## Installation

1. Clone this repository:

```bash
git clone https://github.com/akram-elgh/Arduino-I2C-LCD-Python-demo.git
```

2. Change into the project directory:

```bash
cd Arduino-I2C-LCD-Python-demo
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Connect your Arduino board to your computer.
2. Upload the `LCD_I2C_Firmata.ino` sketch to your Arduino using the Arduino IDE.
3. Run the Python script: `python main.py`

Feel free to modify the `main.py` script to suit your needs and add more commands if necessary.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

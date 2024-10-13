# BMI Calculator

This is a Body Mass Index (BMI) calculator built using the `customtkinter` library in Python. The application allows users to calculate their BMI based on height and weight, with the option to switch between metric and imperial units.

## Features

- **User-Friendly Interface**: Simple, intuitive design to input height and weight values.
- **Unit Switching**: Users can toggle between metric (kg, meters) and imperial (lbs, feet/inches) units.
- **Real-time Calculation**: The BMI result updates as the user changes the height and weight inputs.
- **Custom Title Bar Color**: Adjusts the title bar color (only works on Windows with specific setups).

## Installation

To run this project locally, follow these steps:

### Prerequisites

- Python 3.x
- `customtkinter` library

### Installing Dependencies

1. Clone this repository:

```bash
git clone https://github.com/yourusername/bmi-calculator.git
cd bmi-calculator
```

2. Install the required packages:

```bash
pip install customtkinter
```

## Usage

1. Navigate to the project directory.
2. Run the application:

```bash
python bmi.py
```

3. Enter your height and weight using the provided sliders and buttons. The BMI will be calculated in real-time and displayed in the center of the window.
4. Click on the "metric" label at the top right corner to toggle between metric and imperial units.

## Files

- `bmi.py`: Main script that contains the `App` class and all the UI components.
- `settings.py`: Contains configuration settings such as colors and font sizes used in the application.

## Customization

You can customize various aspects of the app, such as colors, fonts, and button styles, by modifying the constants in the `settings.py` file.

### Text Sizes:
- **Main Text Size**: Adjusts the size of the BMI result display.
- **Input Font Size**: Controls the size of the text for weight and height inputs.
- **Switch Font Size**: Changes the size of the text for the unit switcher.

### Colors:
- **GREEN**: Main theme color for buttons and progress bars.
- **DARK_GREEN**: Secondary color for labels.
- **WHITE**: Background color for text areas.
- **BLACK**: Color for input text.
- **LIGHT_GRAY**: Background color for sliders and buttons.
- **GRAY**: Hover color for buttons.

## Compatibility

- **Windows**: Full functionality, including custom title bar color.
- **macOS and Linux**: Custom title bar color may not work due to platform limitations, but the application runs normally otherwise.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
NOTE: EVERYTHING BELOW THIS LINE IS AI-GENERATED DOCUMENTATION AND I HAVEN'T VERIFIED THE ACCURACY OF IT YET.

# Graph Plotter

An interactive Python application for plotting mathematical functions and parametric equations, similar to a graphing calculator.

## Features

- **Two types of equations supported:**
  - y = f(x) functions (e.g., y = x², y = sin(x))
  - Parametric equations (e.g., x(t) = cos(t), y(t) = sin(t))

- **Interactive GUI:**
  - Input dialog for equation entry
  - Dynamic visibility based on equation type selection
  - Full-featured graphing window with proper axes and labels

- **Mathematical functions supported:**
  - Basic arithmetic: +, -, *, /, ** (power)
  - Trigonometric: sin, cos, tan
  - Exponential: exp, log
  - Other: sqrt, abs
  - Constants: pi, e

## Installation

1. Make sure you have Python 3.7+ installed
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Run the application:
```bash
python graph_plotter.py
```

2. **First Dialog (Equation Input):**
   - Select equation type from the dropdown:
     - "y = f(x)" for standard functions
     - "Parametric" for parametric equations
   - Enter your equation(s):
     - For y = f(x): Enter the right side of the equation (e.g., "x**2" for y = x²)
     - For Parametric: Enter both x(t) and y(t) equations
   - Click "OK" to plot or "Exit" to quit

3. **Second Window (Graph Display):**
   - Shows the plotted equation with labeled axes
   - Displays the equation title above the graph
   - Standard window controls (minimize, maximize, close)
   - Close the window to return to the input dialog

## Examples

### y = f(x) Functions:
- `x**2` (parabola)
- `sin(x)` (sine wave)
- `exp(x)` (exponential)
- `sqrt(x)` (square root)
- `x**3 - 2*x` (cubic function)

### Parametric Equations:
- Circle: `x(t) = cos(t)`, `y(t) = sin(t)`
- Ellipse: `x(t) = 2*cos(t)`, `y(t) = sin(t)`
- Spiral: `x(t) = t*cos(t)`, `y(t) = t*sin(t)`
- Lemniscate: `x(t) = cos(t)/(1 + sin(t)**2)`, `y(t) = sin(t)*cos(t)/(1 + sin(t)**2)`

## Requirements

- Python 3.7+
- tkinter (usually included with Python)
- matplotlib
- numpy
- sympy

## Notes

- The graph displays in the range [-10, 10] for both x and y axes
- For parametric equations, the parameter t ranges from 0 to 4π
- The application supports standard mathematical notation
- Error handling is included for invalid equations

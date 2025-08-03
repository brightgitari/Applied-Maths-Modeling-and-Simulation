# Applied Mathematics: Modeling and Simulation

This repository contains a collection of Python notebooks and projects focusing on mathematical modeling, numerical simulation, and control systems. Each project demonstrates practical applications of mathematical concepts in physics, engineering, and control theory.

## 📁 Project Overview

### 🚀 [Projectile Motion with Air Resistance](./Projectile-Motion-with-Air-Resistance/)


Mathematical modeling and simulation of projectile motion incorporating air resistance effects. This project explores:
- Classical projectile motion equations
- Air resistance modeling (linear and quadratic drag)
- Numerical integration methods
- Trajectory optimization
- Comparative analysis with and without air resistance

### ⚡ [RLC Circuits](./RLC-Circuits/)


Analysis and simulation of RLC (Resistor-Inductor-Capacitor) electrical circuits. Features include:
- Circuit differential equation modeling
- Transient response analysis
- Frequency domain analysis
- Resonance characteristics
- Step and sinusoidal response simulations

### 🔧 [Servo Motor with Speed Control](./Servo-Motor-with-speed-control/)


Implementation and analysis of servo motor control systems focusing on:
- PID controller design and tuning
- Motor dynamics modeling
- Speed control algorithms
- System stability analysis
- Performance optimization techniques

### 🌊 [Spring Mass Oscillator](./Spring-Mass-Oscillator/)


Comprehensive study of simple harmonic motion and oscillatory systems:
- Simple harmonic oscillator equations
- Phase space analysis
- Energy conservation principles
- Frequency and amplitude relationships
- Nonlinear oscillator extensions

### 🔄 [Spring Mass Damper System](./Spring-Mass-Damper-System/)


Advanced analysis of damped oscillatory systems including:
- Underdamped, critically damped, and overdamped responses
- Quality factor calculations
- Resonance phenomena
- Forced oscillation analysis
- Real-world damping effects

### 🌡️ [Thermostat Control](./Thermostat-Control/)


Temperature control system modeling and simulation covering:
- Heat transfer equations
- On-off control strategies
- PID temperature control
- System identification
- Energy efficiency analysis

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.7+ installed along with the following packages:

```bash
pip install numpy matplotlib scipy pandas jupyter sympy control-systems-library
```

### Installation

1. Clone this repository:
```bash
git clone <repository-url>
cd Applied-Maths-Modeling-and-Simulation
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## 📚 Usage

Each project folder contains:
- **Jupyter notebooks** (.ipynb files) with detailed explanations and code
- **Python scripts** for standalone execution
- **Data files** (if applicable) for analysis
- **Documentation** specific to each project

### Running the Notebooks

1. Navigate to the desired project folder
2. Open the main notebook file
3. Run cells sequentially to see the analysis and simulations
4. Modify parameters to explore different scenarios

### Example Usage

```python
# Example: Running a simple projectile motion simulation
import numpy as np
import matplotlib.pyplot as plt

# Load the projectile motion module
from projectile_motion import ProjectileWithDrag

# Create simulation instance
sim = ProjectileWithDrag(initial_velocity=50, angle=45, drag_coefficient=0.1)

# Run simulation
time, x, y = sim.simulate(time_max=10)

# Plot trajectory
plt.plot(x, y)
plt.xlabel('Horizontal Distance (m)')
plt.ylabel('Vertical Distance (m)')
plt.title('Projectile Motion with Air Resistance')
plt.show()
```

## 🔧 Technical Details

### Mathematical Methods Used
- **Numerical Integration:** Runge-Kutta methods, Euler's method
- **Linear Algebra:** Matrix operations, eigenvalue analysis
- **Control Theory:** PID controllers, transfer functions, stability analysis
- **Differential Equations:** ODE and PDE solving techniques
- **Signal Processing:** Fourier transforms, frequency analysis

### Key Libraries
- **NumPy:** Numerical computations and array operations
- **SciPy:** Scientific computing and optimization
- **Matplotlib:** Data visualization and plotting
- **SymPy:** Symbolic mathematics
- **Control:** Control systems analysis
- **Pandas:** Data manipulation and analysis

## 📊 Features

- **Interactive Visualizations:** Dynamic plots and animations
- **Parameter Studies:** Sensitivity analysis and optimization
- **Comparative Analysis:** Multiple solution methods comparison
- **Real-world Applications:** Practical engineering examples
- **Educational Content:** Step-by-step mathematical derivations

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Add new modeling projects
- Improve existing simulations
- Fix bugs or optimize code
- Enhance documentation
- Suggest new features

### Contribution Guidelines
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/NewModel`)
3. Commit your changes (`git commit -m 'Add new oscillator model'`)
4. Push to the branch (`git push origin feature/NewModel`)
5. Open a Pull Request


## 📞 Contact

For questions, suggestions, or collaboration opportunities, please open an issue or contact the repository maintainer.

## 🙏 Acknowledgments

-Dr Sam Macharia, PhD



**Note:** This repository is designed for educational and research purposes. 
The models and simulations provide good approximations for learning and analysis but may require additional considerations for real-world applications.

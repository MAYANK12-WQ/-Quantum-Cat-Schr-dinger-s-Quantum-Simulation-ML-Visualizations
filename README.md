# Quantum Cat: Schrödinger's Quantum Simulation & ML Visualizations

Welcome to **Quantum Cat**, a groundbreaking project that fuses quantum mechanics, machine learning, and hyper-futuristic data visualizations into one interactive, educational package. This project simulates Schrödinger's iconic thought experiment using synthetic quantum data, advanced ML models, and a suite of animated, interactive charts. It's designed to both educate and inspire, demonstrating the power of modern data science to elucidate even the most abstract scientific concepts.

## Project Overview

**Quantum Cat** is an end-to-end project that:

- **Simulates Quantum States:** Generates a synthetic dataset capturing the probabilistic evolution of Schrödinger's cat, tracking the superposition of "Alive," "Dead," and "Superposition" states over time.
- **Quantifies Uncertainty:** Uses Shannon entropy to measure the system's quantum uncertainty at each time step.
- **ML-Powered Insights:** Trains a machine learning classifier (Random Forest) to predict collapse outcomes (i.e., whether the cat is observed as "Alive" or "Dead") based on quantum probabilities.
- **Hyper-Futuristic Visualizations:** Features interactive, animated graphs including:
  - An animated **line graph** showing the evolution of entropy over time.
  - A **3D scatter plot** visualizing the quantum state in a three-dimensional probability space.
  - An animated **bar chart** and **pie chart** that depict the evolving distribution of collapse outcomes with cinematic transitions.
- **Interactive Dashboard (Planned):** Future enhancements will allow users to adjust simulation parameters (observation probability, noise, time horizon) in real time, linking multiple views into one immersive dashboard.

## Key Features

- **Educational & Visually Striking:** Explains quantum superposition, wavefunction collapse, and entropy through engaging, interactive visualizations.
- **Machine Learning Integration:** Implements a Random Forest classifier to predict collapse outcomes, providing data-driven insight into the quantum simulation.
- **Cinematic Animations:** Includes smooth, futuristic animations with play, pause, and reset controls for an immersive experience.
- **Modular and Extensible:** Designed as a foundation for further development into an interactive web app (using Plotly Dash or Streamlit) with advanced simulation controls.

## How It Works

1. **Data Simulation:**  
   A synthetic quantum dataset is generated that simulates the evolution of Schrödinger's cat. Key parameters such as observation probability, noise, and time horizon are used to create a dynamic environment where the cat's state is continuously updated.

2. **Entropy Calculation:**  
   Shannon entropy is computed at each time step, quantifying the uncertainty within the system and providing a numerical measure of the quantum state's disorder.

3. **Machine Learning Prediction:**  
   A Random Forest classifier is trained on observed collapse events to predict whether the cat will be "Alive" or "Dead" when observed, adding a predictive layer to the simulation.

4. **Visualization & Animation:**  
   Multiple animated visualizations (line graphs, 3D scatter plots, bar charts, pie charts) illustrate:
   - The evolution of quantum probabilities and entropy.
   - The dynamic distribution of collapse outcomes over time.
   - Interactive controls that allow users to play, pause, and reset the animations.

## Installation

```bash
# Clone the repository
git clone https://github.com/MAYANK12-WQ/DOGECOINPRO1.git

# Navigate to the project directory
cd DOGECOINPRO1

# Install required dependencies
pip install -r requirements.txt
```

## Usage

```python
# Run the main simulation and visualization script
python quantum_cat.py

# For interactive dashboard (when available)
python dashboard.py
```

## Requirements

- Python 3.7+
- NumPy
- Pandas
- Scikit-learn
- Plotly
- SciPy
- Matplotlib

## Project Structure

```
DOGECOINPRO1/
├── quantum_cat.py         # Main simulation script
├── visualization.py       # Visualization functions
├── ml_models.py           # Machine learning model implementations
├── utils/
│   ├── entropy.py         # Entropy calculation utilities
│   └── quantum_sim.py     # Quantum simulation functions
├── data/
│   └── simulated/         # Directory for simulated quantum data
├── notebooks/
│   ├── exploration.ipynb  # Exploratory data analysis
│   └── model_dev.ipynb    # Model development notebook
├── static/
│   └── images/            # Images for documentation
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation
```

## Future Enhancements

- Interactive web dashboard with Plotly Dash or Streamlit
- Parameter adjustment sliders for real-time simulation control
- Multiple linked views showing different aspects of the quantum system
- Enhanced ML models for more accurate collapse prediction
- Extended visualization library with additional chart types
- User accounts for saving custom simulation configurations

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by Erwin Schrödinger's famous thought experiment
- Built with modern data science and visualization libraries
- Dedicated to making complex quantum concepts accessible through interactive data visualization

---

*Note: This is an educational project and is not intended to provide actual quantum computing capabilities or real quantum simulations. The quantum behavior is simulated using classical computing techniques and probabilistic models.*

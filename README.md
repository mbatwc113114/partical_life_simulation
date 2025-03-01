# Particle Life Simulation

## Overview

Particle Life Simulation is a physics-based simulation where particles interact based on predefined rules, forming dynamic patterns and emergent behaviors. This project aims to model artificial life using simple interaction rules.

## Features

- **Customizable Interaction Rules**: Modify attraction/repulsion forces between particles.
- **Real-Time Visualization**: Watch particles form clusters, swarms, or chaotic movements.
- **Optimized Performance**: Efficient algorithms for large-scale simulations.
- **Multi-Threaded Support**: Utilize multiple CPU cores for faster processing.
- **Export Simulation Data**: Save and analyze particle interactions.

## Installation

### Requirements

- Python 3.8+
- Required libraries:
  ```bash
  pip install numpy matplotlib pygame
  ```

### Running the Simulation

Clone the repository and execute the main script:

```bash
git clone https://github.com/yourusername/particle-life-simulation.git
cd particle-life-simulation
python main.py
```

## Usage

- **Modify Parameters**: Adjust forces, number of particles, and colors in `config.json`.
- **Pause/Resume**: Press `Space` key.
- **Reset Simulation**: Press `R` key.

## Configuration

Modify `config.json` to tweak settings:

```json
{
  "num_particles": 500,
  "interaction_matrix": [
    [0.5, -1.0],
    [1.0, 0.5]
  ],
  "time_step": 0.01
}
```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit changes (`git commit -m "Added new feature"`).
4. Push to GitHub (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgments

- Inspired by **Lenia** and **Boid flocking simulations**.
- Special thanks to open-source contributors!

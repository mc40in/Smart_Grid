#README
# Smart_Grid
This is examples of program with was created for Smart_Grid_Technology

author Maksym SOROKIN

## Smart Grid Energy Flow Analysis Using Python

This repository contains a Python-based program for analyzing energy flows in a Smart Grid system. It is designed for educational purposes, particularly for energy engineering students, to demonstrate the integration of renewable energy sources and optimization techniques within modern energy grids.

---

## Features

1. **Energy Load Input**:
   - Users can manually input energy load profiles for a 24-hour period (divided into 3-hour intervals).
   - Includes the ability to account for solar generation variability based on seasonal conditions.

2. **Visualization**:
   - Generates bar charts to compare energy consumption and solar generation, helping users visualize energy distribution over time.

3. **Cost Analysis**:
   - Calculates the cost of energy from the grid and solar panels based on user-defined tariffs.
   - Provides economic efficiency metrics to aid in decision-making.

4. **Deficit and Surplus Recommendations**:
   - Identifies energy deficits or surpluses.
   - Recommends increasing solar panel capacity in case of deficits or suggests optimal battery capacity for energy storage in case of surpluses.

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mc40in/smart-grid-energy-analysis.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd smart-grid-energy-analysis
   ```

3. **Install dependencies**:
   - Ensure Python 3.7+ is installed on your system.
   - Install required packages:
     ```bash
     pip install -r requirements.txt
     ```

4. **Run the program**:
   - Open the code in [Google Colab](https://colab.research.google.com/) or a local Jupyter Notebook.

---

## How to Use

1. **Data Input (Block 1)**:
   - Enter the energy load profile for the 24-hour period.
   - Specify the capacity of the solar installation.
   - Select the season to simulate solar energy generation.

2. **Execution (Block 2)**:
   - Generates a bar chart comparing energy load and solar generation.

3. **Cost Analysis (Block 3)**:
   - Input the cost of grid electricity and solar energy.
   - Calculates total energy costs and determines economic efficiency.

4. **Optimization Suggestions (Block 4)**:
   - Analyzes energy deficits or surpluses.
   - Provides actionable recommendations to balance energy needs effectively.

---

## Example Output

- **Bar Chart**: Visual representation of energy load vs. solar generation.
- **Cost Analysis**:
  - Total cost of energy from the grid and solar panels.
  - Economic efficiency metrics.
- **Recommendations**:
  - Suggested additional solar capacity for deficits.
  - Optimal battery capacity for surpluses.

---

## Applications

This program can be used to:
- Teach concepts of energy flow and optimization in Smart Grid systems.
- Simulate the impact of renewable energy integration on grid performance.
- Evaluate the economic feasibility of renewable energy investments.

---

## Contribution

Contributions are welcome! Feel free to submit issues or pull requests to enhance the program’s functionality or fix bugs.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For questions or feedback, please reach out to [mc40in@gmail.com].



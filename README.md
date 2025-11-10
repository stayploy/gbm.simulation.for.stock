%%writefile README.md

## Simulating Stock Prices with Geometric Brownian Motion (GBM)
This project simulates how stock prices change over time using a mathematical model called GBM.

---

## What This Code Does
- Simulates **GBM stock price paths**  
- Plots each stock path separately  
- Creates an **animation** showing how all prices move together over time  

---

## Default Parameters
| Variable  | Meaning  | Default Value |
|-----------|----------|----------------|
| N  | Number of time steps | 500 |
| S0 | Initial stock price | 100 |
| mu | Expected growth rate (drift) | 0.00005 |
| sigma | Volatility | 0.01 |
| dt | Time step size | 1 |
| n_paths | Number of simulated paths | 3 |

---

## Results
- Line plots showing each stock price path  
- Animation displaying all paths together  
Each color represents a different simulated scenario.

---

## How to Run

### Option 1 — Run on Google Colab
1. Open **Google Colab**  
2. Upload the `.ipynb` file  
3. Click **Run all** to see the graphs and animation  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

### Option 2 — Run on Your Computer
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
pip install numpy matplotlib
python gbm_simulation.py

---

## Note
This project was created for educational purposes with partial assistance from AI tools.

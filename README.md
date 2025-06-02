
## 📌 Project Overview

Choosing a temporary place to live often involves considering various factors such as cost, safety, distance, and comfort. This project applies the **Weighted Product model**, a widely used technique in MCDM, to rank housing options by calculating a preference value for each alternative.

The implementation is done using a Python-based Jupyter Notebook.

## 🔧 Features

- Input dataset of housing alternatives and criteria
- Criteria weighting and normalization
- Calculation of preference scores using the Weighted Product formula
- Ranking of alternatives from most to least recommended
- Final decision visualization and output


## 📊 Methodology

The Weighted Product (WP) model is a decision support tool where each alternative is evaluated by multiplying its attributes, each raised to a power equivalent to the assigned weight:

```
S_i = (x_i1)^w1 * (x_i2)^w2 * ... * (x_in)^wn
```

Or in more formal notation:

**Sᵢ = ∏ (xᵢⱼ)^wⱼ for j = 1 to n**

Where:
- `x_ij` = value of criterion `j` for alternative `i`
- `w_j` = weight of criterion `j`
- `S_i` = score of alternative `i`

## 🧪 Requirements

Make sure to have the following Python packages installed:

```bash
pip install pandas numpy matplotlib
```

Or use an environment like **Google Colab** or **Jupyter Notebook**.

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/raisenbk/mcdm-wp.git
   cd mcdm-wp
   ```

2. Open the notebook:
   - Use Jupyter Notebook or upload it to Google Colab.
   - Run all the cells to see the decision-making process and results.

## 📈 Sample Output

- Criteria weighting and normalization
- Weighted scores for each housing option
- Final ranking recommendation


📉 L1 & L2 Regularization in Machine Learning

````markdown
This project explains and implements **L1 (Lasso)** and **L2 (Ridge)** regularization techniques in linear regression to combat overfitting and improve model generalization. It uses `scikit-learn` and synthetic or real-world datasets.

---

## 📦 Libraries Used

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

---

## 📊 Techniques Explained

| Type   | Algorithm | Effect                                   |
|--------|-----------|------------------------------------------|
| L1     | Lasso     | Shrinks coefficients; can eliminate some |
| L2     | Ridge     | Shrinks coefficients smoothly to zero    |

---
````
## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/l1-l2-regularization-demo.git
   cd l1-l2-regularization-demo
   ```
2. Launch the notebook:

   ```bash
   jupyter notebook L1-L2-Regularization.ipynb
   ```

3. (Optional) Run a Python script version:

   ```bash
   python regularization_comparison.py
   ```

---

## 📈 Output & Visualizations

* Coefficient magnitude comparison
* Loss vs Regularization strength plot
* Mean squared error for different values of alpha/λ

---

## ✅ Results

* L1 can shrink irrelevant features to **exactly zero**
* L2 shrinks all coefficients **toward zero** but not exactly
* Both methods **reduce overfitting** and improve generalization

---

## 📂 File Structure

```
l1-l2-regularization-demo/
│
├── L1-L2-Regularization.ipynb     # Main notebook
├── README.md                      # Project documentation
├── requirements.txt               # Python dependencies
```

---

## 📜 License

[MIT License](LICENSE)

---



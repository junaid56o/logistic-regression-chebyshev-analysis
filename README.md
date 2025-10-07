# Logistic Regression and Bayes with Chebyshev

This project demonstrates how **Logistic Regression** and **Naive Bayes Classifier** can be compared using the **Iris dataset**, with an additional statistical analysis using **Chebyshev’s Inequality** to detect outliers and understand prediction uncertainty.

---

##Overview

The notebook explores:

* Training a **Logistic Regression** model for binary classification
* Comparing it with a **Naive Bayes Classifier**
* Applying **Chebyshev’s Inequality** to identify unusual prediction probabilities
* Visualizing probability bounds and interpreting outliers

This project connects traditional statistical concepts like **Chebyshev’s theorem** and **Bayesian inference** with modern **machine learning classification** techniques.

---

##Concepts Covered

| Concept                    | Description                                                         |
| -------------------------- | ------------------------------------------------------------------- |
| **Logistic Regression**    | Models the probability of class membership using a sigmoid function |
| **Naive Bayes Classifier** | Uses Bayes’ theorem assuming feature independence                   |
| **Chebyshev’s Inequality** | Provides distribution-free bounds to detect outlier probabilities   |
| **Evaluation Metrics**     | Accuracy, Precision, Recall, F1-score                               |

---

## Technologies Used

* **Python 3.x**
* **NumPy**
* **Pandas**
* **Scikit-learn**
* **Matplotlib**

---

##  How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/logistic-regression-and-bayes-with-chebyshev.git
   cd logistic-regression-and-bayes-with-chebyshev
   ```

2. Install dependencies:

   ```bash
   pip install numpy pandas scikit-learn matplotlib
   ```

3. Open the notebook:

   ```bash
   jupyter notebook logistic_chebyshev_analysis.ipynb
   ```

4. Run all cells to reproduce results and visualization.

---

##  Output Highlights

* Chebyshev bounds calculated for predicted probabilities
* Outlier samples identified beyond 2 standard deviations
* Accuracy comparison between Logistic Regression and Naive Bayes

---

## Future Enhancements

* Apply on real-world datasets (e.g., spam detection, medical data)
* Extend to multi-class classification
* Add confidence interval visualization using Chebyshev’s bounds

---

**Author:** Jun Aid
📍 *Educational Machine Learning Project – integrating statistics and ML*

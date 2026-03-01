# Early Sepsis Risk Modeling

A comparative study of tree-based models and neural networks for early sepsis prediction using structured ICU data.

---

## Motivation

Sepsis is a life-threatening condition associated with high mortality. Early detection may significantly improve clinical outcomes.

This project investigates whether structured physiological data contains sufficient predictive signal to detect sepsis within a short time horizon.

---

## Research Question

Do neural networks outperform tree-based models for early sepsis prediction using tabular ICU data?

---

## Prediction Task

Predict whether a patient will develop sepsis within the next 6 hours based on the previous 6 hours of physiological data.

To prevent data leakage, only past information is used for feature construction.

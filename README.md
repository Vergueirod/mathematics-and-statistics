## 📘 Personal Mathematics and Statistics Language Guide

---

# Create a virtual environment (name it 'venv' or something descriptive)
python3 -m venv venv

# Activate the virtual environment
source venv/bin/activate

# Install
pip install ipykernel notebook

# Add Your Virtual Environment to Jupyter as a Kernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)"

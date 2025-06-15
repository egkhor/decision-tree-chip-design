# Decision Tree for Chip Design Defect Prediction

This open-source project showcases the **Decision Tree algorithm** for machine learning, applied to predict defects in semiconductor chip designs. Using a Decision Tree classifier, we analyze synthetic chip data (e.g., transistor count, defect rate) to achieve ~80% accuracy in defect detection, streamlining design workflows.

## Features
- **Decision Tree Model**: Splits data using Gini index for interpretable defect predictions.
- **Synthetic Dataset**: 1,000 samples for prototyping.
- **Scalable**: Lightweight for local or cloud execution.

## Project Structure
```
decision-tree-chip-design/
├── README.md
├── requirements.txt
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
├── src/
│   └── decision_tree_defect_prediction.py
└── data/
    ├── chip_defect_data.csv
    └── decision_tree_metrics.txt
```

## Getting Started

### Prerequisites
- Python 3.8+
- Dependencies: `pip install -r requirements.txt`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/egkhor/decision-tree-chip-design.git
   cd decision-tree-chip-design
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python src/decision_tree_defect_prediction.py
   ```

### Output
- Generates `chip_defect_data.csv` and `decision_tree_metrics.txt` with model accuracy (~80%).

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.markdown) to add datasets, models, or visualizations.

## License
MIT License. See [LICENSE](LICENSE).

## Contact
Open an Issue or join Discussions on [GitHub](https://github.com/egkhor/decision-tree-chip-design).

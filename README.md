# Data Analysis Project

## Problem Statement

#  Looking at Data to Correct Cognitive Biases

<b>data/inspiration -></b> [Medium article: "How to Overcome Biases with Data"](https://medium.com/p/692c8c35f4a5)

In this notebook, we will investigate a simple problem: is the smoking rate higher in the metro area of my hometown (Peoria, Il) or in Boston. The purpose is to see if I can combat my cognitive biases with data and explore the data to determine why I made a incorrect conclusion.

# Relevant Data:

* Boston number of adults = 472582: https://www.bumc.bu.edu/inspir/files/HTML/Boston%20Population%20and%20Demographics.htm
* Peoria number of adults = 83925: https://www.infoplease.com/us/illinois/demographic-statistics-61
* Boston smoking rate = 0.164 (from first source in image)
* Peoria smoking rate = 0.199(from first source in image)

z-score for 95% CI: http://www.stat.yale.edu/Courses/1997-98/101/confint.htm

Difference between two proportions formula: https://onlinecourses.science.psu.edu/stat100/node/57/

![](images/rates_smoking.PNG)


## Dependencies

This project requires the following Python libraries:

- NumPy
- Matplotlib

You can install these dependencies using pip:

```
pip install numpy matplotlib
```

## Project Structure

```
project/
│
├── data/
│   └── dataset.csv
│
├── src/
│   ├── data_loader.py
│   ├── data_processor.py
│   └── visualizer.py
│
├── notebooks/
│   └── analysis.ipynb
│
├── results/
│   └── figures/
│
├── README.md
└── requirements.txt
```

## Usage

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/data-analysis-project.git
   cd data-analysis-project
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the analysis:
   ```
   python src/main.py
   ```

   Alternatively, you can open and run the Jupyter notebook:
   ```
   jupyter notebook notebooks/analysis.ipynb
   ```

## Results

The analysis results, including generated figures, will be saved in the `results/` directory.

## Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request with your proposed changes.

## License

This project is license free .

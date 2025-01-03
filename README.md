# Logistic Regression Project

This project implements a logistic regression model to predict whether an internet user will click on an advertisement based on various features. The dataset used for this analysis is a simulated advertising dataset that includes user demographics and behavior metrics.

## Project Structure

The project is organized as follows:

```
logistic-regression-project
├── data
│   └── advertising.csv          # Dataset used for logistic regression analysis
├── notebooks
│   └── logistic_regression_project.ipynb  # Jupyter Notebook containing the project code
├── .gitignore                   # Files and directories to be ignored by Git
├── requirements.txt             # List of required Python packages
└── README.md                    # Overview and documentation of the project
```

## Dataset

The dataset `advertising.csv` contains the following features:

- **Daily Time Spent on Site**: Consumer time on site in minutes
- **Age**: Customer age in years
- **Area Income**: Average income of the geographical area of the consumer
- **Daily Internet Usage**: Average minutes a day the consumer is on the internet
- **Ad Topic Line**: Headline of the advertisement
- **City**: City of the consumer
- **Male**: Gender of the consumer (1 if male, 0 if female)
- **Country**: Country of the consumer
- **Timestamp**: Time at which the consumer clicked on the ad or closed the window
- **Clicked on Ad**: 0 or 1 indicating whether the ad was clicked

## Setup Instructions

1. **Clone the Repository**: 

2. **Install Requirements**: 
   It is recommended to create a virtual environment before installing the requirements. You can use `venv` or `conda` for this purpose.
   ```
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**: 
   Launch Jupyter Notebook and open the `logistic_regression_project.ipynb` file.
   ```
   jupyter notebook notebooks/logistic_regression_project.ipynb
   ```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
# NYC Taxi Trip Data Analysis using PySpark

This repository contains a project that implements an ETL (Extract, Transform, Load) process using PySpark for analyzing NYC Taxi trip data. The goal is to demonstrate how to use PySpark to handle large datasets, perform data cleaning, and extract meaningful insights from the data.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The NYC Taxi Trip Data Analysis project aims to provide a comprehensive analysis of taxi trips in New York City. By leveraging the power of PySpark, we can efficiently process and analyze large volumes of data, gaining insights into patterns and trends in taxi usage.

## Dataset

The dataset used in this project is the NYC Taxi Trip dataset, which includes detailed information about taxi trips in New York City. The data is publicly available.

## Project Structure

The project structure is as follows:

```
NYC-Taxi-Trip-Data-Analysis-using-PySpark/
├── data/
│   └── [yellow_tripdata_2024-12.parquet]
├── NYC_Taxi_Trip_Data_Analysis_using_PySpark.ipynb
├── README.md
└── requirements.txt
```

- `data/`: Directory to store the dataset files.
- `notebooks/`: Directory containing Jupyter notebooks with data analysis and visualizations.
- `README.md`: Shows step by step guide.
- `requirements.txt`: dependencies for the project.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Mamiololo01/NYC-Taxi-Trip-Data-Analysis-using-PySpark.git
   cd NYC-Taxi-Trip-Data-Analysis-using-PySpark
   ```

2. Create a virtual environment and activate it:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the analysis, follow the instructions provided in the Jupyter notebooks located in the `.ipynb/` directory. It contains step-by-step explanations and code to perform data processing and analysis.


## Contributing

Contributions are welcome! If you have any improvements, bug fixes, or new features to add, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, feel free to open an issue or contact the repository owner:

- GitHub: [Mamiololo01](https://github.com/Mamiololo01)


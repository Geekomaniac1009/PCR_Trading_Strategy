#PCR Trading Strategy
This project implements a Pivot Point Cumulative Ratio (PCR) trading strategy using options data. The strategy aims to identify potential buy and sell signals based on the relationship between the PCR value and the price movement.

Overview
The above project was implemented as a part of the Inter-Hostel Technical Competition, Kriti 2024 at IIT Guwahati. The PCR trading strategy involves analyzing the PCR value, which is the ratio of put options open interest to call options open interest, along with pivot points calculated from the price data. When certain conditions are met, buy or sell signals are generated.

Installation
To use this project, follow these steps:

Clone the repository:

bash
Copy code
git clone <repository_url>
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
To run the PCR trading strategy:

Ensure that the required CSV files containing options and index data are available in the data directory.

Execute the main script:

bash
Copy code
python QuantKriti.py
The script will generate buy and sell signals based on the PCR strategy and visualize them along with the price data.

File Structure
css
Copy code
#PCR-Trading-Strategy
│
├── data/
│   ├── index_data.csv
│   ├── put_option_data.csv
│   └── call_option_data.csv
├── QuantKriti.py
├── PS.pdf
└── README.md

Dependencies
Pandas (version 2.1.1)
NumPy (version 1.26.0)
Matplotlib (version 3.8.0)
...
Contributing
Contributions to the project are welcome! Here's how you can contribute:

Report issues or bugs
Submit pull requests for enhancements or fixes

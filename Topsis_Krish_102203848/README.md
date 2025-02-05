# Topsis-Krish-102203848

`Topsis-Krish-102203848` is a Python package for implementing the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS), a multi-criteria decision-making (MCDM) method. This package simplifies the process of ranking and selecting alternatives based on multiple criteria with varying weights and impacts.

## Installation

Install the package from PyPI using `pip`:

```bash
pip install Topsis-Krish-102203848


Usage
Command-Line Interface (CLI)
Prepare a CSV file with the following format:

The first column contains the names of the alternatives (e.g., "M1", "M2").
The subsequent columns contain numeric values for each criterion.
Ensure the file has a header row.
Example:

FundName	P1	  P2	P3	  P4	P5
  M1	   0.67	  0.45	6.5	  42.6	12.56
  M2	    0.6	  0.36	3.6	  53.3	14.47

E.g. Program-

import os
from topsis.topsis import main

# def run_topsis():
#     # Define input file
#     input_file = "input.csv"
    
#     # Define weights and impacts
#     weights = "1,1,1,1,1"  # Example: Equal weights for all criteria
#     impacts = "+,+,-,+,-"  # Example: Benefits (+) and costs (-) criteria
    
#     # Define output file
#     output_file = "output.csv"
    
#     # Generate the input CSV file
#     data = """Fund Name,P1,P2,P3,P4,P5
# M1,0.67,0.45,6.5,42.6,12.56
# M2,0.6,0.36,3.6,53.3,14.47
# M3,0.82,0.67,3.8,63.1,17.1
# M4,0.6,0.36,3.5,69.2,18.42
# M5,0.76,0.58,4.8,43,12.29
# M6,0.69,0.48,6.6,48.7,14.12
# M7,0.79,0.62,4.8,59.2,16.35
# M8,0.84,0.71,6.5,34.5,10.64"""
    
#     with open(input_file, "w") as file:
#         file.write(data)
    
#     print(f"Input file '{input_file}' has been created.")
    
#     # Run TOPSIS
#     try:
#         main(input_file, weights, impacts, output_file)
#         print(f"Output file '{output_file}' has been generated.")
#     except Exception as e:
#         print(f"Error during TOPSIS execution: {e}")
    
#  
#     if os.path.exists(output_file):
#         with open(output_file, "r") as file:
#             print("\nGenerated Output File Content:")
#             print(file.read())

# if __name__ == "__main__":
#     run_topsis()


License
This package is licensed under the MIT License.

Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.


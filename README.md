# Basket-CDS-Pricing

Pricing a basket k-th to default CDS based on their joint probability of default. The joint probability of default is simulated using a joint Gaussian and Student-t distribution and the securities are priced using these simulations. The term structure of hazard rates is bootstrapped from the market price of the CDS over different tenures. The covariance matrix for calibrating the joint distributions is found from the equity prices of individual references. 

## Getting Started 

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites 

This project requires a Python2.7 environment with the following dependencies: 
1) Pandas 
2) Numpy
3) SciPy
4) Matplotlib
5) Sklearn
 

### Installation

The code for the strategy has been implemented in the .ipynb file included in the repository and can be replicated with the consent of the contributors.

## Testing 

The IPython notebook containts the code and the descriptive comments which debrief about the functionality of each function used. To begin implementation, run the code in the final block of the notebook. The parameters for computing the price need to be entered while running the pricing model. The data for bootstrapping hazard rates is found in the 'cds_data' folder. 

## Contributors 

Akhil Sethia


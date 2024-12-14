# The repository contains an overview of models for short interest rates, specifically the Hull-White and Vasicek models.

# Files structure
- **`/Hull-White_model/`**: Contains:
  - **`EM_simulation.ipynb`** includes how path simulation behaves in the Hull-White model depending on changes in the model parameters
  - **`caps_and_floors.ipynb`** contains the implementation of pricing a simple Hull-White model using analytical formulas related to the value of a caplet and a floorlet. The file also includes the appropriate formulas for option pricing.
- **`/Vasicek_model/`**: Contains:
  - **`estimating_parameters.ipynb`** contains the implementation of estimating the parameters of the Vasicek model using the maximum likelihood estimation method.

# Neural Network Charity Analysis

## Overview
Use deep learning to predict which charities are too high risk to donate to.

## Results: 
### Data Preprocessing
- Target : Is_Successful
- Features : Application_Type, Affiliation, Classification, Use_Case, Organization, Status, Income_Amt, Special_Considerations, Ask_Amt
- Non Features : EIN and Name
### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- I Used 5 layers
- 100, 80, 60, 40, and 20 neurons respectfully
- relu activation method worked the best,

Were you able to achieve the target model performance?
- I was not able to achieve the desired performance

What steps did you take to try and increase model performance?
- Raised the bin sizes for the cuts
- Added extra layers
- Increased the number of neurons
- Changed the activation function.

## Summary: 
I was not able to achieve the desired performance. I changed the sizes of the bins, increased layers, increased neurons, and was still falling short of the desired goal. I think that using RandomOverSampling would achieve better results.

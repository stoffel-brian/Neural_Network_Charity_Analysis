# Neural_Network_Charity_Analysis


### 1. Overview of the analysis: Explain the purpose of this analysis.
Here are the columns of data
- EIN	
- NAME	
- APPLICATION_TYPE	
- AFFILIATION	
- CLASSIFICATION	
- USE_CASE	
- ORGANIZATION	
- STATUS	
- INCOME_AMT	
- SPECIAL_CONSIDERATIONS	
- ASK_AMT	IS_SUCCESSFUL

Here is the H5 file - [AlphabetSoupCharity_Optimzation (.h5)](https://github.com/stoffel-brian/Neural_Network_Charity_Analysis/blob/711560d14024ba7b2679915c2d03e17e438a91a6/AlphabetSoupCharity_Optimzation.h5)

### 2. Results: Using bulleted lists and images to support your answers, address the following questions.

 [Results Un-Optimized (.png)](https://github.com/stoffel-brian/Neural_Network_Charity_Analysis/blob/958190e8f5302b72c55a46bcb20242211f904727/Results%20Un-Optimized.PNG)

 
 [Results Optimized (.png)](https://github.com/stoffel-brian/Neural_Network_Charity_Analysis/blob/958190e8f5302b72c55a46bcb20242211f904727/Results%20Optimized.PNG)

- Data Preprocessing
    - What variable(s) are considered the target(s) for your model?
      - "Is_Sucessful" & "Status"
    - What variable(s) are considered to be the features for your model?
      - "Is_Sucessful" & "Status"
    - What variable(s) are neither targets nor features, and should be removed from the input data?
      - "Is_Sucessful" & "Status"
 - Compiling, Training, and Evaluating the Model
    - How many neurons, layers, and activation functions did you select for your neural network model, and why?
      - The un-optimized has 2 layers and the optimized has 7 layers 
    - Were you able to achieve the target model performance?
      - Yep, my targets are low but still under the class module requirement of 75%. See screenshots. 
    - What steps did you take to try and increase model performance?
      - Added in more layers to increase the optimization. 
### 3. Summary
Not really a useful time measurement; further analysis is requirement for this module to be truly optimized. 

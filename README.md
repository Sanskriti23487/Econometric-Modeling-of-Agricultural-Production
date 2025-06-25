# Econometric Modeling of Groundnut Production in India

This project applies econometric techniques to analyze and model groundnut crop production across various districts in India for the year 2017. Using Python for data manipulation, statistical modeling, and visualization, it explores the relationship between agricultural output and multiple inputs, including environmental factors.

## Project Objectives

- **Data Integration & Preparation**  
  Merged and cleaned district-level datasets including groundnut production, input usage (area, irrigation, fertilizers), monthly rainfall, and soil quality (salinity/alkalinity index). Created season-specific rainfall summaries relevant to groundnut growth.

- **Cobb-Douglas Production Function**  
  Estimated a log-linear Cobb-Douglas model to measure the elasticity of output with respect to inputs (e.g., total area, irrigated area, fertilizers), while controlling for environmental factors like rainfall and soil degradation. Addressed zero-value inputs and distinguished farmer-controlled inputs from environmental controls.

- **Quadratic Production Function**  
  Modeled diminishing marginal returns by including squared input terms. Tested the hypothesis of diminishing productivity for specific inputs.

- **Hypothesis Testing & Diagnostics**  
  Conducted statistical testing for:
  - Returns to scale (for farmer-controlled inputs)
  - Diminishing marginal productivity
  - Input complementarity (e.g., interaction between irrigation and fertilizer)
  - Multicollinearity and detection of influential observations

- **Model Visualization & Evaluation**  
  Visualized residuals (e.g., residuals vs. crop area, histogram plots) to evaluate model assumptions. Compared Cobb-Douglas and Quadratic models in terms of fit and interpretability.

- **Regional Analysis**  
  Explored regional variations in estimated production functions to enhance insight granularity.

## Technologies Used

- Python – Primary programming language
- Pandas – Data manipulation and cleaning
- NumPy – Numerical operations
- Statsmodels – Econometric estimation and statistical testing
- Matplotlib – Visualization and plotting

# Data Science Project: Retirement Investment Optimizer

## Goal
The objective of this project is to assist users, particularly the elderly, in maximizing their rate of return in the stock market to facilitate a comfortable retirement. The algorithm is designed to be applicable to individuals of all ages based on their specified maximum risk tolerance.

## How to Use
Users can input their maximum acceptable risk and desired rate of return on an interactive HTML page for personalized investment recommendations.

## Implementation Steps

1. **Get Historical Stock Market Data:**
   - Utilize historical data from index funds and bonds.
   - Crypto assets are not included currently due to limited applicability.

2. **Calculate Average Annual Rate of Return and Risk:**
   - Employ simple math for calculating the annual rate of return.
   - Use standard deviation to assess risk for each financial instrument.

3. **Implement Machine Learning Model for Future Predictions:**
   - Utilize a machine learning model to predict future data.
   - Train the model using older data and test it with more recent data to forecast annual rates of return and risk for each financial instrument.

4. **Apply Markowitz Model:**
   - Use a mathematical algorithm (Markowitz Model) to determine the maximum rate of return for a given risk level.

5. **Generate Ideal Portfolio:**
   - Develop additional code to generate an ideal portfolio of index funds and bonds tailored to an individual's specified risk level.

## Implementation Status
The core functionality of the project is complete.

**Enhance User Experience (Optional):**
   - Create a visually appealing HTML page with graphs and visuals for a user-friendly interface.

## Why Machine Learning
The inclusion of a machine learning model enhances the predictive capabilities of the algorithm, allowing it to adapt to changing market conditions and generate more accurate forecasts.

**Note:** This project is a continuous work in progress, and future enhancements may include additional features and asset classes for a more comprehensive investment strategy.

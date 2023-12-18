# Triton Forex Trading Robot

## Product Description
Triton is a professional forex trading robot designed for major currency pairs. It implements three strategies - swing, gap, and support and resistance - to analyze price data and determine optimal parameters for profitable trades. The robot includes a software filter that analyzes daily and monthly charts over the last 12 periods to filter trades and improve trading accuracy.

Triton allows traders to customize their trading experience by providing options to adjust settings according to their preferences. It is compatible with various execution order types offered by different brokers and ensures compatibility with brokers that do not average multiple positions into one position.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates how Triton can work as described in the product. To find the official developer of Triton, please refer to MQL5.

## Terms of Reference
1. Develop code for Triton, a forex trading robot designed for major currency pairs.
2. Implement three strategies - swing, gap, and support and resistance - to analyze price data and determine optimal parameters for profitable trades.
3. Include a software filter that analyzes daily and monthly charts over the last 12 periods to filter trades.
4. The Swing strategy should be applicable on TF H1 or M30, with the option for more frequent trades but higher risk on M15 or M5.
5. The Gap strategy is recommended for use on M30 or H1 timeframes.
6. The Support and Resistance strategy is best suited for M30, H1, or H4 timeframes.
7. Provide default settings for EURUSD, GBPUSD, and USDJPY on the M30 timeframe.
8. Ensure compatibility with brokers that do not average multiple positions into one position.
9. Account for various execution order types offered by different brokers.
10. Customize trading experience by providing options for traders to adjust settings.
11. Limit the terms of reference to code requirements and necessary feature development.
12. Specify only the essential trading functions in the technical specification.
13. The size of the terms of reference should not exceed 1500-2000 characters.

## Usage
1. Include the necessary libraries and resources.
2. Define the constants for currency pairs and timeframes.
3. Create an instance of the Triton class by providing the desired currency pair symbol and timeframe.
4. Implement the Start() method in the Triton class to define the main entry point for the trading robot.
5. Implement the desired trading strategies (swing, gap, support and resistance) based on the provided logic.
6. Apply the software filter by implementing the FilterTrades() method in the Triton class.
7. Execute trades based on the selected strategies and filtered data by implementing the ExecuteTrades() method in the Triton class.
8. Initialize the Triton trading robot with the default settings by calling the OnInit() method.
9. Start trading by calling the OnStart() method.

## Sample Code Explanation
- The code starts by including the necessary libraries and resources.
- Constants are defined for the currency pairs and timeframes.
- The Triton class is defined, which contains variables and objects required for trading.
- The constructor of the Triton class initializes the symbol and timeframe.
- The Start() method is the main entry point for the trading robot, where the logic for each strategy is implemented based on the specified timeframe.
- The FilterTrades() method applies a software filter to analyze price data over the last 12 periods and returns true if the trades pass the filter.
- The ExecuteTrades() method executes trades based on the selected strategies and filtered data.
- The OnInit() method initializes the Triton trading robot with the default settings for each currency pair and timeframe.
- The OnStart() method calls the OnInit() method to start trading.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy's review of Triton](https://forexroboteasy.com/forex-robot-review/review-of-triton-a-professional-forex-traders-analysis-of-this-software/).

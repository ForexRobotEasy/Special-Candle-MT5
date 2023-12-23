# Special Candle MT5 Indicator

This is the ReadMe file for the Special Candle MT5 Indicator developed by Forex Robot Easy Team. This indicator utilizes the Ichimoku strategy to analyze and identify strong crosses on specified currency pairs for different timeframes. It also detects and highlights powerful Tenkunsen and Kijunsen crosses.

## Developer Information
- Developer: Forex Robot Easy Team
- Developer's Site: [forexroboteasy.com](https://forexroboteasy.com)

## Installation
To use the Special Candle MT5 Indicator, follow the steps below:

1. Import the necessary libraries:
```cpp
#include <Trade\Trade.mqh>
#include <Indicators\Ichimoku.mqh>
```

2. Define the constants:
```cpp
#define TIMEFRAME_30M 30
#define TIMEFRAME_H1 60
```

3. Define the currency pairs for analysis:
```cpp
string[] currencyPairs30M = {'CADJPY', 'CHFJPY', 'USDJPY', 'NZDJPY', 'AUDJPY', 'EURUSD', 'EURGBP'};
string[] currencyPairsH1 = {'GBPUSD', 'GBPNZD', 'GBPAUD', 'USDCAD', 'USDCHF', 'USDJPY', 'EURAUD'};
```
Note: You can modify the currency pairs to suit your needs.

4. Initialize the objects:
```cpp
CTrade trade;
CIchimoku ichimoku;
```

5. Implement the `analyzeStrongCrosses()` function to analyze and identify strong crosses on the specified currency pairs for different timeframes.

6. Implement the `detectPowerfulCrosses()` function to detect and highlight powerful Tenkunsen and Kijunsen crosses.

7. Implement the `calculateIndicators()` function to calculate and display relevant indicators and signals based on the Ichimoku strategy.

8. In the `OnStart()` function, call the necessary functions in the desired order to perform the required analysis and actions.

## Usage
To use the Special Candle MT5 Indicator:

1. Compile and run the code in your MetaTrader 5 terminal.

2. The indicator will analyze the specified currency pairs for strong crosses and perform the necessary actions.

3. It will also detect and highlight powerful crosses.

4. Finally, it will calculate and display relevant indicators and signals based on the Ichimoku strategy.

## Product Description
The Special Candle MT5 Indicator is a powerful tool developed by the Forex Robot Easy Team. It utilizes the Ichimoku strategy to analyze and identify strong crosses on specified currency pairs for different timeframes. With its advanced algorithm, it can detect and highlight powerful Tenkunsen and Kijunsen crosses, providing traders with valuable insights into market trends and potential trading opportunities.

This indicator is designed to assist traders in making informed trading decisions by calculating and displaying relevant indicators and signals based on the Ichimoku strategy. It provides valuable information such as Tenkan Sen, Kijun Sen, Senkou Span A, Senkou Span B, and Chikou Span. By analyzing these indicators, traders can gain a deeper understanding of market dynamics and improve their trading strategies.

Please note that ForexRobotEasy is not the official developer of this product. We are showcasing the sample code that can work as described in this product. To find the official developer and access detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/special-candle-mt5-review-top-forex-indicator-with-ichimoku-strategy/). For any technical support or inquiries, please contact the official developer via their website or using MQL5.

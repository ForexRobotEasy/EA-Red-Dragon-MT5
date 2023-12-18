# EA Red Dragon MT5

## Developer: Forex Robot Easy Team
## Website: forexroboteasy.com

---

This is a sample code for the EA Red Dragon MT5 expert advisor developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We are only providing this sample code that can work as described in the product.

For detailed reviews and trading results of the official EA Red Dragon MT5 product, please visit [this link](https://forexroboteasy.com/forex-robot-review/review-ea-red-dragon-mt5-real-results-and-download-options/).

---

## Code Description

### Libraries Used:
- Trade.mqh
- PositionInfo.mqh
- OrderInfo.mqh
- Indicators.mqh

### Constants:
- TAKE_PROFIT: 100
- STOP_LOSS: 50

### Variables:
- cciValue: stores the current Commodity Channel Index (CCI) value
- isBuySignal: indicates if a buy signal is present
- isSellSignal: indicates if a sell signal is present

### Modules and Indicators:
- trade: initializes the trade module
- cci: initializes the CCI indicator

### Expert Advisor Function:
The expert advisor is executed on every tick of the market. The following steps are performed:

1. Calculate the CCI value using the iCCI function.
2. Check if the CCI value is above 100 to determine a buy signal.
3. Check if the CCI value is below -100 to determine a sell signal.
4. If a buy signal is present and there is no open position for the current symbol, open a buy trade using the Buy function from the trade module.
5. If a sell signal is present and there is no open position for the current symbol, open a sell trade using the Sell function from the trade module.
6. If there is an open position for the current symbol, check the position type and close the position if the CCI value changes its sign.

---

Please note that this code is a simplified version of the EA Red Dragon MT5 expert advisor. The actual product may have additional features and complexity. To find the official developer of the EA Red Dragon MT5 product, please use MQL5.

For detailed reviews and trading results of the official EA Red Dragon MT5 product, please visit [this link](https://forexroboteasy.com/forex-robot-review/review-ea-red-dragon-mt5-real-results-and-download-options/).

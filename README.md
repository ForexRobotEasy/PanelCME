# PanelCME ReadMe

## Description
PanelCME is an automated forex software developed by the Forex Robot Easy Team. It provides various features such as setting stop loss and take profit levels, converting to breakeven, trailing stop loss, and setting take profit as a limit order.

For detailed reviews and trading results of this product, visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/panelcme-review-boost-your-trading-with-this-automated-forex-software/). Please note that ForexRobotEasy is not the official developer of this product. We only provide the sample code that can work as described in this product. To find the official developer of this product, use MQL5.

## Libraries and Variables
The necessary libraries are included, and the following variables are defined:
- `trade`: an instance of the `CTrade` class for trading operations.
- `stopLoss`: the stop loss level in points.
- `takeProfit`: the take profit level in points.
- `trailingStop`: the trailing stop level in points.
- `breakevenPips`: the number of pips to convert to breakeven.
- `ticket`: the ticket number of the market order.

## Functions
### SetStopLossTakeProfit
This function sets the stop loss and take profit levels for the open position. It takes the stop loss and take profit levels in pips as parameters and converts them to points before modifying the position.

### ConvertToBreakeven
This function checks if the current price is above the breakeven level and modifies the position to breakeven if true. It calculates the breakeven level based on the open price and the number of pips to convert to breakeven.

### TrailingStopLoss
This function checks if the current price is above the trailing stop level and modifies the position to the trailing stop level if true. It calculates the trailing stop level based on the current price and the trailing stop value.

### SetTakeProfitAsLimit
This function sets the take profit level as a limit order. It modifies the position by setting the take profit level and setting the stop loss level to 0.

### OnInit
This is the main start function that is called when the EA is initialized. It initializes the variables, places a market order, sets the stop loss and take profit levels, converts to breakeven, applies trailing stop loss, and sets take profit as a limit order.

### OnTick
This is the main execution function that is called on each tick. No additional actions are required in this example.

For more information on how to use this code, refer to the official documentation or contact the official developer of the product.

## Disclaimer
Please note that ForexRobotEasy is not the official developer of PanelCME. We only provide the sample code that can work as described in this product. To find the official developer of this product, use MQL5. For detailed reviews and trading results, visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/panelcme-review-boost-your-trading-with-this-automated-forex-software/).

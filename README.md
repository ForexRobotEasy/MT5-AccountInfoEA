# AccountInfoEA

This code is an Expert Advisor (EA) for MetaTrader 5 (MT5) platform. It is designed to provide information about the positions in the trading account. The EA retrieves details of each position, such as ticket number, symbol, type, volume, open price, stop loss, take profit, and profit. It then prints these details on the chart.

## Initialization and Deinitialization

The `OnInit()` function is called when the EA is initialized. In this function, the trade levels on the chart are hidden using the `ChartSetInteger()` function. The `OnDeinit()` function is called when the EA is deinitialized. Here, the trade levels on the chart are shown again.

## Tick Function

The `OnTick()` function is called on each tick of the price. It retrieves the total number of positions in the trading account using the `PositionsTotal()` function. Then, it loops through each position using a for loop. Inside the loop, it retrieves various details of the position using appropriate functions, such as `PositionGetTicket()`, `PositionGetString()`, `PositionGetInteger()`, `PositionGetDouble()`, etc.

Finally, it prints the position details on the chart using the `Print()` function.

## Product Description

**AccountInfoEA** is an Expert Advisor (EA) for MetaTrader 5 (MT5) platform. It provides detailed information about the positions in your trading account. With this EA, you can easily monitor the ticket number, symbol, type, volume, open price, stop loss, take profit, and profit of each position.

This EA is designed to help traders optimize their forex trading view by providing real-time position details. By having access to such information, traders can make better-informed decisions and improve their trading strategies.

Please note that **Forex Robot Easy** is not the official developer of this product. We only provide sample code that demonstrates how this product works. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [here](https://forexroboteasy.com/forex-robot-review/mt5-accountinfoea-review-optimize-forex-trading-view/).

# Head and Shoulder MT4 ReadMe File

## Developer's Site: [forexroboteasy.com](https://forexroboteasy.com)
## Development by: Forex Robot Easy Team

### Initialization
The `OnInit()` function sets up the scanner button.

### Start scanning
The `OnButtonClick()` function is triggered when the scanner button is clicked. If the button is clicked, the `ScanMarket()` function is called.

### Scan the Forex market
The `ScanMarket()` function loops through all symbols and timeframes to perform market analysis. It retrieves the symbol name and the timeframe name, then calls the `PerformMarketAnalysis()` function to perform the analysis. The result is printed.

### Perform market analysis for a symbol
The `PerformMarketAnalysis()` function performs market analysis for a given symbol and timeframe. This function should be implemented separately to perform the analysis and calculate the analysis result.

### Program termination
The `OnDeinit()` function is called when the program is terminated. It can be used to clean up any resources used by the program.

Please note that ForexRobotEasy is not the official developer of this product. We provide sample code that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/head-and-shoulder-mt4-review-instant-forex-scan-solution/).

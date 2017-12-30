# Excel-Trading-Trainer
An Excel-based tool to train financial trading with real stock and financial data using price action.

Only a few features are implemented, but good enough to be useful. If I upgrade the tool I will upload the file with new features such as automatic buy/sell/limit/sl/tp management.

The charting capabilities of Excel are unexplored to me and however, they seem quite limited if compared with other frameworks like matplotlib, d3.js, anystock etc. Anyway, Excel is a reliable program, extremely easy for programming and for creating working basic tools very fast.

## Instructions:

#### DATA SHEET
The data sheet must contain at least the following columns in this order:
- Price date
- Open Price
- High Price
- Low Price
- Close Price

The other two are not used currently.

#### ITERATOR SHEET
Once the data sheet is populated, click on the "reset charts" button on the bottom-left and the charts and displays will be automatically updated and adjusted with the data.

Insert an integer (ie 1) in cell BD36 (its fixed named range is "iterator_positions") and then click on the "move bars" button to move one step forward.

The tool supports both positive and negative values to move bars forward and backwards respectively. However, at this stage it is recommended not to go backwards beyond the initial default bar generated on clicking "reset charts" button.

## Sample Data:
Over 400Mb of stock data from New York Stock Exchange companies can be downloaded already prepared for Excel here:
https://drive.google.com/drive/folders/18DkJeCqpibKdR8ezwk9hGjdHYSGwovWH?usp=sharing

Before pasting the values on the data sheet:
- The decimal separator is "comma". If the destination system is configured with another decimal place separator, the values on the original csv file shall be replaced first.
- The field separator is tabulation, not comma. It fits perfectly on Excel sheets.


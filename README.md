Ticks-To-Second-Bars
=====================
Converts tick data semicolon delimited - TIME;PRICE;VOLUME - format (from Netfonds-Tick-Capture) to second bars - TIME,OPEN,HIGH,LOW,CLOSE,VWAP-PRICE,VOLUME

#How-To
* Replace the line ```DATA_DIR =  # TODO - insert data directory path here``` to point to the path of the tick data directory.
* Then run ticks_to_bars.py and pass the list of ticker symbols as arguments
* The new files will be added to the "bars" folder in your DATA_DIR path.

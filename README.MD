
## README
- V1.0版本 芯片使用AS5040，插针接口

- V2.0版本 芯片使用AS5047，1.25贴片 6Pin ,MOSI与MISO网络名错误
	- 实际线序为：GND MO MI CK CS 5V
	
- V2.9版本 芯片使用AS5047，1.25贴片 6Pin,工字型，未正式打板，线序与2.0不同

- V3.0版本 芯片使用AS5047，1.25贴片 6Pin ,修正MOSI与MISO网络名错误问题
	- 为与2.0版本线序兼容，线序仍为 GND MO MI CK CS 5V
	- 今后使用时，只要是2.0或者3.0版本，不管板子上的丝印怎么写，都按GND MO MI CK CS 5V接即可
	- 当然，如果要确认一下的话，2.0版本MO于MI的丝印时反的，3.0版本是对的
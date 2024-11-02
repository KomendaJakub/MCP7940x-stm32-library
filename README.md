# MCP7940x-stm32-library
An stm32 library to access the MCP7940x peripheral using HAL.

https://www.microchip.com/en-us/product/mcp7940n

This project is a rewrite of [Zanduino/MCP7940](https://github.com/Zanduino/MCP7940) 
using the stm32 HAL. 


The library limits itself to basic timekeeping using blocking functions, e.g. alarms are not implemented. 
It can be used as a template to easily extend to INT or DMA. 

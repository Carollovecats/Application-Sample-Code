Application-Sample-Code
-----------------------
- [DC_Fan_Speed_Control](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216133919)
- [Master_Slave_communication](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216134016)
- [PWM_trigger_ADC_and_PWM_Brake_function](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216134105)
- [Measure_Internal_Temperature_Sensor](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216133639)
- [SoftwareUART](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216133807)
- [HID_Keyboard_Mouse_w_MultiMediakeys](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216134204)
- [Selective_Suspend](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216134257)
- [Dual_IO](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216134343)
- [Vender_Command](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216134432)


| Main Function | Product  | Code | Description |
| :-----------: | :------: | :--: | :---------  |
|      ADC      |   M051   | [Measure_Internal_Temperature_Sensor](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216133639) | Transform band-gap voltage through ADC7, and then use band-gap voltage to calculate ADC reference voltage. After that, use ADC7 to transform the value detected by a temperature sensor to calculate the voltage of temperature sensor. |
|   Composite   |  M051 | [SoftwareUART](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216133807) | Use GPIO to create software UART if the number of hardware UART is insufficient. This example is to create UART protocol from GPIO through time interrupt. |
|   Composite   |  Mini51 | [DC_Fan_Speed_Control](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216133919) | The fan speed is captured by Timer0 Capture, and then adjusted through PWM2. |
|   I2C   |  Mini51 | [Master_Slave_communication](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216134016) | A master transfers data to a slave. That is, the master transfers the slave address to call the slave, and then sends the data address to the slave and keeps transmitting 10 data to the slave. The slave saves data in sequence to the data address. After the transmission, the master will start to read data; the master sends the slave address and data address to the slave, and gets 10 data back in sequence from the slave. At last, the master compares the received data with the original data for verification. | 
|   PWM   |  Mini51 | [PWM_trigger_ADC_and_PWM_Brake_function](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216134105) | PWM output is configured to trigger ADC, and can be stopped by brake function. |
|   SPI   |  NUC123 | [Dual_IO](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216134343) | Speed up SPI Read/Write function by using Dual I/O. | 
|   USBD  |  NUC122 | [HID_Keyboard_Mouse_w_MultiMediakeys](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216134204) | Support HID keyboard and mouse devices simultaneously. Add source code to control Multi-Media Keys and LEDs. |
|   USBD  |  NUC122 | [Selective_Suspend](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216134257) | Support USB Selective Suspend function:          1. Need to declare USB 2.0 device                        *  2. Add 0xee to String descriptor                       *  3. Support vender command                           *  4. Support Windows 8 or later             | C0120151216134432) | Vender command sends data through the control transfer. There are three steps: setup, data and status. | 


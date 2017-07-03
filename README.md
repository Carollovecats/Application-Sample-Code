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
|   Composite   |  Mini51 | [DC_Fan_Speed_Control](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216133919) | The fan speed is captured by Timer0 Capture, and then adjusted through PWM2. |
|   Composite   |  M051 | [SoftwareUART](http://www.nuvoton.com/opencms/resource-download.jsp?tp_GUID=EC0120151216133807) | Use GPIO to create software UART if the number of hardware UART is insufficient. This example is to create UART protocol from GPIO through time interrupt. |

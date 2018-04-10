# DistGC
## Versions
### V1: Small MPPT Charge Contoller
* Solar input only (100V max.)
* Battery connection (max. 48V)
* Regulated output (max. 48V)

### V2: Medium MPPT Charge Controller 
* something in between

### V3: Big MPPT DistGrid Controller 
* Max 1kV Solar input
* 100V Wind turbine input
* Controller will provide 300V DC
* Battery connection
* System of Controller and Converter 

## Notes
### V1:
* MPPT Control: STM32F373CBTx 
* Monitoring: STM32L072CZTx
* FDMT800100DCTR-ND (MOSFET N-CH 100V 24A)
* MPQ18021A (100V, 2.5A, High-Frequency Half-Bridge Gate Driver)
* ACS720 (High Accuracy, Dual Fault, Galvanically Isolated Current Sensor in SOIC16)
* LT8705A (80V VIN and VOUT Synchronous 4-Switch Buck- Boost DC/DC Controller) (Optional)
* ZVN4424GTR (MOSFET N-CH 240V 500MA SOT223)

### V2:
* MPPT Control: STM32F303K8 (UART1 intercomm)
* Monitoring/Controlling: STM32F(4/7)xx (I²C, Ethernet, CAN, SPI)

### V3:
## Wiki
-> [Wiki](https://git.dk0tu.de/dl7jc/DistGC/wikis/home)

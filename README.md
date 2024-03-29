# Board Communication Examples (Arduino Only for now )

This repository contains code examples for different communication protocols between different arduino development boards 
## SPI Communication

The SPI (Serial Peripheral Interface) protocol is commonly used for communication between microcontrollers and peripherals. The SPI folder contains the following examples:
#### Result: 
![image](https://github.com/Oreoluwa-IVT/Board_Communication/assets/75027292/e9ad6ade-d56e-4e75-a466-b28e12abb317)



- [SPI_Master.c](./SPI_Master.c): Arduino code for the master Arduino that sends a message via SPI.
- [SPI_Slave.c](./SPI_Slave.c): Arduino code for the slave Arduino that receives a message via SPI.

## I2C Communication

The I2C (Inter-Integrated Circuit) protocol is widely used for communication between integrated circuits. The I2C folder contains the following examples:

- [I2C_Master.c](./I2C_Master.c): Arduino code for the master Arduino that sends data via I2C.
- [I2C_Slave.c](./I2C_Slave.c): Arduino code for the slave Arduino that receives data via I2C.

## UART Communication

UART (Universal Asynchronous Receiver-Transmitter) is a serial communication protocol commonly used for point-to-point communication. The UART folder contains the following examples:

- [UART_Transmitter.c](./UART_Transmitter.c): Arduino code for the transmitter Arduino that sends data via UART.
- [UART_Receiver.c](./UART_Receiver.c): Arduino code for the receiver Arduino that receives data via UART.

## Contributing

Contributions to this repository are welcome! If you have any improvements or additional examples for communication between Arduinos, feel free to submit a pull request.

## License

This repository is licensed under the [Apache License 2.0](LICENSE).

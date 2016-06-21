# SimpleModbus
Simple Modbus Arduino Libraries

Most of files here come from: https://drive.google.com/folderview?id=0B0B286tJkafVYnBhNGo4N3poQ2c&usp=drive_web&tid=0B0B286tJkafVSENVcU1RQVBfSzg so credits go to Juan Bester
I have added SimpleModbusSlaveSoftwareSerial which use Software Serial port. 

All pull requests are welcome!

Here is release notes from Juan Bester
#SimpleModbusMaster
16/02/2014 - SMMv11
Cleaned up comments and changed the BUFFER size to 64 which matches the new buffer value in the hardwareSerial core library in version 1.05 onwards.

16/06/2014 - SMMv12
Minor changes in the keywords.txt file.

15/09/2014 - SMMv2rev2
I have decided to rewrite some of the library to create easier abstraction and to add functions 5 and 6. I have also created a manual of sorts with lots of information to help getting started. I have also shared a link on my drive to all my communication information. The ones in question are modbus and RS485. It makes for a very good (and long) read. The library for the DUE differs only in the removal of the byteFornat parameter in modbus_configure().

#SimpleModbusSlave
16/02/2014 - SMSv9
- Cleaned up comments and changed the BUFFER size to 64 which matches the new buffer value in the hardwareSerial core library in version 1.05 onwards.

- Added: void modbus_update_comms(long baud, unsigned char byteFormat, unsigned char _slaveID);
   This allows for easy update of the port variables and the slave id dynamically in your code.

10/11/2014 - SMSV10
Added function 6
The library for the DUE differs only in the removal of the byteFornat parameter in modbus_configure().


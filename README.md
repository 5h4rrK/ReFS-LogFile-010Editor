# ReFS-LogFile-010Editor

Here is a template for the Resilient File System **LogFile** designed for use with the widely used Hex editor known as `010Editor`.

This template provides you with the capability to interpret the following elements:

- ReFS Entry Header
- ReFS Log Header
- The **redo** opcode
- RedoArrayEntry and TransactionRecord

## How to use it ?

You have two options: Either utilize it directly on the disk image or extract the logfile `MLog` from the disk image.
  
- Open the logfile or disk image.

- Navigate to `Templates` -> `New Template` & paste the script `LogFile.bt`

- Execute the script.

![alt text](assests/image.png)


## License 

[License](LICENSE)
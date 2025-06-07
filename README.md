# fins_simulator_omron
Simulate OMRON PLC with FINS protocol

go mod init main
go mod tidy
go build

execute main.exe
operation with DM Area
set 001 10
get 001
----- for real---- 2.3 (Little Endian), use https://www.h-schmidt.net/FloatConverter/IEEE754.html
set 001 13107
set 002 16403
----- for real 3.0 (little Endian)
set 001 0
set 002 16448

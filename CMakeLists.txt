cmake_minimum_required(VERSION 3.27)
project(Panoxyda C)

set(CMAKE_C_STANDARD 23)

add_executable(Panoxyda main.c
        Engine/Headers/IoT/Asus.h
        Engine/IoT/Asus.c
        Engine/Headers/IoT/Gpon.h
        Engine/Headers/IoT/Hnap.h
        Engine/Headers/IoT/Jaws.h
        Engine/Headers/Net/Protocol.h
        Engine/Headers/IoT/Rand.h
        Engine/Headers/IoT/Resolv.h
        Engine/Headers/IoT/Netlink.h
        Engine/Headers/Net/Linksys.h
        Engine/Headers/Analys/Scanner.h
        Engine/Headers/IoT/Tr.h
        Engine/Headers/Util.h
        Engine/Headers/Data/Table.h
        Engine/Headers/IoT/Dpon.h
        Engine/Headers/Attack/Attack.h
        Engine/Headers/Checksum.h
        Engine/Headers/IoT/Comtrend.h
        Engine/Headers/IoT/Realtek.h
        Engine/Headers/ThinkPHP.h
        Engine/Headers/Enc.h
        Engine/Headers/Analys/DSLScanner.h
        Engine/Headers/Analys/IoTScanner.h
        Engine/Attack/Attack.c
        Engine/Attack/Service.cpp
        Engine/IoT/Comtrend.c
        Engine/IoT/Dpon.c
        Engine/IoT/Gpon.c
        Engine/IoT/Hnap.cpp
        Engine/IoT/Jaws.c
        Engine/IoT/Netlink.c
        Engine/IoT/Rand.c
        Engine/IoT/Realtek.c
        Engine/IoT/Resolv.c
        Engine/IoT/Tr.c
        Engine/Checksum.c
        Engine/Enc.c
        Engine/ThinkPHP.c
        Engine/Util.c
        Engine/Headers/Attack/Service.h
        Engine/Analys/DSLScanner.c
        Engine/Analys/IoTScanner.c
        Engine/Analys/Scanner.c
        Engine/Data/Table.c
        Engine/Net/Linksys.c
        Engine/Net/Protocol.c)

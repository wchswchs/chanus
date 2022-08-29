# Chanus
Chanus is next generation operating system，it's so fast and safe because it implement the separation of data flow and control flow. 

Chanus make data flow running in user space, so data doesn't need to go through the kernel, avoding to copy between kernel and user space.

Chanus make conrol flow running in kernel space, so it can prevent processes/threads accessing system resource.

## Features
- Network transmission more faster than Linux
- Processes/Threads context switch more faster than Linux
- Custom driver using any programing language，such as C, C++, Java, Rust, Go etc.
- Custom processes/threads scheduling strategy using any programing language

## Architecture
![os 001](https://user-images.githubusercontent.com/1735799/187169571-35c2945d-f24a-4bae-a478-6d9a00feedef.jpeg)

DPDK：https://www.dpdk.org/

PTDK：Development Kit of memory management of processes and threads control block

## Process Context Switch
![context_switch 001](https://user-images.githubusercontent.com/1735799/187160804-5eba51ca-6246-4a22-929e-0113161e8a37.jpeg)

## Thread Context Switch
![thread_context_switch 001](https://user-images.githubusercontent.com/1735799/187161031-75244848-f53a-454b-b182-83a0eef5bfcd.jpeg)

## Network Transmission
![network 001](https://user-images.githubusercontent.com/1735799/187156112-ca58b03f-3c58-445d-9d84-9e0782dc72b2.jpeg)











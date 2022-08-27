# chanus
Chanus is next generation operating system，it's so fast because it implement the separation of data flow and control flow. 

Chanus make data flow running in user space, so data doesn't need to go through the kernel, avoding to copy between kernel and user space.

Chanus make conrol flow running in kernel space, so it can prevent process/thread accessing system resource.

## Architecture
![os 001](https://user-images.githubusercontent.com/1735799/186941620-7484453a-65a6-44dc-af30-121f347dc380.jpeg)

## Process Context Switch
![context_switch 001](https://user-images.githubusercontent.com/1735799/187027566-7ec68f3c-7813-4d70-bc6e-8a751574911d.jpeg)




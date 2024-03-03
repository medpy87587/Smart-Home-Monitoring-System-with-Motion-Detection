# Smart-Home-Monitoring-System-with-Motion-Detection

The "Smart Home Monitoring System with Motion Detection" project utilizes the FreeRTOS (Real-Time Operating System) to manage concurrent tasks effectively. FreeRTOS is a popular open-source operating system designed for microcontrollers, providing features such as multitasking, task prioritization, and synchronization mechanisms like semaphores.

In this project, FreeRTOS enables the system to execute multiple tasks concurrently, ensuring that sensor readings, LCD updates, and motion detection functionalities operate independently without blocking each other. Tasks are scheduled based on their priority levels, allowing critical tasks like sensor reading to be executed promptly while ensuring the responsiveness of the system.

FreeRTOS also facilitates the creation of semaphores, such as the lcdMutex, which helps protect shared resources like the LCD display from simultaneous access by multiple tasks, preventing data corruption and ensuring reliable operation.
![Screenshot 2024-03-03 231218](https://github.com/medpy87587/Smart-Home-Monitoring-System-with-Motion-Detection/assets/112163057/6f7780f5-90d5-40e1-88bd-c6e6ddbd0156)


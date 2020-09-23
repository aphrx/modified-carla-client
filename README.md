# Modified CARLA Client

### Introduction
This is a modified CARLA client python file which sends CAN messages on the vcan0 virtual bus on linux (Must be set up prior to execution) using the Honda DBC file from comma.ai's OpenDBC repository.

### Execute
To execute, simply run the CARLA server on Linux and run ```./vcan.sh``` to open vcan0. Then simply run ```python3 modified_client.py``` to open the client.

### Future Plans
- Lane Detection
- Vehicle Detection
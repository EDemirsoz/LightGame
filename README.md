
# Light Game

The LightGame project is a simple game implemented using ARM assembly language and the STM32 NUCLEO Development board. It uses the light sensor, LED matrix, and LED button on the board.

##  Disclaimer
The project available in this repository is an academic project and is not intended to be publicly available since it is related to academic coursework, and there is a potential for academic misconduct if it is used improperly. Therefore, only a video recording of the project is available for viewing.

If you would like to request access to code base and additional materials related to this project, please contact me directly and make your request. Please note that access to any additional materials will be granted solely at my discretion and only for legitimate educational or research purposes.

By accessing the video recording of this project, you acknowledge and agree that you will not use it for any unauthorized or unethical purposes, and that any misuse of the project may result in serious consequences, including academic penalties and disciplinary action.
## Features
The LightGame project has the following features:

- Retrieves the current light sensor value and displays a bar graph on the LED matrix indicating the current light level.
- Bar graph displays range from 0 to 32, even though the light sensor value range is 0 to 4096.
- The game has a delay feature that limits the delay value between 1 and 10 and should be able to operate with a default value.
- When the LED button is pressed, the game switches to play mode.
- The winning target value is set to the current bar graph value when the button is pressed.
- The bar graph starts going up and down on its own (not according to the light).
- When the LED button is pressed again, the game decides if the player has won or lost based on whether the current bar graph value matches the target value recorded when the button was first pushed.
## Tech Stack
The LightGame project uses the following technologies and tools:

- ARM assembly language
- C programming language
- STM32 NUCLEO Development board
- Light sensor
- LED matrix
- LED button
- Linux


## Requirements
To run the LightGame project, you will need the following:

- STM32 NUCLEO Development board
- Light sensor connected to the board
- LED matrix connected to the board
- LED button connected to the board
- Linux environment
- ARM assembly language toolchain

## Run Locally
To run the LightGame project locally, follow these steps:

	1. Connect the light sensor, LED matrix, and LED button to your STM32 NUCLEO Development board according to the circuit diagram.
	2. Set up the ARM assembly language toolchain on your Linux environment.
	3. Clone the LightGame project code from the repository.
	4. Compile the code using the ARM assembly language toolchain.
	5. Upload the compiled code to your STM32 NUCLEO Development board.
	6. Set the delay value by sending the command "_xxLightGame delay" to your board, where "xx" is your initials and "delay" is the desired delay value.
	7. Observe the bar graph on the LED matrix indicating the current light level.
	8. Press the LED button to switch to play mode.
	9. Wait for the bar graph to stop moving up and down.
	10. Press the LED button again to see if you have won or lost based on whether the current bar graph value matches the target value recorded when the button was first pushed.


## Demo
### Easy Mode



https://user-images.githubusercontent.com/64825806/226465246-7aa13655-d4af-44e9-bc4c-96bec35bd6d4.mp4



### Hard Mode

https://user-images.githubusercontent.com/64825806/226464685-9cd7d7f4-187c-474d-be2b-ce635d77f08d.mp4


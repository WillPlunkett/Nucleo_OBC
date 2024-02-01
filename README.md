# Nucleo_OBC
This directory houses the code that runs the temporary OBC for the UVA HEDGE cubesat project. The board this is running on is a NUCLEO-H745ZI-Q. The GPS is an Adafruit ultimate GPS v3 board, and the wiring diagram can be found in the file ________.

To install and run: Download the STM32CubeIDE from https://www.st.com/en/development-tools/stm32cubeide.html Clone the repository directly into the STM32CubeIDE directory that is created upon install (By default this should be under the user directory you install the software with). (You might also need to create a workspace directory in the STM32CubeIDE directory to house this repo. Mine is called workspace_1.14.1). Plug in the NUCLEO board using a USB-MicroUSB connector to provide power and IO to the board. To load the code onto the board, first build the code base (Either press control+b or go to project -> build all) Now click the run button, and the code will be uploaded to the board (green button with white arrow).

To add code: (DO LATER)

ToDo: Upload wiring diagrams / screenshots. Have build configurations that run different programs on the board. Integrate other hardware with the board. Outline the program flow of the board software.

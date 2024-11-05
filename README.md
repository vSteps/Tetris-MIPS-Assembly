# Tetris-MIPS-Assembly 🎮

## Introduction 📚

This game was developed by me during the 2nd semester of Systems Analysis and Development course. I was nominated to develop the Tetris game in Assembly-mips by Professor Eduardo Bráulio Wanderley Netto(all my thanks to him). It's the classic tetris, you need to complete a line using the set of pieces you are given, each line grants you 100 points.

![tetris](https://github.com/user-attachments/assets/65e891c8-8df2-40cd-bae9-67923ad529ba)


## Table of Contents 📑

- [Requirements](#requirements)
- [Installation](#installation)
- [Execution](#execution)
- [Commands](#commands)

## Requirements ✨

- Git
- Java Runtime Environment (JRE)

## Installation ⚡

Steps to set up the environment:

1. **Verify if you have the above requirements. If not, look for a tutorial to meet the requirements.**

2. **Clone the Repository:**

    ```bash
    git clone https://github.com/vSteps/Tetris-MIPS-Assembly.git
    ```

## Execution 🚀

Steps to run the project:

1. **Run the Mars4_5.jar file:**

    - Open the terminal and run the following command:

        ```bash
        java -jar Mars4_5.jar
        ```

2. **Opening the cloned project in MARS:**

    - Click on the icon to select the folder:
      
        ![Select Folder](https://github.com/user-attachments/assets/a1118076-1725-47e5-8d97-d6e4810f225c)

    - Select the folder where the project is located and open the `TetrisFinal.asm` file:

        ![Open File](https://github.com/user-attachments/assets/09848dbe-c4e6-4723-91ba-2aced89eb981)

3. **Opening the display tool:**

    - Click on `Tools` in the upper left corner:

        ![Open Tools](https://github.com/user-attachments/assets/3b83f8d5-a722-48bc-8a7d-c8d26461870c)

    - Select the option: **Bitmap Display**
      
        ![Bitmap Display](https://github.com/user-attachments/assets/5bf93964-7af0-4272-9475-707587c40cc1)

    - Change the first two fields to **4 pixels**:

        ![Configure Pixels](https://github.com/user-attachments/assets/b1f2a27e-a201-45f5-b22a-45bbccc7f6d7)

    - Change fourth field to **512**:
      
        ![Configure Pixels](https://github.com/user-attachments/assets/fdaddff5-8f57-4a6c-ac83-f0b75eaa11b3)

    - Click the **Connect to MIPS** button:
      
        ![Connect to MIPS](https://github.com/user-attachments/assets/2e12358f-c02c-4247-bcd2-6bce76b3f796)

4. **Opening the keyboard tool:**

    - In `Tools` again, select the **Keyboard and Display MMIO Simulator** option:

        ![Open Keyboard](https://github.com/user-attachments/assets/319b8b16-9857-41d9-adca-060aba52df8a)

    - Click the **Connect to MIPS** button:
      
        ![Connect to MIPS](https://github.com/user-attachments/assets/04e4b353-c67c-4abf-a893-129e9af2c5b7)

5. **Organizing the Screen:**

    - Arrange the two tools on your screen:

        ![Organize Screen](https://github.com/user-attachments/assets/0d25fc57-8f7e-4912-a406-da23eddd36f6)

6. **Running the game**

    - Click the `Run` icon at the top of the window:
      
        ![Run Game](https://github.com/user-attachments/assets/d29cb0dc-abbc-44fa-9db3-6bb856a1c893)

    - Click the icon next to it to start the game:

        ![Start Game](https://github.com/user-attachments/assets/03400194-6244-49a0-a466-a95fb330bc69)

    - Use the keyboard area to type actions:

        ![Keyboard Area](https://github.com/user-attachments/assets/eb93184c-2e3d-4f54-bc69-04b99d998762)

## Commands ⌨️

- `w` => Makes currently falling piece fall all the way to the bottom.
- `a` => Makes currently falling piece move left.
- `s` => Makes currently falling piece fall faster.
- `d` => Makes currently falling piece move right.

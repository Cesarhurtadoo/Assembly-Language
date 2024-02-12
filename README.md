# Assembly Language Code

This assembly language code is designed to read a character from the keyboard, toggle its case (convert uppercase letters to lowercase and vice versa), and then write the modified character to the monitor.

## Code Overview

The code consists of several sections:

- **\_start:** Entry point of the program.
- **\_read:** System call to read input from the keyboard.
- **\_togglecase:** Toggle the case of the input character.
- **\_write:** System call to write the modified character to the monitor.
- **\_exit:** Exit the program.

## Usage

1. Assemble the code using an appropriate assembler.
2. Execute the resulting binary file.
3. Enter characters from the keyboard.
4. The program will toggle the case of each character and display the result on the monitor.
5. Exit the program when finished.

## System Calls Used

- **read:** System call number 3, used to read input from the keyboard.
- **write:** System call number 4, used to write output to the monitor.
- **exit:** System call number 1, used to exit the program.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This code is provided under the [MIT License](LICENSE).

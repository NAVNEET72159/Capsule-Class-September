# Music File Search and Metadata Extractor 🎵

A Java program that searches for music files within specified directory paths, retrieves basic file attributes, and extracts metadata for those music files.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Program Explanation](#program-explanation)
- [Data Classes](#data-classes)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites 🛠️
- Java Development Kit (JDK)
- Java IDE (e.g., IntelliJ IDEA, Eclipse) or Command-Line Tools
- Basic knowledge of Java programming

## Getting Started 🚀
1. Clone or download this repository to your local machine.
2. Open the project in your Java IDE or compile and run it using command-line tools.

## Usage 📋
1. Run the program.
2. Enter the directory paths to search for music files, separated by commas.
3. The program will search for music files, retrieve basic file attributes, and display the collected information on the console.

## Program Explanation ℹ️
- The program uses recursion to search for music files in specified directory paths.
- It extracts basic file attributes such as name, size, creation time, last modified time, and owner information.
- Metadata about music files (e.g., artist, album, title, year, genre, duration) can be extracted and displayed.

## Data Classes 📦
The program uses two record classes:
- `ModelMusic`: Represents basic information about music files (e.g., name, size, path, metadata).
- `MetaData`: Represents metadata about the music files (e.g., artist, album, title, year, genre, duration).

## Contributing 🤝
Contributions are welcome! If you have suggestions or improvements, please open an issue or create a pull request.

## License 📜
This project is licensed under the [MIT License](LICENSE).

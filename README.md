# Grass Identifier

## Overview

Grass Identifier is a tool designed to efficiently identify various species of grasses based on a series of binary trait questions. Utilizing a decision tree classifier, the tool narrows down the possible grass species with each question, aiming to identify the correct species with the fewest number of questions.

## Features

- **Binary Trait Questions**: Simple yes/no questions that help in narrowing down the grass species.
- **Entropy-based Questioning**: Uses entropy calculations to determine the most efficient questions to ask next.
- **User-friendly Interface**: Easy-to-use interface that guides users through the identification process.
- **Extensive Grass Database**: Contains a wide variety of grass species and their associated traits.
- **Optimized Question Order**: Over time, the tool refines the order of questions based on user responses to improve identification efficiency.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/grass-identifier.git
   ```

2. Navigate to the project directory:
   ```
   cd grass-identifier
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   python main.py
   ```

## Usage

1. Start the Grass Identifier tool.
2. Answer the binary trait questions as they appear.
3. After a series of questions, the tool will either identify the grass species or narrow it down to a few possibilities.
4. If the tool cannot definitively identify the grass, consider providing more detailed information or checking against the provided list of potential matches.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push to your fork.
4. Open a pull request against the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The decision tree classifier algorithm was inspired by the binary search tree concept.
- Thanks to the botanists and grass enthusiasts who contributed to the grass database.

---

For any issues or suggestions, please [open an issue](https://github.com/yourusername/grass-identifier/issues) on GitHub.
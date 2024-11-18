<!-- @format -->
# Personal Trainer using OpenAI Assistance API

## Overview
The **Personal Trainer** project leverages the OpenAI Assistance API to provide users with personalized training plans and advice. This program can serve as a digital personal trainer by offering tailored workout routines, fitness tips, and progress tracking based on user input.

## Features
- Interactive fitness guidance using natural language prompts.
- Personalized workout suggestions based on user goals and fitness levels.
- Integration with OpenAI's API for intelligent and adaptive responses.
- Easy-to-use command-line interface for direct interaction.

## Project Structure
- **`main.py`**: The core script containing the logic for interacting with the OpenAI Assistance API and processing user input.
- **`.env`**: Stores environment variables like API keys (not included in the repository for security reasons).
- **`.gitignore`**: Ensures sensitive files like `.env` are excluded from the repository.
- **`requirements.txt`**: Lists all the dependencies required for the project.

## Prerequisites
1. **Python 3.7 or higher**
2. Install the required libraries using:
   ```bash
   pip install -r requirements.txt
   ```

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/personal-trainer.git
   cd personal-trainer
   ```

2. Create a `.env` file in the project directory with the following content:
   ```
   OPENAI_API_KEY=your-api-key-here
   ```

3. Run the program:
   ```bash
   python main.py
   ```

4. Interact with the Personal Trainer by providing inputs like fitness goals, workout preferences, and more.

## Dependencies
The project uses the following Python libraries:
- `python-dotenv`: For managing environment variables.
- `openai`: For interacting with OpenAI's API.

Install them via:
```bash
pip install -r requirements.txt
```

## Customization
- Modify `main.py` to add or change features, such as including nutrition advice or detailed workout plans.
- Update the `.env` file to include additional environment variables if needed.

## Contribution
Feel free to fork this repository and submit pull requests for enhancements or bug fixes. Contributions are always welcome!

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

# Gmail Automation

Gmail Automation is a Python project that automates the process of reading and summarizing new unread emails in your Gmail inbox. The summarized content is then transformed into a spoken output, providing a convenient way to consume your emails hands-free.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Email Extraction:** Automatically retrieves new unread emails from the Gmail inbox.
- **Summarization:** Summarizes the content of each email for quick understanding.
- **Text-to-Speech:** Converts the summarized content into a spoken output.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.12.x or higher
- [Google API credentials](https://developers.google.com/gmail/api/quickstart) for Gmail API access.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/Gabriel-Dee/Gmail-Automation.git
   cd Gmail-Automation
   ```
2. Create environment and Activate it:

   ```
   python -m venv env
   source env/bin/activate
   ```

3. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Set up Google API credentials following the instructions [here](https://developers.google.com/gmail/api/quickstart).

5. Set up openAI API credentials following the instructions [here](https://platform.openai.com/docs/overview).


## Usage

1. Run the main script:

   ```bash
   python main.py
   ```

2. Follow the on-screen instructions to authenticate and grant access to your Gmail account.

3. Sit back and listen as the program reads out the summarized content of your new unread emails.

## Configuration

- Modify the `config.py` file to customize settings such as summarization algorithms, voice options, etc.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

# LinkedIn Automation App

The LinkedIn Automation App is a Python-based web scraper built using Selenium and Streamlit. This application allows you to automate various tasks on LinkedIn, including adding connections, sending custom messages, and generating AI-powered messages.

## Features

- **Add Connections**: Send connection requests to LinkedIn profiles based on a specified URL and number of pages.
- **Send Custom Message to connections**: Send personalized messages to your LinkedIn connections.
- **Send Message generated by AI**: Use OpenAI's language model to generate customized messages based on prompts.

## Installation

1. Clone the repository:
   ```shell
   git clone https://github.com/Shabbir-Handa/Linkedin_Automation.git
   cd Linkedin_Automation
   ```

2. Install the dependencies:
   ```shell
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   - Open the `.env` file and provide your OpenAI API key.
   - Also in the `.env` file provide your linkedin.com Email and Password
## Usage

1. Run the app:
   ```shell
   streamlit run main.py
   ```

2. Open the provided URL in your web browser.

3. Use the sidebar to select the desired service:
   - **Add Connections**: Provide the URL and number of pages to send connection requests.
   - **Send Custom Message to connections**: Enter the message and customize whether to include the connection's name.
   - **Send Message generated by AI**: Enter the prompt and generate AI-powered messages.

## Contributing

Contributions are welcome! To contribute to the LinkedIn Automation App, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure they adhere to the project's coding style.
4. Test your changes thoroughly.
5. Commit your changes with clear and descriptive messages.
6. Push your branch to your forked repository.
7. Open a pull request against the `main` branch of the original repository.
8. Be ready to address any feedback or questions during the code review process.

Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for more details.

## Code of Conduct

Please review and adhere to the [Code of Conduct](https://www.contributor-covenant.org/) when participating in this project.

## Reporting Issues

If you encounter any bugs, have questions, or would like to suggest new features, please open an issue on the [GitHub issue tracker](https://github.com/Shabbir-Handa/Linkedin_Automation/issues).

## Acknowledgements

- [Streamlit](https://streamlit.io/) - Python framework for building interactive web apps.
- [Selenium](https://www.selenium.dev/) - Web automation and testing tool.
- [OpenAI](https://openai.com/) - Platform for AI-powered applications.
- [Contributor Covenant](https://www.contributor-covenant.org/) - Code of Conduct.

## Contact

For any inquiries or support, please contact [shabbirahanda52@gmail.com].
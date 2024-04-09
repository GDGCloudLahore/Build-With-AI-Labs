# Build With AI - Lahore Labs 🌟
## Workshop on Google Gemini

Welcome to the Build With AI - Lahore Labs workshop focused on Google Gemini. This guide will walk you through setting up your API key 🗝️, understanding the project folder structure 📁, and ensuring the security of your sensitive data 🔒.

### Setup API Key

To interact with Google Gemini, you'll need an API key. Here's how to obtain it:

1. **Obtain a Gemini API Key**: Visit the [Google Maker Suite official website](https://makersuite.google.com/app/apikey) to acquire your API key. Follow the on-site instructions to register and receive your key.

### Folder Structure

The project is organized into two main folders for clarity and ease of use:

- **Problem Set**: Contains the project's problem sets, designed to challenge and enhance your understanding of Google Gemini.
- **Solution**: Offers solutions to the problem sets for reference or verification of your solutions.

### Secure Your Gemini API Key

It's crucial to keep your Gemini API key secure to prevent unauthorized access to your account. Here's how you can secure your key on GitHub and within your Python projects:

#### On GitHub:

- **Avoid Hardcoding Keys** 🔑: Never hardcode your API keys directly into your files, especially if you're pushing them to public repositories on GitHub.
- **Use Environment Variables** 🌍: Store your API key in an environment variable and reference it in your code. This method ensures your key is not exposed if your code is shared or made public.
- **Gitignore** 🚫: Ensure your environment variable files (e.g., `.env`) are listed in your `.gitignore` file to prevent them from being accidentally committed and pushed to GitHub.

#### In Python Projects:

1. **Environment Variables**: Store your API key in an environment variable. This can be done by creating a `.env` file in your project root and adding your API key like so:
   ```plaintext
   GEMINI_API_KEY=your_api_key_here
   ```
2. **Access the Environment Variable in Python**:
   Use a package like `python-dotenv` to load and use environment variables in your Python code. Here's a quick guide:
   - Install `python-dotenv` using pip:
     ```bash
     pip install python-dotenv
     ```
   - Load your environment variables at the start of your script:
     ```python
     from dotenv import load_dotenv
     import os

     load_dotenv()  # This loads the environment variables from a .env file

     GEMINI_API_KEY = os.getenv("GEMINI_API_KEY")
     ```
   - Use `GEMINI_API_KEY` in your code to authenticate with Google Gemini without exposing the key itself.

### Get Your Digital Badge 🏅

Follow these steps to participate in the project, complete a problem lab, and earn your Digital badge.

#### Step 1: Clone the Repository

- **Important**: Do not fork the repository if you're not contributing to it. Instead, clone the repository to work on a problem lab. You can refer to the solutions provided during the lab for assistance.

#### Step 2: Choose Your Development Environment

- For your project, you may use one of the following environments:
  - Google Colabs
  - GitHub Codespaces
  - Your local machine's editor

#### Step 3: Create Your New Repository

- Create a new repository on GitHub. Name it `Built With AI - Google Cloud Lahore Gemini Labs`.
- Add this new repository as a remote origin to your project. This step involves using git commands to set up your local repository's remote URL.

#### Step 4: Commit Your Changes

- Before committing, check the status of your local repository to see the changes. Use the `git status` command.
- Commit your code changes to your GitHub remote repository. Ensure you add a meaningful commit message that describes the changes or features you are adding.

#### Step 5: Prepare Your README File

- Create a README file for your repository. The README should include:
  - A description of the lab problem you solved.
  - The output of your solution.
- The README file is crucial as it provides an overview of your project and lab solution to others.

#### Step 6: Earn Your Digital Badge

- Once you have completed your project and pushed it to GitHub, fill out the provided form to claim your Digital badge. This badge recognizes your participation and achievement in the Built With AI - Lahore Google Gemini Labs project.

Remember, this project is not only about coding but also about sharing knowledge and contributing to the community. Good luck!

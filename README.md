# LinkedIn Reviewer Chatbot

A chatbot designed to assist with reviewing LinkedIn profiles. This project allows you to automate LinkedIn interactions through a simple server setup.

## Getting Started

### Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory and run:
   ```bash
   npm install
   ```
3. Copy the `.env.example` file to `.env` and provide the necessary environment variables.
4. Start the development server using:
   ```bash
   npm run dev
   ```

### Retrieving Cookies & CSRF Token

To interact with LinkedIn, you need to fetch your LinkedIn `cookie` and `csrf` token:

1. Open your browser and log in to [LinkedIn](https://www.linkedin.com/) (preferably with a new account).
2. Open Developer Tools (usually `F12` or `Ctrl+Shift+I`).
3. Navigate to the **Network** tab.
4. Find and select a request labeled `GraphQL` under the network activity.
5. Copy the `cookie` and `csrf` token values from the request headers.
6. Paste these values into your `.env` file under the appropriate fields.

---

You're now ready to use the LinkedIn Reviewer Chatbot!

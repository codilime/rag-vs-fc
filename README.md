Check out the demo video [here](https://www.youtube.com/watch?v=Dpll7izWKEQ&ab_channel=CodiLime)


# RAG vs. Function Calling
## Setup Guide

This guide will help you set up and run the Streamlit application on your local machine.

## Step 1: Obtain API Key & Credentials

You will need to obtain the following API key & Credentials:

- `OPENAI_API_KEY`
- `SALESFORCE_USERNAME`
- `SALESFORCE_PASSWORD`
- `SALESFORCE_SECURITY_TOKEN`


Once you have your keys, you will need to set them as environment variables. Open a terminal or command prompt and run the following commands:

```bash
export OPENAI_API_KEY=your_openai_api_key_here
```

Replace `your_openai_api_key_here` with your actual API key.

## Step 2: Install Dependencies

The application requires certain Python packages to run. These dependencies are listed in a `requirements.txt` file.
Navigate to the root directory of the project in your terminal or command prompt and run the following command to install the dependencies:

```bash
pip install -r requirements.txt
```


## Step 3: Run the Notebooks


## License

This project is licensed under the terms of the [MIT License](LICENSE).

## External free libraries used
- [openai](https://platform.openai.com/docs/libraries)
- [python-dotenv](https://pypi.org/project/python-dotenv/1.0.1/)
- [langchain](https://pypi.org/project/langchain/0.2.1/)
- [langchain-community](https://pypi.org/project/langchain-community/)
- [pypdf](https://pypi.org/project/pypdf/)
- [simple_salesforce](https://pypi.org/project/simple-salesforce/)
- [chromadb](https://pypi.org/project/chromadb/)
- [tiktoken](https://pypi.org/project/tiktoken/)


## Authors and acknowledgment

The author of this code is Katarzyna Hewelt (katarzyna.hewelt@codilime.com), CodiLime (codilime.com).

# Building a RAG application

Building a simple RAG (Retrieval-Augmented Generation) application using OpenAI's API.

## Installation

1. Clone the repository.
2.  Create a virtual environment and install the required packages:

```shell
python3 -m venv .venv
source .venv/bin/activate
```

3. (Optional) Alternatively, you can use devbox for environment management:
```shell
# Install devbox if not already installed
curl -fsSL https://get.jetpack.io/devbox | bash

# Start devbox shell
devbox shell

# Install dependencies
devbox install
```

4. Install the required dependencies by running the following command:

```shell
pip install -r requirements.txt
```

4. Create a `.env` file in the root directory of your project.
5. Add the necessary environment variables to the `.env` file. For example:

```plaintext
OPENAI_API_KEY=[your_api_key]
```

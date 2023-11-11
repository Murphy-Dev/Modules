# CustomGPT

CustomGPT is a free and open-source library that provides a customized version of the GPT language model. It allows for greater customization and flexibility in defining the rules and personality of the AI.

## Features

- Customizable rules: With CustomGPT, you have the freedom to define your own rules for the AI model. This means you can tailor the behavior and responses of the AI to suit your specific needs.

- Personality customization: You can customize the personality of the AI to give it a unique character and tone. This allows for more engaging and personalized interactions with the AI.

- Self-hosted AI model: CustomGPT enables you to host the AI model on your own infrastructure, giving you full control over its usage and ensuring compliance with your own ethics and guidelines aswell as allowing you to embed it into your application and adding custom ui's etc

## Getting Started

To get started with CustomGPT, follow these steps:

1. Clone the CustomGPT repository to your local machine.

2. Install the required dependencies by running the following command:

   ```
   pip install -r requirements.txt
   ```

3. Set up your API key for accessing the OpenAI GPT model. You can obtain an API key from the OpenAI website.

4. Customize the ethics, key, model, temperature, frequency_penalty, presence, and personality parameters in the `AI` class according to your requirements.

5. Start using the CustomGPT library by importing the necessary classes and methods into your Python project.

## Usage

Here's an example of how to use CustomGPT:

```python
from customgpt import AI

# Create an instance of the AI class
ai = AI(ethics="Custom ethics", key="your-api-key", model="your-model", temperature=0.9, frequency_penalty=0.0, presence=1.0, personality="Custom personality")

# Create a new thread
thread = ai.NewThread("Thread 1")

# Send a message to the AI model
response = thread.Send("Hello, how are you?")

# Print the AI's response
print(response)
```

## Contributing

Contributions to CustomGPT are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request 


## Prompt Engineering with Gemini API

Prompt engineering involves designing and refining prompts to effectively interact with language models like GPT-4. This process includes crafting specific questions, providing context, and adjusting the wording to elicit accurate and relevant responses from the model. By carefully constructing prompts, users can guide the model to generate desired outputs, enhance its performance on particular tasks, and ensure clarity and precision in the generated text. This technique is crucial for optimizing the utility of AI models in various applications, from content creation to problem-solving.

### Getting Started with Gemini

#### Setting up Gemini API key

1. Go to the [website](https://ai.google.dev/gemini-api?gad_source=1&gclid=CjwKCAjw34qzBhBmEiwAOUQcF8qd5IqzZYQYs8Jaeo0dUGZ8xGsqd9FH5HAorjRDeTsLDYhAhwmw0RoC5soQAvD_BwE)

2. Create a API key, make sure donot disclose your API key anywhere
3. create '.env' and store the key.
4. Load environment variables from .env file

            'load_dotenv()'

5. Load API key from environment variable

           'api_key = os.getenv("my_key")'


6. Configure with the loaded API key

         'genai.configure(api_key=api_key)'

5. you are all set now. 

6. See the src file to fully understand the how LLM's responds to our prompts

### Contact

If you have any questions or comments, feel free to contact me on [Email](mailto:achadharma333@gmail.com)

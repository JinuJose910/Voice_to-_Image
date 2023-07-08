# Voice_to-_Image
This repository contains code that combines the power of OpenAI's ChatGPT and DALL-E models to perform speech-to-text transcription and generate images based on voice prompts. The code utilizes the `gradio` library to create a user-friendly interface for real-time interaction.

## Setup

To run the code in this repository, please follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running the following command:

```shell
pip install -r requirements.txt
```

3. Obtain an API key from OpenAI and replace the placeholder API key in the code with your actual OpenAI API key. Find the following line in the code and update it:

```python
openai.api_key = "YOUR_API_KEY"
```

4. Run the code using the following command:

```shell
python main.py
```

## Usage

Once the code is running, a graphical user interface (GUI) will launch, allowing you to interact with the speech-to-text and image generation functionality.

1. Click on the "Start" button to activate the microphone.
2. Speak into the microphone, and the code will transcribe your speech into text using OpenAI's Whisper model.
3. The text will be passed as a prompt to ChatGPT, which will generate a DALL-E2 prompt.
4. The DALL-E model will then generate an image based on the prompt.
5. The transcribed text and generated image will be displayed in the interface.

## Customization

You can modify the code to suit your needs. For example, you can change the models used (e.g., different versions of ChatGPT or DALL-E) or add additional processing steps for further analysis or visualization.

Please refer to the `gradio` documentation (https://www.gradio.app/docs) for more information on customizing the user interface and incorporating different input and output components.

## Acknowledgments

This code is built upon the `gradio` library and utilizes the power of OpenAI's models, including ChatGPT and DALL-E. We acknowledge the contributors of these libraries for their valuable contributions to this project. This is a guided project by Pooja Madam from OpenWeaver as a part of Virtual Internship


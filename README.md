# Image Captioning with Hugging Face API and Gradio

This repository contains a simple yet powerful Image Captioning application using the Hugging Face API for image-to-text conversion and Gradio for creating an interactive and user-friendly interface. With this application, you can upload an image, and the model will generate a caption for it.

## Getting Started

### Prerequisites

Before running the code, make sure you have the necessary dependencies installed. You can install them using the following command:

```bash
pip install -r requirements.txt
```
# Environment Variables

To use the Hugging Face API, you need to set up your Hugging Face API key. Create a `.env` file in the root of your project and add your API key:

```bash
HF_API_KEY=your_hugging_face_api_key
  ```
# Running the Application

Run the application using the following command:

```bash
python app.py
```
# Components

## 1. Hugging Face API Integration

The `get_completion` function in the `app.py` file handles the communication with the Hugging Face API's image-to-text endpoint. It sends a POST request with the base64-encoded image to the API and retrieves the generated text.

## 2. Gradio Interface

The Gradio interface is defined in the `captioner` function. It takes an image as input, converts it to base64 format, sends it to the Hugging Face API, and displays the generated caption in a user-friendly interface. Gradio makes it easy to create interactive applications without the need for complex frontend development.

# Usage

1. Run the application as mentioned in the "Running the Application" section.
2. Open your web browser and go to the provided Gradio interface link.
3. Upload an image using the provided interface.
4. View the generated caption for the uploaded image.

# Acknowledgments

- [Hugging Face](https://huggingface.co/) for providing the powerful API used in this project.
- [Gradio](https://www.gradio.app/) for simplifying the creation of interactive interfaces.

`title: Gradio Image Caption` `emoji: 🦀` `colorFrom: red` `colorTo: indigo` `sdk: gradio` `sdk_version: 3.39.0` `app_file: app.py` `pinned: false` `license: mit`

Check out the app at https://huggingface.co/spaces/nishikantmandal007/gradio-image-caption

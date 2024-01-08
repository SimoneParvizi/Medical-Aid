# Medical Help using Multimodal LLM

## About

This Streamlit application utilizes OpenAI's LLM to analyze medical images. Users can upload images, and the app provides an analysis that points out any irregularities, illnesses, or conditions visible in the images.

![Medical Aid](https://github.com/SimoneParvizi/Medical-Aid/assets/75120707/b63c2b76-cb8a-4ccd-8778-32903bb01bc9)


## Features

- **Image Upload**: Upload medical images in JPG, JPEG, or PNG formats.
- **LLM Analysis**: Leverage the power Large Language Models to analyze medical images.
- **Explain Like I'm 5 (ELI5)**: Simplified explanations of complex medical terms for easier understanding.

## How to Use

1. **Upload an Image**: Click on the 'Upload an Image' button to upload your medical image.
2. **Analyze Image**: After uploading, click 'Analyze Image' to start the analysis.
3. **View Results**: The analysis will be displayed below the image.
4. **ELI5 Explanation**: For a simplified explanation, select 'Yes' under the ELI5 section.

## Running the App

To run the application, follow these steps:

1. **Start the App**: Navigate to the project directory in your terminal and run the following command:

    ```bash
    streamlit run app.py
    ```

2. **Access the App**: Once the server starts, it will be accessible via your web browser. By default, the app runs at:

    ```
    http://localhost:8501
    ```

3. **Interact with the App**: Follow the on-screen instructions to upload a medical image and receive an analysis.

## Tips for Using the App

- Ensure that the image format is either JPG, JPEG, or PNG.
- Wait for the analysis to complete after uploading the image.
- For a simplified explanation, choose the 'Yes' option under the ELI5 (Explain Like I'm 5) section.

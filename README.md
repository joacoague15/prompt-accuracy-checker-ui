# Prompt Accuracy Checker UI

The Prompt Accuracy Checker is an application that analyzes the accuracy of prompts for stable diffusion. With the click of a button, users can submit a prompt and receive a percentage score indicating how detailed the prompt is. In addition to the score, users will also see an image related to the prompt and a short description of the prompt.

## Getting Started

To get started with the Prompt Accuracy Checker: 
Clone this repository and run `npm install` && `npm start`

## How to Use
1. Enter your prompt in the text input field.
2. Click the "Generate" button.
3. Wait a few seconds for the analysis to complete.
4. View the percentage score and accompanying image and description.

## Technologies Used
The Front-end of Prompt Accuracy Checker is built using React. The image generation and scoring is handled by a backend API that the front-end communicates with via GET requests.

## Contributing
If you would like to contribute to the Prompt Accuracy Checker, please fork this repository and submit a pull request with your changes.

## Acknowledgments
This project was inspired by the need to quickly and accurately assess the quality of prompts for stable diffusion. Thanks to OpenAI for providing the models used in the backend API.

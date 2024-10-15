# Image-Search-Assistant-with-AI-Generated-Descriptions
This project is a web-based tool that allows users to upload images, provide search prompts, and retrieve relevant web search results. By combining image captioning AI models and a web search API, the tool enhances the search process by generating contextual descriptions of images and returning web results based on user-defined prompts.



Here’s a description you can use for your GitHub project:

Image Search Assistant with AI-Generated Descriptions
This project is a web-based tool that allows users to upload images, provide search prompts, and retrieve relevant web search results. By combining image captioning AI models and a web search API, the tool enhances the search process by generating contextual descriptions of images and returning web results based on user-defined prompts.

Key Features:
Image Upload & Processing: Users can upload an image, which is analyzed using the BLIP (Bootstrapped Language-Image Pre-training) model to generate a description.
Customizable Prompts: Users can enter a search prompt that will be combined with the AI-generated image description for more accurate searches.
Real-time Web Search: The tool integrates with SerpAPI to perform real-time web searches based on the combined image caption and user prompt.
Results Display: Web search results, including titles and links, are displayed in the application for easy access.
Tech Stack:
Backend: Google Colab (Python) for image captioning using the BLIP model.
Frontend: Anvil framework for building the web interface and handling user interactions.
API: SerpAPI for fetching search results based on the processed text.
Integration: Anvil Uplink for connecting the web app to the Google Colab backend.
How It Works:
Users upload an image and provide a prompt.
The image is analyzed using the BLIP image-captioning model to generate a descriptive caption.
The user-defined prompt is combined with the image caption.
The combined text is sent to the SerpAPI, which returns relevant web search results.
The results (titles and links) are displayed in the web app for the user to browse.


![image](https://github.com/user-attachments/assets/dd415e71-7b20-4658-8cde-2c255d25320a)

![image](https://github.com/user-attachments/assets/d328de8b-a3a8-416d-bfbe-b13b781eafe0)


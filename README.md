# Stable Diffusion 
Stable Diffusion is a latent text-to-image diffusion model. Thanks to a generous compute donation from Stability AI and support from LAION, we were able to train a Latent Diffusion Model on 512x512 images from a subset of the LAION-5B database. Similar to Google's Imagen, this model uses a frozen CLIP ViT-L/14 text encoder to condition the model on text prompts. With its 860M UNet and 123M text encoder,the model is relatively lightweight and runs on a GPU with at least 10GB VRAM

# Text-to-Image with Stable Diffusion

![image](https://user-images.githubusercontent.com/106483459/209474631-3ae678c0-b6a4-4f46-b08d-069a2661fc3d.png)

## Requirements

- Executed in google colab as the execution requires Vram of atleast 10gb.If your local machine meets the requirements,you can run it on your local machine 
- Hugging face Access tokens
- Ngrok Auth tokens

## Comments 

- For more information see [Stable Diffusion - What, Why, How?](https://youtu.be/ltLNYA3lWAQ) and [creating streamlit app using ngrok](https://youtu.be/MUD-pBOnvdo)

# CutoutProAutomatorBot

CutoutProAutomatorBot is a UiPath automation sequence designed to enhance images using the Cutout.Pro photo enhancer. This bot automates the process of uploading images, downloading the enhanced versions, and deleting the original images from a specified folder.

## Features

- Automates image enhancement using Cutout.Pro
- Uploads images from a specified folder
- Downloads enhanced images automatically
- Deletes original images after enhancement

## Requirements

- UiPath Studio (2024.10.1)
- A web browser (e.g., Chrome, Firefox)
- Internet connection

## Setup

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/CutoutProAutomatorBot.git
    ```

2. Open the project in UiPath Studio.

3. Ensure you have a folder with images that need enhancement at `E:\tmp3\blur`.

## How to Use

1. Open the UiPath Studio and run the project.
2. The bot will:
   - Open a web browser and navigate to [Cutout.Pro](https://www.cutout.pro/photo-enhancer-sharpener-upscaler/upload).
   - Click on the "Upload Image" button.
   - Select an image from the folder `E:\tmp3\blur`.
   - Wait for 15 seconds for the enhancement process.
   - Click the "Free Download" button if it is visible.
   - Refresh the site using `F5`.
   - Delete the original image from the folder.
   - Repeat the process for all images in the folder.

## Demo Video

Watch the demo video below to see the bot in action:




https://github.com/user-attachments/assets/8cfde1a9-0164-4047-a4d1-d50ade724e3d






## Acknowledgements

- [Cutout.Pro](https://www.cutout.pro/) for providing the photo enhancer service.

# Comfy_Moondream_Caption
Comfy Moondream Caption (Dataset Caption Tool for Comfyui)

Welcome to Comfy Moondream Caption, a tool designed to generate captions for images using a local LMM. Follow the steps below to get started:

![Moondream_01](https://github.com/DenRakEiw/Comfy_Moondream_Caption/assets/89697885/ec37a780-5571-4e21-83fb-5f0a7c5d9aa6)



Select Image Folder:

Navigate to the "folder_path" option and select the folder where your images are stored. Ensure that the images are in the supported format (e.g., PNG, JPEG).



Naming Convention:

Ensure that the images in the selected folder are sequentially numbered, such as "1.png", "2.png", and so on. This numbering is crucial for proper processing.



Enable Batch Captioning:

To enable batch captioning, go to the "Extra Options" section in the Comfy UI.

Select "Auto Queue" to ensure that captions are generated for all images in the selected folder.



Generate Captions:

Once the folder and options are set, click on the "Que Prompt" button to initiate the caption generation process.

Comfy Moondream Caption will analyze each image in the folder and generate captions for them.





Post-Processing:

After the caption generation process is complete, it's essential to reset the start index manually to 0. This ensures that the tool starts processing from the beginning for the next dataset.

![Moondream_03](https://github.com/DenRakEiw/Comfy_Moondream_Caption/assets/89697885/10644a21-96c6-4d80-8a5e-a029f18b73ba)

![Moondream_04](https://github.com/DenRakEiw/Comfy_Moondream_Caption/assets/89697885/b1179c51-19ad-486b-88bb-fde4db4f922f)





Repeat for Additional Datasets:

If you have more datasets to analyze, repeat the process by selecting a new folder containing images.


Installation:

To set up this workflow, you'll need the ComfyUI Moondream custom nodes developed by Kijai.
You can find them at: https://github.com/kijai/ComfyUI-moondream

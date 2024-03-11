# voice_cloning_elevenlabs

### What do we need?
-	API key
-	Up to 25 audio files with duration maximum 30 seconds
-	Google account to run Google Colab

### Procedure
1.	Open the Google Colab Notebook: https://colab.research.google.com/drive/1yP0UTi-eUc1P1oKAEjqMmLEIDKiszU-i?usp=sharing or access voice_cloning.ipynb file
2.	(Optional) Open original and cloned voice samples to experience the result of voice cloning
3.	Install ElevenLabs library
 
4.	Define api_key with given API key
 
5.	Test api_key by printing remaining characters. Correct API key will run code without errors otherwise errors will pop up.
 
 
6.	Put all pre-recorded audio files into audio folder in sample_data folder
   - Click “folder” icon button on the left
   - Click “triple dot” icon button on the sample_data folder
   - Choose “New folder
   - Set name as “audio”
   - Click “triple dot” icon button on the audio folder
   - Choose “Upload”
   - Upload all audio files
 
8.	Create files variable with uploaded files
 
9.	Clone your voice (make sure everything is prepared)
 
10.	Run code after that to find your voice id (thus unique name is needed)
 
11.	Generate speech from text prompt and alter voice settings for better results
 
ElevenLabs allows to use voice cloning for +Starter subscribers, currently the first month of Starter package use costs 1 USD to have own API key to run Google Colab (From https://elevenlabs.io/app/subscription)

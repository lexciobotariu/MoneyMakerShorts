# Money Maker Shorts
This script adds comments to a video based on the subject of the video using AI.

You will provide some videos that are in portrait mode.
The script will transcribe the audio of the video using Wisper, it will create a TXT file.

Using the transcription, it will create a comment using ChatGPT 3.5 or 4-turbo.
It will generate an audio using XYZ and output the length of the audio.

Based on the length of the audio, it will cut the same length from the original video, 
- Add a blur effect on top
- Mute original audio
- Generate a Subtitle for the comment audio
- Merge the final comment video with the Original video. 

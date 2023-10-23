# Wav2lip_lip_sync
Using the Wav2lip model for generating lip synced video
## Model used: Wav2Lip + GFPGAN
## Original video : 
https://www.youtube.com/watch?v=YMuuEv37s0o&ab_channel=Prasadtechintelugu
## Original audio:
https://drive.google.com/file/d/1jhUOAeGw8lPjNf7Q1cIcBOvzE3CJ3gVz/view
## lip sync video using Wav2Lip : 
https://drive.google.com/file/d/10-4y_9btnCAVFQEO7GKbhXUWLzNApPDk/view?usp=sharing
## STEPS TO USE:
1)Break your video into the parts having a face and no face since wav2lip mandates having a face in the video,accordingly convert audio in chunks.
2)Run the inference using the given code for a video part and corresponding audio.
3)Stitch the videos together.

# Lip-sync_using_wav2lip
Created a Lip Synced video with the help of the video and audio links provided.

# ALGORITHM:

The algorithm consists of the following steps:

1. Pretrained ESRGAN on the given video with the speech of the target person.
2. Applied the Wav2Lip model to the source video and target audio.
3. Upsampled the output of Wav2Lip with ESRGAN.
4. Used BiSeNet to change only relevant pixels in video.

To convert 32bit to 16bit (We want to save space)

ffmpeg -i crash-acoustic.wav -c:a pcm_s16le crash_accoustic_16bit.wav


To build:
idf.py build

To flash it on device:
idf.py flash monitor

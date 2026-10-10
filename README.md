Human Privacy Protection through Object Detection and Encryption

Videos and CCTV footage capture people who never agreed to be recorded. This app hides them automatically, it spots every person with YOLOv8, blurs them, and keeps the originsl frames locked with ChaCha20 encryption. If someone with the right keys needs to see one person, they can unlock a single frame and reveal just that person, without exposing anyone else.

What it does
Blurs people in a video: upload a video and every detected person gets blurred.

Encrypts original frames: a random samole of frames (you choose how many) is encrypted, each with its own key.

Reveal onr person: pick a frame, pick a person, and only that person is shown again.

Live mode: the same blur on your webcam or an RTSP/CCTV stream.

Built with

Python, Streamlit, YOLOv8 (Ultralytics), OpenCV, cryptography (ChaCha20), imageio

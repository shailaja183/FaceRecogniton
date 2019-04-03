# FaceRecogniton
Python/OpenCV based Real-time Face Recognition in Full-HD video, robust to facial expressions, illumination conditions and variants in videos
# Execution Steps
# Train
python facerec.py -t ./Mugshots -r 100x100 -v 10 model_filename.pkl
# Test
python facerec.py model_filename.pkl

# LipReader
LipReader – Silent Speech to Text
A deep learning project that reads lip movements from a video (no sound) and predicts the spoken sentence. Designed to assist the hearing-impaired, enable silent communication, and explore computer vision-based language understanding.
| Area            | Tools / Libraries                 |
| Language        | Python 3                          |
| Computer Vision | OpenCV, Dlib (or MediaPipe)       |
| Deep Learning   | TensorFlow / Keras (CNN + BiLSTM) |
| GUI             | Tkinter                           |
| Dataset         | GRID Corpus / Custom Videos       |
| Version Control | Git + GitHub                      |
Roles of Team Members -                                                                |
Siddhika Savant- Project Lead & ML Developer (Model building (CNN + BiLSTM), data preprocessing, integration, GitHub, documentation)
Samruddhi Shelake- Preprocessing Expert (Extracting frames from videos, cropping lips using Dlib/MediaPipe, organizing dataset)
Harshada Chopade- GUI Designer (Designing the Tkinter-based GUI, adding upload & display features, styling interface)
Aliya Nadaph- Tester & Data Manager (Testing outputs, organizing folders, uploading files, assisting with documentation)
Setup -
git clone https://github.com/your-username/LipReader.git
cd LipReader
pip install -r requirements.txt
To Run -
python main.py

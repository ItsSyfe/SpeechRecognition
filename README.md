# Speech Recognition

Speech Recognition is a test for me to experiment with data science in Python, I'll may be making new things later.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install SpeechRecognition. Note: this isn't my package, I'm simply using it to learn data science

```cmd
pip install SpeechRecognition
```

## Usage
Basic usage from online guide, this is a base for what I'm going to be creating (not sure what I'm gonna be making exactly)
```python
import speech_recognition as sr

r = sr.Recognizer()

harvard = sr.AudioFile('harvard.wav')
with harvard as source:
    audio = r.record(source)

r.recognize_google(audio)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

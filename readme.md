# example results

![spectrogram](/spectro.png "Example spectrogram for XC653412")

Data source: Daniele Baroni on [xeno-canto](http://www.xeno-canto.org/653412)

# install

Set up the environment and dependencies:

```
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Make sure you have ffmpeg on your system:

```
brew install ffmpeg
```

# run notebook

```
source .venv/bin/activate
jupyter notebook blackbird-poc.ipynb
```

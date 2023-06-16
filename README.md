# streamlit-image-juxtapose
A simple Streamlit Component to compare images in Streamlit apps using [Knightlab's JuxtaposeJS](https://juxtapose.knightlab.com/). The images are saved to the streamlit `static` directory then served via streamlit as an image overlay with an adjustable slider.

<p align="center">
<img src="https://github.com/robmarkcole/streamlit-image-juxtapose/blob/main/usage.png" width="700">
</p>

## Development
* Create and activate a venv: `python3 -m venv venv` and `source venv/bin/activate`
* Install requirements: `pip3 install -r requirements.txt`
* Run streamlit: `streamlit run app.py`

## Pip installable alternative
If you wish to `pip install` the functionality provided by this plugin checkout [streamlit-image-comparison](https://github.com/fcakyon/streamlit-image-comparison)

## References
- https://juxtapose.knightlab.com/
- https://github.com/innerdoc/streamlit-timeline
- https://discuss.streamlit.io/t/restrict-download-of-images-videos-on-streamlit-app/11718/2

# streamlit-image-juxtapose
A simple Streamlit Component to compare images in Streamlit apps using [Knightlab's JuxtaposeJS](https://juxtapose.knightlab.com/). The images are saved to the streamlit `static` directory then served via streamlit as an image overlay with an adjustable slider. Try on [https://share.streamlit.io/robmarkcole/streamlit-image-juxtapose/main/app.py](https://share.streamlit.io/robmarkcole/streamlit-image-juxtapose/main/app.py)

<p align="center">
<img src="https://github.com/robmarkcole/streamlit-image-juxtapose/blob/main/usage.png" width="700">
</p>

## Development
* Create and activate a venv: `python3 -m venv venv` and `source venv/bin/activate`
* Install requirements: `pip3 install -r requirements.txt`
* Run streamlit: `streamlit run app.py`

## References
- https://juxtapose.knightlab.com/
- https://github.com/innerdoc/streamlit-timeline
- https://discuss.streamlit.io/t/restrict-download-of-images-videos-on-streamlit-app/11718/2
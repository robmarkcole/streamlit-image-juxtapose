# streamlit-image-juxtapose
A simple Streamlit Component to compare images in Streamlit apps using [Knightlab's JuxtaposeJS](https://juxtapose.knightlab.com/). The images are saved to the streamlit `static` directory then served via stremlit as an image overlay with an adjustable slider.

<p align="center">
<img src="https://github.com/robmarkcole/streamlit-image-juxtapose/blob/main/usage.png" width="700">
</p>

Live example:

<div class="iframe-container">
    <iframe frameborder="0" class="juxtapose" width="100%" height="360" src="https://cdn.knightlab.com/libs/juxtapose/latest/embed/index.html?uid=a8a68540-c5b0-11eb-b7bf-95443c729a29"></iframe>
</div>

## Development
* Create and activate a venv: `python3 -m venv venv` and `source venv/bin/activate`
* Install requirements: `pip3 install -r requirements.txt`
* Run streamlit: `streamlit run app.py`

## References
- https://juxtapose.knightlab.com/
- https://github.com/innerdoc/streamlit-timeline
- https://discuss.streamlit.io/t/restrict-download-of-images-videos-on-streamlit-app/11718/2
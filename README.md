# Streamlit Demo: The Controllable GAN Face Generator
This project highlights Streamlit's new `hash_func` feature with an app that calls on TensorFlow to generate photorealistic faces, using Nvidia's [Progressive Growing of GANs](https://research.nvidia.com/publication/2017-10_Progressive-Growing-of) and Shaobo Guan's [Transparent Latent-space GAN](https://blog.insightdatascience.com/generating-custom-photo-realistic-faces-using-ai-d170b1b59255) method for tuning the output face's characteristics.

The Streamlit app is implemented in only 150 lines of Python and demonstrates the wide new range of objects that can be used safely and efficiently in Streamlit apps with `hash_func`. 

![In-use Animation](https://github.com/streamlit/demo-face-gan/blob/master/GAN-demo.gif?raw=true "In-use Animation")

## How to run this application
The demo requires Python 3.6 (TensorFlow is not yet compatible with later versions). **We suggest creating a new virtual Python 3.6 environment**, then running:

```
git clone https://github.com/Toulik-Das/Face-GAN.git
cd demo-face-gan
pip install -r requirements.txt
streamlit run app.py
```


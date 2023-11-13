# BLIP2-NYT
The repo contains the Jupyter Notebook that fine-tunes the BLIP2 model on the NYT dataset.

The Jupyter Notebook is heavily inspired by YBelkada's work: 
https://huggingface.co/ybelkada/blip-image-captioning-base-football-finetuned

The dataset can be found here:
https://huggingface.co/datasets/generative-newsai/news-unmasked

The fine-tuned model predicts the news category given an image. Keep in mind the size of the dataset, so fine-tuning will 
take a very long time on older GPUs. The model was fine-tuned on a consumer-grade GPU, RTX 4090.


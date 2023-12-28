# cogvlm-image-caption
CLI script using CogVLM and CogAgent for image captioning. Iterates over a folder of images and creates a caption .txt for each image found. Modified from example in CogVLM repo (https://github.com/THUDM/CogVLM)

Example usage: python caption_hf_cli.py --folder_path ./tmp --quant 4 --bf16 --from_pretrained /path/to/model (or hugging face repo_id)

CogVLM models on HF: https://huggingface.co/THUDM

Feel free to fork and modify as needed.

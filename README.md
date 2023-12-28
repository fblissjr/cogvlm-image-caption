
# cogvlm-image-caption

CLI (Command Line Interface) script using CogVLM and CogAgent for image captioning. This script iterates over a folder of images and creates a caption `.txt` file for each image found. It is modified from the example in the CogVLM repository (https://github.com/THUDM/CogVLM).

## Usage

Example usage:

```bash
python caption_hf_cli.py --folder_path [path_to_images] --quant [quant_value] --bf16 --from_pretrained [model_path_or_repo_id]
```

You can find CogVLM models on Hugging Face here: https://huggingface.co/THUDM

## Contributing

Feel free to fork and modify the script as needed for your use case.

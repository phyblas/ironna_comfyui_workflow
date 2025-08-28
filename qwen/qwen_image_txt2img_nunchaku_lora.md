# 简单说明

用qwen image来生成图片。用nunchaku的量化模型来加速。基于[nunchaku开发者提供的工作流](https://github.com/nunchaku-tech/ComfyUI-nunchaku/tree/main/example_workflows)。还用lora来减少步数而更快。

# 需要插件

- [nunchaku.tech / ComfyUI-nunchaku](https://github.com/nunchaku-tech/ComfyUI-nunchaku)
- - NunchakuQwenImageDiTLoader

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
- [svdq-fp4_r128-qwen-image-lightningv1.0-4steps](https://huggingface.co/nunchaku-tech/nunchaku-qwen-image/tree/main)

### clip
- [qwen_2.5_vl_7b_fp8_scaled](https://huggingface.co/Comfy-Org/Qwen-Image_ComfyUI/blob/main/split_files/text_encoders/qwen_2.5_vl_7b_fp8_scaled.safetensors)

### lora
- [Qwen-Image-Lightning-4steps-V1.0](https://huggingface.co/lightx2v/Qwen-Image-Lightning/blob/main/Qwen-Image-Lightning-4steps-V1.0.safetensors)

### vae
- [qwen_image_vae](https://huggingface.co/Comfy-Org/Qwen-Image_ComfyUI/blob/main/split_files/vae/qwen_image_vae.safetensors)

# 简单说明

用qwen image来生成图片。基于comfyui提供的模版。还有用lora来减少步数。

能用中文的提示此所以不用使用自动翻译的节点。而且还能生成中文或日文的字。

# 需要插件

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
- [qwen_image_distill_full_fp8_e4m3fn](https://huggingface.co/Comfy-Org/Qwen-Image_ComfyUI/resolve/main/non_official/diffusion_models/qwen_image_distill_full_fp8_e4m3fn.safetensors)

### clip
- [qwen_2.5_vl_7b_fp8_scaled](https://huggingface.co/Comfy-Org/Qwen-Image_ComfyUI/resolve/main/split_files/text_encoders/qwen_2.5_vl_7b_fp8_scaled.safetensors)

### lora
- [Qwen-Image-Lightning-4steps-V1.0](https://huggingface.co/lightx2v/Qwen-Image-Lightning/resolve/main/Qwen-Image-Lightning-4steps-V1.0.safetensors)

### vae
- [qwen_image_vae](https://huggingface.co/Comfy-Org/Qwen-Image_ComfyUI/resolve/main/split_files/vae/qwen_image_vae.safetensors)

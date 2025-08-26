# 简单说明

用qwen image edit来修改图片。还有用lora来减少步数。

能用中文的提示此所以不用使用自动翻译的节点。

# 需要插件

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
- [qwen_image_edit_fp8_e4m3fn](https://huggingface.co/Comfy-Org/Qwen-Image-Edit_ComfyUI/blob/main/split_files/diffusion_models/qwen_image_edit_fp8_e4m3fn.safetensors)

### clip
- [qwen_2.5_vl_7b_fp8_scaled](https://huggingface.co/Comfy-Org/Qwen-Image_ComfyUI/blob/main/split_files/text_encoders/qwen_2.5_vl_7b_fp8_scaled.safetensors)

### lora
- [Qwen-Image-Lightning-4steps-V1.0](https://huggingface.co/lightx2v/Qwen-Image-Lightning/blob/main/Qwen-Image-Lightning-4steps-V1.0.safetensors)

### vae
- [qwen_image_vae](https://huggingface.co/Comfy-Org/Qwen-Image_ComfyUI/blob/main/split_files/vae/qwen_image_vae.safetensors)

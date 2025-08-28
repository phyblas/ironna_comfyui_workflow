# 简单说明

用florence2来从1张输入图片写出提示词，再来用[shuttle 3 diffusion](https://huggingface.co/shuttleai/shuttle-3-diffusion)模型生成。

# 需要插件

- [kijai / ComfyUI-Florence2](https://github.com/kijai/ComfyUI-Florence2)
- - DownloadAndLoadFlorence2Model
- - Florence2Run

- [kijai / ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)
- - JoinStrings

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorTextNode
- - PreviewTextNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
- [shuttle-3-diffusion-fp8](https://huggingface.co/shuttleai/shuttle-3-diffusion/blob/main/shuttle-3-diffusion.safetensors)

### clip
- [clip_l](https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/clip_l.safetensors)
- [t5xxl_fp8_e4m3fn_scaled](https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/t5xxl_fp8_e4m3fn_scaled.safetensors)

### vae
- [ae](https://huggingface.co/Comfy-Org/Lumina_Image_2.0_Repackaged/blob/main/split_files/vae/ae.safetensors)
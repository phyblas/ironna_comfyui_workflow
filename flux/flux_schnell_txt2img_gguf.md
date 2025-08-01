# 简单说明

用gguf模型来代替原本的unet和vae模型。会节省记忆体。适合用于记忆体不足的电脑和显卡。

# 需要插件

- [city96 / ComfyUI-GGUF](https://github.com/city96/ComfyUI-GGUF)
- - DualCLIPLoaderGGUF
- - UnetLoaderGGUF

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
- [flux1-schnell-Q4_K_S](https://huggingface.co/city96/FLUX.1-schnell-gguf/blob/main/flux1-schnell-Q4_K_S.gguf)

### clip_vision
- [clip_l](https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/clip_l.safetensors)
- [t5-v1_1-xxl-encoder-Q4_K_S](https://huggingface.co/city96/t5-v1_1-xxl-encoder-gguf/blob/main/t5-v1_1-xxl-encoder-Q4_K_S.gguf)

### vae
- [ae](https://huggingface.co/Comfy-Org/Lumina_Image_2.0_Repackaged/blob/main/split_files/vae/ae.safetensors)
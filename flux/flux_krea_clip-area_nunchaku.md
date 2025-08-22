# 简单说明

用条件采用区域来指定人物在场景中的位置。模型用[flux krea dev](https://docs.comfy.org/tutorials/flux/flux1-krea-dev)的nunchaku量化模型。

# 需要插件

- [nunchaku.tech / ComfyUI-nunchaku](https://github.com/nunchaku-tech/ComfyUI-nunchaku)
- - NunchakuFluxDiTLoader

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorTextNode

- [TinyTerra / ComfyUI_tinyterraNodes](https://github.com/TinyTerra/ComfyUI_tinyterraNodes)
- - ttN text

- [Suzie1 / ComfyUI_Comfyroll_CustomNodes](https://github.com/Suzie1/ComfyUI_Comfyroll_CustomNodes)
- - CR Text Concatenate

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
- [svdq-fp4_r32-flux.1-krea-dev或svdq-int4_r32-flux.1-krea-dev](https://huggingface.co/nunchaku-tech/nunchaku-flux.1-krea-dev/tree/main)

### clip
- [clip_l](https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/clip_l.safetensors)
- [t5xxl_fp8_e4m3fn_scaled](https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/t5xxl_fp8_e4m3fn_scaled.safetensors)

### vae
- [ae](https://huggingface.co/Comfy-Org/Lumina_Image_2.0_Repackaged/blob/main/split_files/vae/ae.safetensors)
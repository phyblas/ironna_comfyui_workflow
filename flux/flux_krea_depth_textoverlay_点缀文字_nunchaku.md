# 简单说明

用textoverlay节点画文字，然后用flux depth dev lora把文字点缀为图片。还有用nunchaku量化技术来加速生成过程。

# 需要插件

- [nunchaku.tech / ComfyUI-nunchaku](https://github.com/nunchaku-tech/ComfyUI-nunchaku)
- - NunchakuFluxDiTLoader
- - NunchakuFluxLoraLoader

- [WASasquatch / was-node-suite-comfyui](https://github.com/WASasquatch/was-node-suite-comfyui)
- - Image Blank

- [Munkyfoot / ComfyUI-TextOverlay](https://github.com/Munkyfoot/ComfyUI-TextOverlay)
- - Text Overlay

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
- [svdq-fp4_r32-flux.1-krea-dev或svdq-int4_r32-flux.1-krea-dev](https://huggingface.co/nunchaku-tech/nunchaku-flux.1-krea-dev/tree/main)

### lora
- [flux1-depth-dev-lora](https://huggingface.co/black-forest-labs/FLUX.1-Depth-dev-lora/tree/main)

### clip_vision
- [clip_l](https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/clip_l.safetensors)
- [t5xxl_fp8_e4m3fn_scaled](https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/t5xxl_fp8_e4m3fn_scaled.safetensors)

### vae
- [ae](https://huggingface.co/Comfy-Org/Lumina_Image_2.0_Repackaged/blob/main/split_files/vae/ae.safetensors)
# 简单说明

基于[comfyui官方的工作流](https://comfyanonymous.github.io/ComfyUI_examples/flux/#flux-schnell)。需要unet和2个CLIP模型。

# 需要插件

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
- [flux1-schnell](https://huggingface.co/black-forest-labs/FLUX.1-schnell/tree/main)

### clip_vision
- [clip_l](https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/clip_l.safetensors)
- [t5xxl_fp8_e4m3fn](https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/t5xxl_fp8_e4m3fn_scaled.safetensors)
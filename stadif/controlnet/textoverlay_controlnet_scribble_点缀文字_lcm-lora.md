# 简单说明

用textoverlay节点画文字，然后用controlnet scibble把文字点缀为图片。

用SDXL模型跟lcm-lora。

# 需要插件

- [WASasquatch / was-node-suite-comfyui](https://github.com/WASasquatch/was-node-suite-comfyui)
- - Image Blank

- [Munkyfoot / ComfyUI-TextOverlay](https://github.com/Munkyfoot/ComfyUI-TextOverlay)
- - Text Overlay

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [kijai / ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)
- - ImageConcanate

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型
### controlnet
- [controlnet-scribble-sdxl-1.0](https://huggingface.co/xinsir/controlnet-scribble-sdxl-1.0)

### lora
- [lcm-lora-sdxl](https://huggingface.co/latent-consistency/lcm-lora-sdxl)
# 简单说明

用textoverlay节点画文字，然后用controlnet scibble把文字点缀为图片。

如果文字看不太清楚可以调整controlnet应用的强度让它的值更高。

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
- [control_v11p_sd15_scribble](https://huggingface.co/nolanaatama/models/blob/main/control_v11p_sd15_scribble_fp16.safetensors)
- [controlnet-scribble-sdxl-1.0](https://huggingface.co/xinsir/controlnet-scribble-sdxl-1.0)
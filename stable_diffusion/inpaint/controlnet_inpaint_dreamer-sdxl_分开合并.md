# 简单说明

用controlnet inpaint模型的controlnet-inpaint-dreamer-sdxl做分开生成而合并的图。

# 需要插件

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [WASasquatch / was-node-suite-comfyui](https://github.com/WASasquatch/was-node-suite-comfyui)
- - Image Blank

- [kijai / ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)
- - ImageConcanate
- - ImageConcatMulti

- [Fannovel16 / comfyui_controlnet_aux](https://github.com/Fannovel16/comfyui_controlnet_aux)
- - InpaintPreprocessor

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### controlnet
- [controlnet-inpaint-dreamer-sdxl](https://huggingface.co/destitech/controlnet-inpaint-dreamer-sdxl/tree/main/v2)
# 简单说明

通过controlnet inpaint模型的controlnet-inpaint-dreamer-sdxl来做外补。做法跟原本模型的controlnet inpaint不一样。这个模型的做法是填在白色的部分。

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
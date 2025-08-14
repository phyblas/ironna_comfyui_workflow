# 简单说明

用controlnet inpaint来做分开生成而合并的图。先生成一部分，再用不同的提示词生成另外一部分。但是两个部分之间的边界还是不一定融合得很好。

# 需要插件

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Fannovel16 / comfyui_controlnet_aux](https://github.com/Fannovel16/comfyui_controlnet_aux)
- - InpaintPreprocessor

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### controlnet
- [control_v11p_sd15_inpaint_fp16](https://huggingface.co/comfyanonymous/ControlNet-v1-1_fp16_safetensors/blob/main/control_v11p_sd15_inpaint_fp16.safetensors)
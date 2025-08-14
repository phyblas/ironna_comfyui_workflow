# 简单说明

用[SDXL-lightning](https://huggingface.co/ByteDance/SDXL-Lightning)来减少采样步数，所以能够很快地生成图，但还是会容易变模糊。按照[SDXL-Lightning官方提供的工作流](https://huggingface.co/ByteDance/SDXL-Lightning/blob/main/comfyui/sdxl_lightning_workflow_lora.json)。

# 需要插件

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### lora
- [sdxl_lightning_4step_lora](https://huggingface.co/ByteDance/SDXL-Lightning/blob/main/sdxl_lightning_4step_lora.safetensors)
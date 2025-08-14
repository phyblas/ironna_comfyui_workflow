# 简单说明

同时使用controlnet的openpose和depth map。用已经预处理准备好的openpose和depth map图片。用lcm-lora和SDXL模型。

# 需要插件

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### controlnet
- [controlnet-openpose-sdxl-1.0](https://huggingface.co/xinsir/controlnet-openpose-sdxl-1.0)
- [controlnet-depth-sdxl-1.0](https://huggingface.co/xinsir/controlnet-depth-sdxl-1.0)

### lora
- [lcm-lora-sdxl](https://huggingface.co/latent-consistency/lcm-lora-sdxl)
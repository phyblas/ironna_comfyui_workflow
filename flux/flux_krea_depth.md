# 简单说明

用[flux krea dev](https://docs.comfy.org/tutorials/flux/flux1-krea-dev)模型和flux depth dev lora来从深度图生成。

# 需要插件

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Fannovel16 / comfyui_controlnet_aux](https://github.com/Fannovel16/comfyui_controlnet_aux)
- - DepthAnythingPreprocessor

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
fp8的量化模型
- [flux1-krea-dev_fp8_scaled](https://huggingface.co/Comfy-Org/FLUX.1-Krea-dev_ComfyUI/blob/main/split_files/diffusion_models/flux1-krea-dev_fp8_scaled.safetensors)

fp16的原本模型
- [flux1-krea-dev](https://huggingface.co/black-forest-labs/FLUX.1-Krea-dev)

### lora
- [flux1-depth-dev-lora](https://huggingface.co/black-forest-labs/FLUX.1-Depth-dev-lora/tree/main)
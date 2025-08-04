# 简单说明

基于[comfyui官方的简化版的工作流](https://comfyanonymous.github.io/ComfyUI_examples/flux/#flux-dev-1)。但分unet和CLIP和vae的模型。还有用FLUX.1-Turbo-Alpha的lora来加速。有了这个lora步数只要8就好了。

# 需要插件

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### checkpoint
fp8的缩小模型
- [flux1-dev-fp8](https://huggingface.co/Kijai/flux-fp8/blob/main/flux1-dev-fp8.safetensors)

fp16的原本模型
- [flux1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev/tree/main)

### lora
- [FLUX.1-Turbo-Alpha]（https://civitai.com/models/876388/flux1-turbo-alpha）
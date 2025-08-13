# 简单说明

用[flux krea dev](https://docs.comfy.org/tutorials/flux/flux1-krea-dev)模型和flux depth dev lora来从深度图生成。还有用nunchaku量化技术来加速生成过程。

# 需要插件

- [nunchaku.tech / ComfyUI-nunchaku](https://github.com/nunchaku-tech/ComfyUI-nunchaku)
- - NunchakuFluxDiTLoader

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Fannovel16 / comfyui_controlnet_aux](https://github.com/Fannovel16/comfyui_controlnet_aux)
- - DepthAnythingPreprocessor

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
- [svdq-fp4_r32-flux.1-krea-dev或svdq-int4_r32-flux.1-krea-dev](https://huggingface.co/nunchaku-tech/nunchaku-flux.1-krea-dev/tree/main)

### lora
- [flux1-depth-dev-lora](https://huggingface.co/black-forest-labs/FLUX.1-Depth-dev-lora/tree/main)
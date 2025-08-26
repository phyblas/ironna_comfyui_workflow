# 简单说明

使用[LatentLabs360](https://civitai.com/models/10753/latentlabs360) LoRA来做球面全景图。

提示词必须包含“a 360 equirectangular panorama”。为了方便这里将这部分的提示词分为个别的节点，再拿来连结。

不能使用SDXL模型。

# 需要插件

- [Suzie1 / ComfyUI_Comfyroll_CustomNodes](https://github.com/Suzie1/ComfyUI_Comfyroll_CustomNodes)
- - CR Text
- - CR Text Concatenate

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorTextNode
- - DeepTranslatorCLIPTextEncodeNode

- [FlyingFireCo / tiled_ksampler](https://github.com/FlyingFireCo/tiled_ksampler)
- - Asymmetric Tiled KSampler
- - Circular VAEDecode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### lora
- [LatentLabs360](https://civitai.com/models/10753/latentlabs360)
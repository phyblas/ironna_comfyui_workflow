# 简单说明

使用[LatentLabs360](https://civitai.com/models/10753/latentlabs360) LoRA来做球面全景图。用controlnet inpaint来修补。

提示词必须包含“a 360 equirectangular panorama”。

这个工作流比[采用tiled_ksampler的方法](latentlabs360_tiled_ksampler_球面全景图.json)跟复杂得多，但结果好一些。

不能使用SDXL模型。

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

### lora
- [LatentLabs360](https://civitai.com/models/10753/latentlabs360)

### controlnet
- [control_v11p_sd15_inpaint_fp16](https://huggingface.co/comfyanonymous/ControlNet-v1-1_fp16_safetensors/blob/main/control_v11p_sd15_inpaint_fp16.safetensors)
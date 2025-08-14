# 简单说明

在ipadapter的不同的权重类型做对比看各种有什么样的差别。

# 需要插件
- [WASasquatch / was-node-suite-comfyui](https://github.com/WASasquatch/was-node-suite-comfyui)
- - Image Blank
- - Create Grid Image from Batchˀ

- [Suzie1 / ComfyUI_Comfyroll_CustomNodes](https://github.com/Suzie1/ComfyUI_Comfyroll_CustomNodes)
- - CR Integer Range List
- - CR String To Combo

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [ltdrdata / ComfyUI-Impact-Pack](https://github.com/ltdrdata/ComfyUI-Impact-Pack)
- - ImpactStringSelector
- - ImageListToImageBatch

- [cubiq / ComfyUI_IPAdapter_plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus)
- - IPAdapterUnifiedLoader
- - IPAdapterAdvanced

- [Munkyfoot / ComfyUI-TextOverlay](https://github.com/Munkyfoot/ComfyUI-TextOverlay)
- - Text Overlay

- [kijai / ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)
- - ImageConcanate

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### ipadapter
- [ip-adapter_sd15](https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter_sd15.safetensors)（非SDXL模型）
- [ip-adapter_sdxl_vit-h](https://huggingface.co/h94/IP-Adapter/blob/main/sdxl_models/ip-adapter-plus_sdxl_vit-h.safetensors)（SDXL模型）

### clip_vision
- [CLIP-ViT-H-14-laion2B-s32B-b79K](https://huggingface.co/h94/IP-Adapter/tree/main/models/image_encoder)
（下载model.safetensors，然后改名为CLIP-ViT-H-14-laion2B-s32B-b79K.safetensors）
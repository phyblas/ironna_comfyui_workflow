# 简单说明

通过ipadapter用2张图做参考图生成新的图片。

# 需要插件

- [cubiq / ComfyUI_IPAdapter_plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus)
- - IPAdapterUnifiedLoader
- - IPAdapterEncoder
- - IPAdapterCombineEmbeds
- - IPAdapterEmbeds

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### ipadapter
- [ip-adapter_sd15](https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter_sd15.safetensors)（非SDXL模型）
- [ip-adapter_sdxl_vit-h](https://huggingface.co/h94/IP-Adapter/blob/main/sdxl_models/ip-adapter-plus_sdxl_vit-h.safetensors)（SDXL模型）

### clip_vision
- [CLIP-ViT-H-14-laion2B-s32B-b79K](https://huggingface.co/h94/IP-Adapter/tree/main/models/image_encoder)
（下载model.safetensors，然后改名为CLIP-ViT-H-14-laion2B-s32B-b79K.safetensors）
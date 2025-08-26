介绍使用ipadapter的工作流。

都需要安装[ComfyUI_IPAdapter_plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus)包。

要下载这些ipadapter的模型放在models/ipadapter的文件夹
- [ip-adapter_sd15](https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter_sd15.safetensors)
- [ip-adapter_sd15_light_v11](https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter_sd15_light.safetensors)
- [ip-adapter-plus_sd15.safetensors](https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter-plus_sd15.safetensors)
- [ip-adapter_sd15_vit-G.safetensors](https://huggingface.co/h94/IP-Adapter/blob/main/models/ip-adapter_sd15_vit-G.bin)
- [ip-adapter_sdxl_vit-h](https://huggingface.co/h94/IP-Adapter/blob/main/sdxl_models/ip-adapter-plus_sdxl_vit-h.safetensors)
- [ip-adapter_sdxl.safetensors](https://huggingface.co/h94/IP-Adapter/blob/main/sdxl_models/ip-adapter_sdxl.safetensors)
- [ip-adapter-plus_sdxl_vit-h.safetensors](https://huggingface.co/h94/IP-Adapter/blob/main/sdxl_models/ip-adapter-plus_sdxl_vit-h.safetensors)

还要下载clip vision模型放在models/clip_vision的文件夹
- [CLIP-ViT-H-14-laion2B-s32B-b79K](https://huggingface.co/h94/IP-Adapter/tree/main/models/image_encoder)
（下载model.safetensors，然后改名为CLIP-ViT-H-14-laion2B-s32B-b79K.safetensors）
- [CLIP-ViT-bigG-14-laion2B-39B-b160k](https://huggingface.co/h94/IP-Adapter/tree/main/sdxl_models/image_encoder)
（下载model.safetensors，然后改名为CLIP-ViT-bigG-14-laion2B-39B-b160k.safetensors,）
# 简单说明

基于[PixelMuseAI的Flux Controlnet Upscale工作流](https://civitai.com/models/907489/flux-controlnet-upscale)，使用flux krea模型而加上了nunchaku加速技术。

controlnet的强度可以调整。接近1.0的值会更保持原本的细节。

# 需要插件

- [nunchaku.tech / ComfyUI-nunchaku](https://github.com/nunchaku-tech/ComfyUI-nunchaku)
- - NunchakuFluxDiTLoader

- [kijai / ComfyUI-Florence2](https://github.com/kijai/ComfyUI-Florence2)
- - DownloadAndLoadFlorence2Model
- - Florence2Run

- [kijai / ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)
- - ImageResizeKJv2
- - ColorMatch

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - PreviewTextNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
- [svdq-fp4_r32-flux.1-krea-dev或svdq-int4_r32-flux.1-krea-dev](https://huggingface.co/nunchaku-tech/nunchaku-flux.1-krea-dev/tree/main)

### controlnet
- Flux.1-dev-Controlnet-Upscaler_fp8是[Flux.1-dev-Controlnet-Upscaler](https://huggingface.co/jasperai/Flux.1-dev-Controlnet-Upscaler)的量化模型。使用[kijai的代码](https://huggingface.co/Kijai/flux-fp8/discussions/7#66ae0455a20def3de3c6d476)

### clip_vision
- [ViT-L-14-BEST-smooth-GmP-TE-only-HF-format](https://huggingface.co/zer0int/CLIP-GmP-ViT-L-14/blob/main/ViT-L-14-BEST-smooth-GmP-TE-only-HF-format.safetensors)
- [t5xxl_fp8_e4m3fn_scaled](https://huggingface.co/comfyanonymous/flux_text_encoders/blob/main/t5xxl_fp8_e4m3fn_scaled.safetensors)

### vae
- [ae](https://huggingface.co/Comfy-Org/Lumina_Image_2.0_Repackaged/blob/main/split_files/vae/ae.safetensors)

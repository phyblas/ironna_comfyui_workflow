# 简单说明

用wan2.2模型来放大图片以及改善画质。

# 需要插件

- [nunchaku.tech / ComfyUI-nunchaku](https://github.com/nunchaku-tech/ComfyUI-nunchaku)
- - NunchakuFluxDiTLoader

- [kijai / ComfyUI-Florence2](https://github.com/kijai/ComfyUI-Florence2)
- - DownloadAndLoadFlorence2ModelMultiGPU
- - Florence2Run

- [ClownsharkBatwing / RES4LYF](https://github.com/ClownsharkBatwing/RES4LYF)
- - ClownsharKSampler_Beta

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### unet
- [wan2.2_t2v_low_noise_14B_fp8_scaled](https://huggingface.co/Comfy-Org/Wan_2.2_ComfyUI_Repackaged/blob/main/split_files/diffusion_models/wan2.2_t2v_low_noise_14B_fp8_scaled.safetensors)

### lora
- [wan2.2_t2v_lightx2v_4steps_lora_v1.1_low_noise.safetensors](https://huggingface.co/Comfy-Org/Wan_2.2_ComfyUI_Repackaged/resolve/main/split_files/loras/wan2.2_t2v_lightx2v_4steps_lora_v1.1_low_noise.safetensors)

### clip_vision
- [umt5_xxl_fp8_e4m3fn_scaled](https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged/blob/main/split_files/text_encoders/umt5_xxl_fp8_e4m3fn_scaled.safetensors)

### vae
- [wan_2.1_vae](https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged/blob/main/split_files/vae/wan_2.1_vae.safetensors)

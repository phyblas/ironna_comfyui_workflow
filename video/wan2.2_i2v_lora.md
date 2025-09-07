# 简单说明

用wan2.2来做视频。输入是最开始的1张图片。还用lora来减少步数而很快。

# 需要模型

### unet
- [wan2.2_i2v_high_noise_14B_fp8_scaled](https://huggingface.co/Comfy-Org/Wan_2.2_ComfyUI_Repackaged/blob/main/split_files/diffusion_models/wan2.2_i2v_high_noise_14B_fp8_scaled.safetensors)
- [wan2.2_i2v_low_noise_14B_fp8_scaled](https://huggingface.co/Comfy-Org/Wan_2.2_ComfyUI_Repackaged/blob/main/split_files/diffusion_models/wan2.2_i2v_low_noise_14B_fp8_scaled.safetensors)

### clip_vision
- [umt5_xxl_fp8_e4m3fn_scaled](https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged/blob/main/split_files/text_encoders/umt5_xxl_fp8_e4m3fn_scaled.safetensors)

### vae
- [wan_2.1_vae](https://huggingface.co/Comfy-Org/Wan_2.1_ComfyUI_repackaged/blob/main/split_files/vae/wan_2.1_vae.safetensors)

### lora
- [wan2.2_i2v_lightx2v_4steps_lora_v1_high_noise](https://huggingface.co/Comfy-Org/Wan_2.2_ComfyUI_Repackaged/blob/main/split_files/loras/wan2.2_i2v_lightx2v_4steps_lora_v1_high_noise.safetensors)
- [wan2.2_i2v_lightx2v_4steps_lora_v1_low_noise](https://huggingface.co/Comfy-Org/Wan_2.2_ComfyUI_Repackaged/blob/main/split_files/loras/wan2.2_i2v_lightx2v_4steps_lora_v1_low_noise.safetensors)
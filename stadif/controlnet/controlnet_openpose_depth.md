# 简单说明

同时使用controlnet的openpose和depth map。用已经预处理准备好的openpose和depth map图片。按照[官方的例子](https://github.com/comfyanonymous/ComfyUI_examples/blob/master/controlnet/mixing_controlnets.png)

# 需要插件

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### controlnet
- [control_v11p_sd15_openpose](https://huggingface.co/lllyasviel/control_v11p_sd15_openpose)
- [control_v11f1p_sd15_depth](https://huggingface.co/lllyasviel/control_v11f1p_sd15_depth)
# 简单说明

用[3d-pose-editor](https://github.com/hinablue/ComfyUI_3dPoseEditor)插件来同时做controlnet的openpose和depth map。depth map是用来控制手部的姿势。可以做出漂亮不崩坏的手指。

# 需要插件

- [hinablue / ComfyUI_3dPoseEditor](https://github.com/hinablue/ComfyUI_3dPoseEditor)
- - Hina.PoseEditor3D

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### controlnet
- [control_v11p_sd15_openpose](https://huggingface.co/lllyasviel/control_v11p_sd15_openpose)
- [control_v11f1p_sd15_depth](https://huggingface.co/lllyasviel/control_v11f1p_sd15_depth)

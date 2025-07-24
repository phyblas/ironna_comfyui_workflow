# 简单说明

通过[张吕敏](https://huggingface.co/lllyasviel)提出的nf4和[CheckpointLoaderNF4节点](https://github.com/comfyanonymous/ComfyUI_bitsandbytes_NF4)来用flux来做文生图。

# 需要插件

- [AlekPet / ComfyUI_Custom_Nodes_AlekPet](https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet)
- - DeepTranslatorCLIPTextEncodeNode

- [Goktug / comfyui-saveimage-plus](https://github.com/Goktug/comfyui-saveimage-plus)
- - SaveImagePlus

# 需要模型

### checkpoint
- [flux1-dev-bnb-nf4-v2](https://huggingface.co/lllyasviel/flux1-dev-bnb-nf4/tree/main)
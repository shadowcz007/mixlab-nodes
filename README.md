# mixlab-nodes
new GUI for stable difffusion &amp; LLM

使用教程：

## 1 填写comfyui和本地LLM服务地址

![image](https://github.com/shadowcz007/mixlab-nodes/assets/12645064/361c04a8-7383-4c79-8ce0-3ffc38b56287)


本地LLM服务地址（参考指南）
私有化本地GPT：万字使用指南

我使用的是LM studio 和gemma
如何使用谷歌的gemma新模型？


## 2 加载创建好的工作流

![image](https://github.com/shadowcz007/mixlab-nodes/assets/12645064/7fabcf34-fd4c-4255-b34e-ebc088646f01)

![image](https://github.com/shadowcz007/mixlab-nodes/assets/12645064/3487858a-8a69-4701-98eb-9412e70d63f8)


（需使用mixlab- node插件的Appinfo节点创建）
安装并更新comfyui-mixlab-nodes到最新版0.17.1

这里我创建了2个用于story模式：
text-to-image
image-to-image

需要注意，输入和输出都分别都需要为1个节点。


## 3 App模式

![image](https://github.com/shadowcz007/mixlab-nodes/assets/12645064/5b0eda0c-e31e-45e7-9b1b-a700051756b8)



App模式是大家熟悉的ComfyUI-mixlab-nodes 的功能：workflow-to-app。


## 4 输入故事主题词

![image](https://github.com/shadowcz007/mixlab-nodes/assets/12645064/58b21aa7-ef44-441c-bec4-7fb80c6eccbd)

打开story模式，story模式是这次主要更新的，一种专注于创作图文的极简模式。


## 5 修改分镜

![image](https://github.com/shadowcz007/mixlab-nodes/assets/12645064/4aca874d-f989-4d85-8a8d-08c9611bc53d)

![image](https://github.com/shadowcz007/mixlab-nodes/assets/12645064/72b174f4-2ff5-4a7f-ae65-9d7f36d55811)


调整提示词、文本生成图像、图像风格迁移


## 6 预览图文故事

![image](https://github.com/shadowcz007/mixlab-nodes/assets/12645064/314b4b26-3a0a-4d66-a3b8-382f1f5ed2a5)


## 7 待续
欢迎讨论后续的进一步高级功能

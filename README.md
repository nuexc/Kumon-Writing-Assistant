# Kumon-Writing-Assistant
这是一个基于InternLM的Tutorial(https://github.com/InternLM/Tutorial) 项目实现的公文写作助手语言模型，主要实现以下几点功能：
1、按照输入的公文写作要求，输出一篇或者多篇符合规范的公文
2、能够为用户解疑关于公文写作的种类、规范、避坑点等信息
3、能够对用户输入的公文进行合理扩写和改写

最后非常感谢上海人工智能实验室开源的InternLM项目，对于新手非常友好，各位对人工智能感兴趣的小伙伴可以关注其官网(https://internlm.intern-ai.org.cn/) 和开源项目(https://github.com/InternLM) ，欢迎大家也来参加书生大模型实战营项目(https://github.com/InternLM/Tutorial) 
![image](https://github.com/user-attachments/assets/53daa266-564e-442d-818e-364cfc2d303f)

经过十多天的学习和探索，在翻阅了大量资料之后，终于是弄出来了第一版，v1版本主要有三个功能：1、解疑公文相关问题 2、按照要求代写公文 3、对用户的公文进行打分。功能2、3主要是靠prompt+LLM实现的，功能1的实现则是通过运用RAG（检索增强生成）技术检索知识库。下面是公文写作助手的部分效果截图：
![公文写作助手_v1（未启用RAG）_00](https://github.com/user-attachments/assets/21c7298e-f12c-4acc-a4e4-95f4f236482f)
![公文写作助手_v1（已启用RAG）_00](https://github.com/user-attachments/assets/e0d7732c-a7c7-4c88-84a2-fef9eafc50e5)


鉴于本人技术有限，v1版本的效果只是部分达到预期，实际上代写公文功能才是最核心的功能，后续会针对这块下功夫，同时也会扩展知识库的内容。

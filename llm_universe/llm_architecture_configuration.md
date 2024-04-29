| 模型名称 | 架构类型 | 注意力机制 | 位置编码 | 归一化 | 激活函数 | 模型大小 | 上下文窗口大小 | 词表大小 | 机构  |
| ---- | ---- | ----- | ---- | --- | ---- | ---- | ------- | ---- | --- |
| BERT | encoder-only | MHA | Learnable | LayerNorm post | GeLU | 110M 340M | 512 | 21K 31K | Google |
| Baichuan | decoder-only | MHA | RoPE ALiBi | RMSNorm pre | SwiGLU | 7B 13B | 4K | 64K | 百川 |
| Baichuan2 | decoder-only | MHA | RoPE ALiBi | RMSNorm pre | SwiGLU | 7B 13B | 4K | 126K | 百川 |
| ChatGLM | GLM | MHA | RoPE | LayerNorm pre | GeGLU | 6B | 2K | 130K | 智谱 |
| ChatGLM2 | decoder-only | MQA | RoPE | RMSNorm pre | SwiGLU | 6B | 8k 32K | 65K | 智谱 |
| ChatGLM3 | decoder-only | MQA | RoPE | RMSNorm pre | SwiGLU | 6B | 8k 32K 128k | 65K | 智谱 |
| ChatRWKV | RNN | Time-mix | Unknown | LayerNorm pre | Square ReLU | 3B 7B 14B | 8k | 66K | 元始智能 |
| Command-R | decoder-only | MHA GQA | RoPE | LayerNorm pre | SwiGLU | 35B 104B | 128k | 256K | Cohere |
| DeepSeek | decoder-only MoE | MHA GQA | RoPE | RMSNorm pre | SwiGLU | 7B 16B 67B | 4K | 102K | 深度求索 |
| DeepSeek-Coder | decoder-only | GQA | RoPE | RMSNorm pre | SwiGLU | 1.3B 6.7B 7B 33B | 16K | 32K | 深度求索 |
| Falcon | decoder-only | MQA | RoPE | LayerNorm pre | GeLU | 1B 7B 40B 180B | 2K | 65K | TII |
| GPT | decoder-only | MHA | Learnable | LayerNorm pre | GeLU | 117M | 512 | 40K | OpenAI |
| GPT2 | decoder-only | MHA | Learnable | LayerNorm pre | GeLU | 124M 355M 774M 1.5B | 1024 | 50K | OpenAI |
| Gemma | decoder-only | MHA | RoPE | RMSNorm pre | GeGLU | 2B 7B | 8k | 256K | Google |
| Grok-1 | decoder-only MoE | MHA | RoPE | RMSNorm SandwichNorm | GeGLU | 314B | 8k | 128K | X |
| InternLM | decoder-only | MHA | RoPE | RMSNorm pre | SwiGLU | 7B 20B | 4K | 103K | 上海人工智能实验室 |
| InternLM2 | decoder-only | GQA | RoPE | RMSNorm pre | SwiGLU | 1.8B 7B 20B | 32K 200K | 93K | 上海人工智能实验室 |
| LLaMA | decoder-only | MHA | RoPE | RMSNorm pre | SwiGLU | 7B 13B 33B 65B | 2K | 32K | Meta |
| LLaMA-2 | decoder-only | MHA GQA | RoPE | RMSNorm pre | SwiGLU | 70B 7B 13B | 4K | 32K | Meta |
| LLaMA-3 | decoder-only | GQA | RoPE | RMSNorm pre | SwiGLU | 8B 70B | 8k | 128K | Meta |
| Mistral/Mixtral | decoder-only MoE | GQA SWA | RoPE | RMSNorm post | SwiGLU | 7B 8x7B 8x22B | 32K 64K | 32K | Mistral |
| OLMo | decoder-only | MHA | RoPE | LayerNorm pre | SwiGLU | 1B 7B | 2K | 50K | AI2 |
| OpenELM | decoder-only | GQA | RoPE | RMSNorm pre | SwiGLU | 270M 450M 1.1B 3B | 2K | 32K | Apple |
| Phi-3 | decoder-only | GQA | RoPE | RMSNorm pre | SwiGLU | 3.8B | 4K 128k | 32K | Microsoft |
| Qwen | decoder-only | MHA SWA | RoPE | RMSNorm pre | SwiGLU | 1.8B 7B 14B 72B | 32K | 152K | 阿里巴巴 |
| Qwen1.5 | decoder-only MoE | GQA SWA FA | RoPE | RMSNorm pre | SwiGLU | 0.5B 1.8B 4B 7B 14B 32B 72B | 32K | 152K | 阿里巴巴 |
| T5 | encoder-decoder | MHA | T5 Relative | LayerNorm pre | GeLU | 60M 220M 770M 3B 11B | 512 | 32K | Google |
| XVERSE | decoder-only MoE | MHA | RoPE | RMSNorm pre | SwiGLU | 7B 13B 65B | 8k 16K 256K | 101K | 元象 |
| Yi | decoder-only | GQA | RoPE | RMSNorm pre | SwiGLU | 6B 9B 34B | 4K 200K | 64K | 零一万物 |
| Yuan | decoder-only | LFA | RoPE | RMSNorm pre | SwiGLU | 2B 51B 102B | 4K | 135K | 浪潮源 |

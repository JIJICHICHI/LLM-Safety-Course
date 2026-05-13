# 大模型越狱攻防实验 (Jailbreak Attack & Defense)
 
## 项目简介

本项目为课程作业，实现了针对开源大语言模型 Qwen2.5-1.5B-Instruct 的黑盒攻击（PAIR）、白盒攻击（GCG）以及困惑度防御，并评估攻击成功率（ASR）和防御有效性。

**重要声明**：所有实验仅在本地开源模型上进行，危险输出已做脱敏处理，对抗性后缀不公开传播。详见 `RESPONSIBLE_USE.md`。

## 环境要求

- Python 3.8+
- PyTorch (支持 CUDA 或 CPU)
- Transformers

## 快速开始

### 1. 安装依赖

```bash
pip install torch transformers

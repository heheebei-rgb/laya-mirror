# Laya 镜像 (convaiinnovations/laya)

HuggingFace [convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya) 的完整镜像（Apache-2.0）。

**Laya**: 多语言非自回归 System-1 决策模型（ModernBERT-large 421M / mmBERT-base 322M），单次前向 (~33ms) 输出带校准概率的 typed answers，RLCD 训练。三个 checkpoint 全集：英文 / 多语言(100+语言) / typed-decisions。

**内网下载**: Code → Download ZIP（或 main.zip 直链），解压后 `python3 merge_and_verify.py` 自动重建三个 model.safetensors 并做 sha256 校验（纯标准库，无需联网）。
**数据日期**: 2026-09-20 从 hf-mirror.com 下载。
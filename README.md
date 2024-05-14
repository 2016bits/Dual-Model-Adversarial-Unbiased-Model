# Dual-Model-Adversarial-Unbiased-Model
## 算法主要思想：首先计算由claim和evidence共同影响的模型ce，然后计算仅有claim影响的有偏模型c-only，使用 ce 减去 c-only得到无偏模型结果。可以考虑类似对抗的思想：先单独优化有偏模型，使其尽可能仅利用claim做出预测；然后固定有偏模块，优化整体模型，再利用整体模型减去有偏模型的结果。

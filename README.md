# pytorch-quantization-demo
A simple network quantization demo using pytorch from scratch. This is the code for my [tutorial](https://jermmy.github.io/2020/06/13/2020-6-13-network-quantization-1/) about network quantization written in Chinese. 

network **without** BN:
|      No-BN     | bit |  1  |  2  |  3  |  4  |  5  |  6  |  7  |  8  |            |
|:--------------:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:----------:|
|  Post_training | Acc | 10% | 36% | 71% | 93% | 98% | 98% | 98% | 98% |            |
| training_aware | Acc | 10% | 25% | 74% | 97% | 98% | 99% | 99% | 98% |   lr=0.04  |
| training-aware | Acc | 10% | 32% | 74% | 95% | 98% | 98% | 98% | 98% |  lr=0.001  |
| training-aware | Acc | 10% | 30% | 73% | 95% | 98% | 98% | 98% | 98% | lr=0.00001 |

network **with** BN

感兴趣的读者欢迎关注原作者知乎专栏：[AI小男孩](https://zhuanlan.zhihu.com/c_1258047709686231040)




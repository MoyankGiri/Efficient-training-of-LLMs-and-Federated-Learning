# Efficient-training-of-LLMs-and-Federated-Learning
## ABSTRACT
Efficient training of deep learning models and Large Language Models (LLMs) is critical
for scalable and privacy-preserving artificial intelligence, yet existing methods struggle with
high computational costs, excessive communication overhead, and poor adaptation to domainspecific
challenges. This work addresses these limitations through two novel contributions,
each targeting a unique aspect of efficient model training.<br><br>
First, an Efficient Hybrid Split Federated Learning Framework is proposed, which optimizes
decentralized learning by balancing global generalization and local personalization. This
is achieved through a gradient norm-based dynamic selection strategy, coupled with activation
caching to minimize communication overhead. Extensive experiments on diverse datasets,
including ISIC2019, CIFAR10, FMNIST, VLCS, PACS, and OfficeHome, demonstrate an average
of 96× reduction in computation costs and a 4.5× reduction in communication traffic,
while maintaining strong test-time performance across heterogeneous data distributions.<br><br>
Second, a Dynamic Fine-tuning Strategy for LLMs is developed, addressing the high computational
demands of fine-tuning large models. By employing selective layer training using
gradient-based criteria, combined with parameter-efficient techniques like LoRA and caching
mechanisms, the approach achieves a 10% reduction in fine-tuning time and significantly lowers
GPU memory utilization, making LLM fine-tuning more resource-efficient.<br><br>
Together, these contributions provide a scalable, resource-efficient, and domain-adaptive solution
for training and deploying deep learning models and LLMs, pushing the boundaries of
efficient AI.<br><br>
**Keywords**: Federated Learning, Split Learning, Large Language Models, Efficient Fine-tuning,
Communication Reduction, Computation Reduction.

# DeepLense (ml4sci) Evaluation Tasks
Chenguang Guan's solutions to ml4sci GSoC evaluation tests (DeepLense)

There are three files.

1. Solution to Task 1 (one file): Deeplense_task1_classification.ipynb
2. Solution to Additional Task (Vision Transformer) (two files): DeepLense_Specific_Task_Transformers.ipynb ; DeepLense_Specific_Task_Transformers_Bonus.ipynb

Task1 includes:
1. Pre-trained models: ResNet-18, VGG-16, AlexNet
2. Non pre-trained models: MLP (one hidden layer NN), CNN (LeNet), Simplified ReNet (with two residual blocks)

Specific task includes:

DeepLense_Specific_Task_Transformers.ipynb: Vision Transformer (ViT), Swin Transformer

DeepLense_Specific_Task_Transformers_Bonus.ipynb: I introduce a DIY version of ViT, and discuss the post-norm and pre-norm. I also implement the MLP-mixer model.

1. MLP-mixer has a really good performance! And the computaional efficiency is really good.
2. The pre-norm ViT learn nothing
3. The post-norm ViT can learn something, but the efficiency is poor.

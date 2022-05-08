Based on https://github.com/junyuseu/pytorch-cifar-models

Cutout code from: https://arxiv.org/abs/1708.04552
Maxup code from: Chengyue Gong and the paper https://openaccess.thecvf.com/content/CVPR2021/html/Gong_MaxUp_Lightweight_Adversarial_Training_With_Data_Augmentation_Improves_Neural_Network_CVPR_2021_paper.html

Refer to commands for what was run and also the corresponding textfile output

All files use cutout and resnet110

MODIFICATION comments label the parts of the main python file changed from junyuseu/pytorch-cifar-models

main-10c.py
- Cifar10
- **Cutout**: holes 1 and length 16
- Result: resnet110_cifar10-cutout.txt

main-10cm.py
- Cifar10
- **Cutout**: holes 1 and length 16 and **MaxUp**
- Result: resnet110_cifar10-cutout-maxup.txt

main-100c.py
- Cifar100
- **Cutout**: holes 1 and length 8
- Result: resnet110_cifar100-cutout.txt

main-100cm.py
- Cifar100
- **Cutout**: holes 1 and length 8 and **Maxup**
- Result: resnet110_cifar100-cutout-maxup-combined.txt
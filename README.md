Based on https://github.com/junyuseu/pytorch-cifar-models

Cutout code from: https://arxiv.org/abs/1708.04552
Maxup code from: Chengyue Gong and the paper https://openaccess.thecvf.com/content/CVPR2021/html/Gong_MaxUp_Lightweight_Adversarial_Training_With_Data_Augmentation_Improves_Neural_Network_CVPR_2021_paper.html

Refer to commands for what was run and also the corresponding textfile output

All files have cutout and resnet110

MODIFICATION comments label the parts of the main python file changed from junyuseu/pytorch-cifar-models

main.py
- Cifar10
- Cutout: holes 1 and length 16
- Result: resnet110_cifar10-cutout.txt

main-andy.py
- Cifar10
- Cutout: holes 1 and length 16
- Maxup
- Result: cutout-maxup.txt

main-withcutoutcifar100.py
- Cifar100
- Cutout: holes 1 and length 8
- Result: cutout100.txt

main-withcutoutcifar100-withmaxup.py
- Cifar100
- Cutout: holes 1 and length 8
- Maxup
- Result: cutoutmaxup100.txt
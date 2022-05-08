Based on https://github.com/junyuseu/pytorch-cifar-models

Refer to commands for what was run and also the corresponding textfile output

All files have cutout and resnet110

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
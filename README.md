# vendor_rpi

## 介绍

该仓库托管ISCAS移植的产品：树莓派系列产品，主要是树莓派3B(Raspberry Pi 3 Model B)和树莓派4B(Raspberry Pi 4 Model B)

## 目录

```
vendor/rpi
├── README.md
└── common                 # 通用路径           
    ├── bluetooth           
    ├── custom_conf        
    ├── default_app_config 
    ├── image_conf          
    ├── resourceschedule      
    └── sample
└── rpi3                   # 树莓派3B开发板(未适配) 
└── rpi4                   # 树莓派4B开发板
   ├── audio
   ├── etc
   ├── hal
   ├── hdf_config
   ├── image_conf
   ├── power_config
   ├── preinstall-config
   ├── security_config
   ├── updater_config
   └── product.gni

```

## 贡献


[如何参与](https://gitee.com/openharmony/docs/blob/HEAD/zh-cn/contribute/%E5%8F%82%E4%B8%8E%E8%B4%A1%E7%8C%AE.md)


## 相关仓

* [device/board/iscas](https://gitee.com/openharmony-sig/device_board_iscas)
* [device/soc/broadcom](https://gitee.com/openharmony-sig/device_soc_broadcom)
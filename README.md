
gitee上的官网见https://gitee.com/opengisbook/Fine3399-Official

gitee上的教程https://gitee.com/xiayang0521/berrybaseboard-test

github由于访问较难仅作为入口使用。

# Fine3399资料

* 本页面无图，不杀猫 *

## 1. 什么是Fine3399

一个基于SW799核心板的底板，由莓（rumu3f）设计，游戏机大佬（　）提供部分技术支持。

由于在一些项目中sw799、bozz等名称已经被SW7990系列底板中的某一款占用，为防冲突这一款底板暂时命名为Fine3399。

### 1.1 版本清单

+ 2022年的第一批

由莓量产，提供了配套的金属外壳和小屏幕。

+ 2023年6月的第二批

由null量产，无配件，基本与2022年版本完全一致，配件在合理范围内进行了cost down。背面贴纸上有版本和序列号、QC情况和资料二维码（本页面）。

版本号格式为：Fine3399 ver 1.0 block 1

序列号格式为：[产品类型][是否SMT][出厂编号][验证码]

a. 产品类型

ES：工程样品，不享受质保

DK：开发者套件，不享受质保

SE：正式售卖品，享受有限质保

LE：正式售卖品，不享受质保

b. 是否SMT

FSMT：基本全SMT

PSMT：部分SMT，作为开发者套件提供

NSMT：空板

c. 出厂编号

各类都是从00001开始

QC情况格式为：□HDMI □LAN1 □LAN2 □NVME

### 1.2 硬件资源

### 1.3 可用固件

### 1.4 开发资料

提供dts，见[fine3399.dts](./fine3399.dts)。未来预计原理图和项目开源。

## 2. 使用教程

这里不提供新手入门教程，请参阅[xiayang0521的gitee](https://gitee.com/xiayang0521/berrybaseboard-test)

## 3. 已知问题

### 3.1 发热问题

默认固件是针对CNC盒子主动散热版的，主频较高，建议选择合适的版本。

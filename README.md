# HFSS-GUI-Scripts
Just for intergrated circuit design project aligned with HFSS software. With GUI based on IronPython, you can save a lot of time to repeat the same operation.

本脚本用于HFSS联合Cadence、ADS等软件进行芯片级电磁仿真，可以省去大量重复工作，提高效率。

## Ahead of all
This script is based on Ironpython(Python 2.0+) and .Net Framework 2.0+, so you should confirm your computer is along with these enverionment above. And you should confirm that the version of HFSS is 16(2015)or higher version.

As for the confidential processing parameters, some data has been removed from the backstage. You'd better add these parameters according to your design. Or you can refer to the script GUI frame and wrapped functions, and deliver your own scripts.

脚本基于Ironpython(Python2.0+)和.Net Framework 2.0+，使用前先确保电脑已配备上述环境。同时HFSS软件版本高于HFSS16(2015)。

由于部分工艺参数保密，所以后台已经移除工艺数据，使用前最好按照自己所使用的工艺进行参数补充。或者可以参考本脚本的图形界面框架以及部分已经封装过的函数，开发自己的脚本来使用。

## Usage
- New/Opne Project -> New/Open HFSS Design -> Menu-Tools -> Run scripts -> Choose xxx.py

## ChangeLog
### [Ver 1.2.1] - 2017-12-12
#### Fixed:
- 修复Panel3金属材料无法生成bug

#### Refactored:
- 优化Panel1生成介质盒的显示问题

### [Ver 1.2.0] - 2017-11-24
- Added:
1. Panel3: Create_Metal_Material

[Ver 1.1.2] --20171124
--- Added:
        1. Function: AddMaterial()
        2. Create_Media_Box Panel 材料生成
        3. Create_Media_Box Panel 参数报错窗口
--- Refactored:
        1. 优化窗口最大化及拖拽问题

[Ver 1.1.1] --20171120
--- Refactored:
        1. 优化界面
--- Fixed:
        1. 修复脚本卡顿问题

[Ver 1.1.0] --20171120
--- Added：
        1. Function: SetModelUnits()
        2. Panel2: Scale_Unit
--- Changed:
        1. Media_Box单位可选择，不再默认为'um'

[Ver 1.0.0] --20171120
--- Added：
        1. Function: CreateBox()
        2. Panel1: Create_Media_Box
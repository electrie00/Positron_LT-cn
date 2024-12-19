# positron lt-cn

1. 国内可制造，任何零件均可在国内买到
2. 价格合理，目前价格大约在1500~2000元左右



## 改动点 - （添加了部分positron v3.2的新设计）： 

  1. 后惰轮张紧块 —— lt原版的张紧块使用4个小惰轮倾斜安装，无法承受皮带张紧力，会被逐渐拉歪，最终导致皮带脱轨。 使用v3.2的设计两个大惰轮可以很好的解决这个问题，需要注意的是，v3.2的惰轮是cnc做的，而此改版lt使用的是成品惰轮，淘宝有卖

  2. 挤出机 —— lt原版挤出机基于bmg，我实际使用时有明显挤出不足的问题。使用v3.2的orbiter2.0挤出机，仅修改了安装孔位，内部挤出结构与v3.2保持一致。 同时扩大了rgb灯孔位，以便折叠时刚好把挤出机卡入凹槽

  3. 热床接口 —— lt原版热床的磁吸接口强度不够，有时连接不稳，再加上lt原版热床支架的热床夹持结构不稳。整个热床可以说是摇摇欲坠。一旦磁吸接口虚接产生火花，就会导致热床接口损坏（亲身经历）。  使用v3.2的金手指连接接口，非常稳固。以及v3.2的热床支架，体积更小，夹持更稳，调平也更方便（lt原版的调平螺丝在下面，很别扭）。  需要注意的是，准确来说此改版lt仅使用了金手指接口，并没有pcb，因此安装需要依赖胶水固定，以及接线需要做好绝缘，因为接线点与线轨金属滑块紧贴，容易短路

  4. ito热床 —— ito导电玻璃，整块玻璃均导电，发热更加均匀。两根长导线连接热床对边边缘作电极，分别连接24v正负极便可发热，中间区域是完全透明的整块玻璃。使用淘宝购买ito玻璃加上可在嘉立创制作的pcb,便可自制，这样就不用去国外买热床了，自己做的价格其实比淘宝的成品热床便宜。不建议使用淘宝的成品热床，那个并不是ito热床，而是普通的导线粘贴在玻璃上。这个导线会干扰positron的红外调平模块（ir probe），导致有大量死区无法触发限位，影响z归位以及网床探测

  5. 主体框架 —— 原版lt使用1010型材搭建框架，但这个在国内是买不到的，基本可以说没有办法。此改版lt修改为整体cnc，价格还行300以内吧，这也是没有办法


## 与lt版本和V3.2版本相比

 1. 用cnc解决了lt 1010铝型材买不到的问题，同时添加了v3.2的新设计，弥补了lt的bug，使用体验大幅上升
 2. 比v3.2容易制造，至少不存在买不到特殊零件的问题了，并且是lt集成电源的,但体积就会比v3.2大一些



## 注意

  1.此工程的文件仍在整理，文档依然还有许多没写
  
  2.此版本没有为打印机添加触摸屏幕，但保留了原版lt安装屏幕的孔位，有需要可以自己参考lt安装

  
<br>

## License

Positron LT is a 3D printer design that is fully open source, which means anyone can use, modify, and share the design. We use a dual-licensing model to ensure that the project remains open source while providing a separate license for entities who want to use the design for financial gain.

### Licensing Explained

- **For personal, educational, and non-commercial use**: The design is available under the GNU General Public License v3.0 (GPLv3). This means you can use, modify, and share the design freely, as long as you also share any changes you make under the same dual-licensing model. This ensures that the open-source nature of the project is maintained. See the [GNU General Public License v3.0 (GPLv3)](LICENSE) file for the full text of the GPLv3.

- **For commercial use or financial gain**: We offer a custom commercial license for companies or individuals who want to use the design for commercial purposes or financial gain. This separate license includes a small royalty fee, which helps support the project. See the [Commercial License](LICENCE-COMMERCIAL) file for details.

### Contributing

We welcome and appreciate contributions to Positron LT! By contributing to this project, you agree that your contributions will be licensed under the dual-licensing model, with the GPLv3 applying to non-commercial use and contributions, and the commercial license applying for commercial use or financial gain.

### License Summary

Positron LT uses a dual-licensing model:

- The GNU General Public License v3.0 (GPLv3) for personal, educational, and non-commercial use and contributions. See the [GNU General Public License v3.0 (GPLv3)](LICENSE) file.
- A commercial license for commercial use or financial gain. See the [Commercial License](LICENCE-COMMERCIAL) file.


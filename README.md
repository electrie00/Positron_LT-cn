<div align="center">
  
# Positron LT-cn

<br>
<img src="参考图片和视频/Positron LT-cn 渲染图.png" width="350" height="350">

<br>


</div>

<br>

<br>

1. 国内可制造，任何零件均可在国内买到
2. 价格合理，目前价格大约在1500~2000元左右
3. 原版 LT 用户也可以很容易的升级这个版本，解决 LT 原版的问题
   
<br>


## - 改动点   （添加了部分 Positron V3.2 的新设计）： 

  1. **后惰轮张紧块** —— LT 原版的张紧块使用4个小惰轮倾斜安装，无法承受皮带张紧力，会被逐渐拉歪，最终导致皮带脱轨。 使用 V3.2 的设计两个大惰轮可以很好的解决这个问题，需要注意的是，V3.2 的惰轮是 CNC 做的，而此改版 LT 使用的是与 V3.2 参数相似成品惰轮，淘宝有卖

  2. **挤出机** —— LT 原版挤出机基于 BMG，我实际使用时有明显挤出不足的问题。使用 V3.2 的 Orbiter2.0 挤出机，仅修改了安装孔位，内部挤出结构与 v3.2 保持一致。 同时扩大了 RGB 灯孔位，以便折叠时刚好把挤出机卡入凹槽

  3. **热床接口** —— lt原版热床的磁吸接口强度不够，有时连接不稳，再加上 LT 原版热床支架的热床夹持结构不稳。整个热床可以说是摇摇欲坠。一旦磁吸接口虚接产生火花，就会导致热床接口损坏（ 亲身经历 ）。  使用 V3.2 的金手指连接接口，非常稳固。以及 V3.2 的热床支架，体积更小，夹持更稳，调平也更方便（ LT 原版的调平螺丝在下面，很别扭 ）。  需要注意的是，准确来说此改版lt仅使用了金手指接口，并没有 PCB，因此安装需要依赖胶水固定，以及接线需要做好绝缘，因为接线点与线轨金属滑块紧贴，容易短路

  4. **ITO 热床** —— ITO导电玻璃，整块玻璃均导电，发热更加均匀。两根长导线连接热床对边边缘作电极，分别连接 24V 正负极便可发热，中间区域是完全透明的整块玻璃。使用淘宝购买 ITO 玻璃加上可在嘉立创制作的 PCB，便可自制，这样就不用去国外买热床了，自己做的价格其实比淘宝的成品热床便宜。不建议使用淘宝的成品热床，那个并不是 ITO 热床，而是普通的导线粘贴在玻璃上。这个导线会干扰 Positron 的红外调平模块（ IR Probe ），导致有大量死区无法触发限位，影响 Z 归位以及网床探测

  5. **主体框架** —— 原版LT使用1010型材搭建框架，但这个在国内是买不到的，基本可以说没有办法。此改版 LT 修改为整体 CNC，价格还行 300 以内吧，这也是没有办法
  
  6. **皮带固定块** —— LT 原版的皮带固定块，仅仅靠设计的弯曲凹槽卡入皮带固定，也就是仅靠摩擦力固定，但凡皮带张紧一点，皮带便会脱落。而 V3.2 的皮带固定块改动太太，无法移植，并且 V3.2 的固定块设计也不算优秀。所以此改版 LT 在原版固定块基础上增加了 0.5mm 小孔，可以使用 0.5mm 的钢针插入，将皮带和固定块串在一起，就像串烧烤一样
     
<br>

## - 与 LT 版本和 V3.2 版本相比

 1. 用 CNC 解决了 LT 1010铝型材买不到的问题，同时添加了 V3.2 的新设计，也改进了大部分 LT 的 bug，使用体验大幅上升
 2. 比 V3.2 容易制造，至少不存在买不到特殊零件的问题了，并且是lt集成电源的,但体积就会比 V3.2 大一些。同时价格也比 V3.2便宜一倍
<br>


## - 注意

  1.此工程的文件仍在整理，文档依然还有许多没写
  
  2.此版本没有为打印机添加触摸屏幕，但保留了原版 LT 安装屏幕的孔位，有需要可以自己参考 LT 安装

  3. X，Y，Z 轴的步进电机依然不太好买，具体参数为 42 步进电机20mm厚15mm轴长。而我目前买的电机是 20mm 轴长，装上去才发现高了 5mm 会阻挡打印头移动，目前解决方案是在电机安装孔垫矮了 5mm，便可解决问题。其实也证明轴长 15~20mm 都是可以的，自行添加垫片调整高度即可


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
<br>  



# 感谢Positron LT 和 Position 3D

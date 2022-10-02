# 恒定电流（电磁场与电磁波第三章作业）

1. 将半径为$a$的半个导电球刚好埋入电导率为$\sigma$的大地中，如下图所示。求接地电阻。
   ![图1](pic/zjooc03-1.png)
   ![tu](https://raw.githubusercontent.com/SpongeBob-hmbb/pic-in-markdown/main/zjooc03-1.png)
   ![tttuuu](https://SpongeBob-hmbb.github.io/pic-in-markdown/images/zjooc03-1.png)
   **解**
   设从地线流出的电流为$I$，在大地中作与导体球同心，半径为$r$的半球面，在此半球面上电流密度相同，显然满足关系
   $$
   J=\frac{I}{2\pi r^2}
   $$
   电场强度为：
   $$
   E=\frac{J}{\sigma}=\frac{J}{2\pi\sigma r^2}
   $$
   导电球的电位为：
   $$
   V=\displaystyle\int_{-\infty}^{a}E\mathrm{d}r=\frac{I}{2\pi\sigma a}
   $$
   因此导电球的接地电阻为：
   $$
   R=\frac{V}{I}=\frac{1}{2\pi\sigma a}
   $$
2. 圆球形电容器内导体半径为$a$，外导体内半径为$c$，内外导体之间填充两层介电常数分别为$\varepsilon_1$、$\varepsilon_2$，电导分别为$\sigma_1$、$\sigma_2$的非理想介质，两层非理想介质分界面半径为$b$，如果内外导体间电压为$V$，求圆球形电容器的电容及漏电导。

   **解**
   此圆球形电容器的电容及漏电导是并串联的形式如图所示。
   ![图2](pic/zjooc03-2.png)
   $$
   C_1=\cfrac{4\pi\varepsilon_1}{\cfrac{1}{a}-\cfrac{1}{b}}\quad C_2=\cfrac{4\pi\varepsilon_2}{\cfrac{1}{b}-\cfrac{1}{c}}
   $$
   $$
   G_1=\cfrac{4\pi\sigma_1}{\cfrac{1}{a}-\cfrac{1}{b}}\quad G_2=\cfrac{4\pi\sigma_2}{\cfrac{1}{b}-\cfrac{1}{c}}
   $$

3. 平板电容器两导电平板之间为三层非理想介质，厚度分别为$d_1$、$d_2$、$d_3$，电导率分别为$\sigma_1$、$\sigma_2$、$\sigma_3$，平板面积为$S$，如果给平板电容器加电压$V$，求电容器的漏电导。

   **解**

   $$
   E_1=\frac{\sigma_2\sigma_3 V}{\sigma_2\sigma_3 d_1+\sigma_1\sigma_3 d_2+\sigma_1\sigma_2 d_3}
   $$
   流过电容器的电流为
   $$
   I=J_1S=\sigma_1E_1S=\frac{\sigma_1\sigma_2\sigma_3 VS}{\sigma_2\sigma_3 d_1+\sigma_1\sigma_3 d_2+\sigma_1\sigma_2 d_3}
   $$
   $$
   G=\frac{I}{V}=\frac{\sigma_1\sigma_2\sigma_3 S}{\sigma_2\sigma_3 d_1+\sigma_1\sigma_3 d_2+\sigma_1\sigma_2 d_3}
   $$
4. 平板电容器两导电平板之间为三层非理想介质，厚度分别为$d_1$、$d_2$、$d_3$，电导率分别为$\sigma_1$、$\sigma_2$、$\sigma_3$，平板面积为$S$，如果给平板电容器加电压$V$，求平板之间的电场。

   **解**

   设导电平板之间三层非理想介质中的电场均为匀强电场，分别为$E_1$、$E_2$、$E_3$，​​​​根据电压关系和边界条件，$E_1$、$E_2$、$E_3$满足以下关系：
   $$
   E_1d_1+E_2d_2+E_3d_3=V
   $$
   $$
   E_1\sigma_1=E_2\sigma_2=E_3\sigma_3
   $$
   解此方程组得
   $$
   E_1=\frac{\sigma_2\sigma_3V}{\sigma_2\sigma_3d_1+\sigma_1\sigma_3d_2+\sigma_1\sigma_2d_3}
   $$
   $$
   E_2=\frac{\sigma_1\sigma_3V}{\sigma_2\sigma_3d_1+\sigma_1\sigma_3d_2+\sigma_1\sigma_2d_3}
   $$
   $$
   E_3=\frac{\sigma_1\sigma_2V}{\sigma_2\sigma_3d_1+\sigma_1\sigma_3d_2+\sigma_1\sigma_2d_3}
   $$

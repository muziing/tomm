# 第7章 机械的运转及其速度波动的调节

## 7-1概述

应设法将机械运转速度波动的程度限制在许可的范围之内。

**机械运转的三个阶段**:

1. 启动阶段（starting period of machinery）
2. 稳定运转阶段（steady motion period of machinery）
   - 平均角速度 $$\omega_m$$ 保持为一个常数
   - 角速度 $$\omega$$ 一般周期性波动
   - 机械的一个运动循环：机械原动件角速度变化的一个周期
3. 停车阶段（stopping period of machinery）

机械特性（mechanical behavior）：各种原动机的作用力/力矩与其运动参数（位移、速度）之间的关系

## 7-4稳定运转状态下机械的周期性速度波动及其调节

盈功（increment of work）

- 驱动功 大于 阻抗功
- 等效构件动能增加
- 等效构件角速度上升

亏功（decrement of work）

- 驱动功 小于 阻抗功
- 等效构件动能减小
- 等效构件角速度下降

$$
\int^{\varphi^`_a}_{\varphi_a} (M_{ed} - M_{er})d\varphi = J_{ea^`} \omega^2_{a^`}/2 - J_{ea}\omega^2_a/2 = 0
$$

**周期性速度波动的调节**：

**飞轮**（flywhell）：

- 最好将飞轮安装在机械的**高速轴**上

- 机械出现盈功时，飞轮加速，储能；机械亏功时，飞轮减速，放能

- 飞轮等效转动惯量 $$J_f$$ 的计算公式：
  $$
  J_f \geq \Delta W_{\max} / (\omega^2_m[\delta]) - J_e
  $$
  如果 $$J_e << J_F$$，则 $$J_e$$ 可以忽略不计，于是可近似写为
  $$
  J_F \geq \Delta W_{\max} / (\omega^2_m[\delta])
  $$
  又如果平均角速度 $$\omega_m$$ 用平均转速 $$n$$ （单位：r/min）代换，则有
  $$
  J_F \geq 900 \Delta W_{\max} / (\pi^2n^2[\delta])
  $$

## 7-5机械的非周期性速度波动及其调节

安装**调速器**（speed regulator）来调节机械出现的非周期性速度波动

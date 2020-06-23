# learn
#这是我接触人工智能开始学习的算法，它们打开了我的视野


**遗传算法**
遗传算法是一种基于自然选择和群体遗传机理的搜索算法,它模拟了自然选择和自然遗传过程中的繁殖、杂交和突变现象.再利用遗传算法求解问题时,
问题的每一个可能解都被编码成一个“染色体”,即个体,若干个个体构成了群体(所有可能解).在遗传算法开始时,总是随机的产生一些个体(即初始解),
根据预定的目标函数对每一个个体进行评估,给出一个适应度值,基于此适应度值,选择一些个体用来产生下一代,选择操作体现了“适者生存”的原理,
“好”的个体被用来产生下一代,“坏”的个体则被淘汰,然后选择出来的个体,经过交叉和变异算子进行再组合生成新的一代,这一代的个体由于继承了上一代的一些优良性状,
因而在性能上要优于上一代,这样逐步朝着最优解的方向进化

**模拟退火**
模拟退火（Simulated Annealing, SA）算法是对热力学中退火过程的模仿。将金属加热到高温，此时金属内部分子热运动非常剧烈，内部的分子结构会出现很大变化；
之后让它缓慢降低温度，随着温度的降低，分子热运动的剧烈程度逐渐减弱，内部分子结构变化较小，逐渐趋于稳定。在寻找问题的最优解时，我们可以先给定一个初始
解。此时温度较高，初始解有很大的概率发生变化，产生一个新的解；随着温度的降低，解发生变化的概率逐渐减小

**人工免疫算法**

1.抗原的识别阶段：输入目标函数和各种约束作为免疫算法的抗原，并选择亲和度函数；

2.初始抗体的产生阶段：在解空间中用随机方法产生抗体；

3.亲和力的计算：分别计算抗原和抗体之间的亲和性并排序

4.记忆单元的活化：将与抗原亲和性高的抗体加入到记忆单元，并执行免疫操作

5.抗体的产生：通过交叉和变异和种群刷新产生进入下一代的抗体

6.终止记忆细胞的迭代：在达到指定阈值的时候终止记忆细胞的生成和选取；
**粒子群算法**
粒子群算法(Particle Swarm Optimization,简称PSO)是1995年Eberhart博士和Kennedy博士一起提出的。粒子群算法是通过模拟鸟群捕食行为设计的一种
群智能算法。区域内有大大小小不同的食物源，鸟群的任务是找到最大的食物源（全局最优解），鸟群的任务是找到这个食物源。鸟群在整个搜寻的过程中，通过
相互传递各自位置的信息，让其他的鸟知道食物源的位置最终，整个鸟群都能聚集在食物源周围，即我们所说的找到了最优解，问题收敛。

**禁忌搜索算法**
又称爬山启发式算法，从当前的节点开始，和周围的邻居节点的值进行比较。如果当前节点是最大的，那么返回当前节点，作为最大值(即山峰最高点)；
反之就用最高的邻居节点替换当前节点，从而实现向山峰的高处攀爬的目的。它是禁忌搜索的基础，TS算法是在其上改进而来。






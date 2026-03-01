1.架构图

 输入编码：encoder；张量：embedding；Transformer循环
 点积
 SoftMax转化为概率
 Linear：多头注意力 升维/降维 ————————与Q K V相乘
 SILU 非线性
残差网络

RMSNorm 归一化，更稳定
DropOut 防止过拟合



初始化项目
uv init

安装依赖 uv sync

工程目录结构：训练（训练函数工具集合，预训练文件），模型，数据集；
model文件设置初始化参数,huggin face
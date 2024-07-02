# IB CS CLASS

——**BY Dubowen**

![image-20240702165203119](C:\Users\86199\AppData\Roaming\Typora\typora-user-images\image-20240702165203119.png)



![image-20240702145741514](C:\Users\86199\AppData\Roaming\Typora\typora-user-images\image-20240702145741514.png)

how cpu work



+ 二进制（指令 地址）

  > 系统软件:OS 数据库 分布式 
  >
  > 应用软件:桌面
  >
  > 机器 汇编 高级
  >
  > 源程序->编译器（编译+汇编）->目标文件(+超链接)->可执行文件z

  + decode
  + 原码 补码 反码
  + IEEE 754

+ ALU

  + 加法

  + 乘法

    

  + 除法



+ 汇编语言



+ 指令流水线

  + 五个阶段
  + IF  ID EXEC MEM WB

  + conflicts

> 资源 
>
> + 后续指令暂停 
> + 数据存储+指令存储（重复配置）
>
> 数据  
>
> + 遇到数据相关的指令都暂停几个时钟时期
> + 数据旁路技术
>
> 控制冲突（地址跳转）
>
> + 提前预判

+ 性能指标
  + 吞吐量：单位时间执行量
  + 加速比
  + 效率



+ 种类：超标量 超流水线



Memorial

+ 分类：主存 辅存 cache

+ RAM(S-,D-)易失 ROM 只读（非易失）
+ 多体并行存储器：高位交叉编制（体号+体内地址） 低位：可并行



+ 主存与Cache映射(cuda)
  + 分块（块号【变？映射】+块内地址【不变】）
  + 直接映射（Tag+快好）
  + 全相联映射（主存块号）
  + 组相联映射（组数模拟块数）

+ 虚拟存储器
  + 页表
  + 段表



+ I/O总线

how cpu connect (device)



![image-20240702145804459](C:\Users\86199\AppData\Roaming\Typora\typora-user-images\image-20240702145804459.png)













![image-20240702165523667](C:\Users\86199\AppData\Roaming\Typora\typora-user-images\image-20240702165523667.png)

+ 时间/空间复杂度
+ 线性表
+ 链表
+ 堆栈
  + 队列
  + KMP
+ 树
+ 遍历 左/右子树
# ppt

The Effect of GoF Design Patterns on Stability: A Case Study

        > 最少30页



        - INTRODUCTION

        - abstract
  - 为什么引用到稳定性
          - 变更倾向与稳定性的相关与区别
          - 为什么关注稳定性
          - 研究稳定性的4个主要关注的因素
          - 模式类型
          - 类角色
          - 模式耦合
          - 应用领域
          - 四个因素预期的影响
          - 分析的具体的方法
          - 文献的主要贡献
          - 本文结构

          - RELATED WORK

          - Table1
          - 2.5节概述
          - 范围、目标、研究方法

          - USED TOOLS

          - 设计模式检测模式
          - ssa
          - pinot
          - 两种方法的不同
          - 两个工具自己纠正的方法
          - 手动检查模式
          - 手动检查方法
          - 模式合并
          - 移除一些模式
          - 两个模式的并集
          - 更改概率工具
          - 类的不稳定性
          - 公式（条件概率公式）
          - 常量说明（两张图 fig1）
          - Ripple Effects Measurement
          - 公式(rem各个参数为什么要算和不算这些参数，公式里面有参数换了ndmc-->rfc)
          - Fig2 具体说一下
          - Rem优势与局限性
          - 应用Rem具体的实例
          - Fig3 各个类的rem值是多少
          - Discussion on the REM

          - Case Study Design

          - 目标和研究问题

          - 研究问题3个大问题

          - Case Selection and Units of Analysis

          - 537 OSS
          - 数值：分析了多少类等。以及纠正的手法
          - Table2放在4.2里面

          - Data Collection and Pre-Processing

          - 描述每个类的9个变量：列表
          - Table3解释
          - 游戏中有很多策略模式，其他应用不用到，就影响到稳定性
          - Fig4
          - Table4
          - Table5 total 与上面提到的数量要少，是因为某周组合出现的频率太低，所以去掉
          - Table6
          - Table7

          - Data Analysis

          - 用到的方法

          - 描述性统计
          - 假设性检验
          - V1-V3用作验证集

          - Table8

          - 介绍了每个问题的具体的变量和使用的具体的方法
      - 结论

          - RQ1-2-3的回答
          - 验证的方法
          - 给语言假设，用数据集验证语言假设
          - fig5是对rq1的回答
          - 3个原假设：h0,a,b,c
          - Fig6回答rq1.1
          - h0(a)
          - Fig7回答rq1.2
          - Fig8回答rq1.3
          - Rq2.1 fig9 table9
          - rq2.2 fig10
          - rq3
          - fig11
          - table10总结了fig11的内容
          - 注意：把不稳定性区分成了两类
          - table11为啥区分两种稳定性
          - 结果：6个点

          - 讨论（自己发挥）

          - 模式出现的次数
          - 设计模式类型
          - 设计模式角色

          - 结果的有效性分析

          - 构建的有效性
          - 拿来做研究的数据集的准确性以及工具的准确性
          - 可靠性
          - 两名研究人员对数据集负责（收集、复查）
          - 外部有效性
          - 3个点
          - 内部有效性
          - 别记了

          -

########
使用指南
########

==============
     概览
==============
..  todo::

如果您已经掌握了新手入门阶段的内容，期望可以针对实际问题建模、搭建自己网络，本模块提供了一些 Fluid 的使用细节供您参考：


    - `Fluid 设计思想 <../user_guides/design_idea/fluid_design_idea.html>`_：介绍 Fluid 底层的设计思想，帮助用户更好的理解框架运作过程

    - `准备数据 <../user_guides/howto/prepare_data/index.html>`_ ：介绍使用 Fluid 训练网络时，数据的支持类型及传输方法

    - `配置简单的网络 <../user_guides/howto/configure_simple_model/index.html>`_： 介绍如何针对问题建模，并利用 Fluid 中相关算子搭建网络

    - `训练神经网络 <../user_guides/howto/training/index.html>`_：介绍如何使用 Fluid 进行单机训练、多机训练、以及保存和载入模型变量

    - `模型评估与调试 <../user_guides/howto/evaluation_and_debugging/index.html>`_：介绍在 Fluid 下进行模型评估和调试的方法，包括：
      
      - `模型评估 <../user_guides/howto/evaluation_and_debugging/evaluation/metrics.html>`_：介绍常用模型评估指标的构造方法
      - `Visual DL 工具 <../user_guides/howto/evaluation_and_debugging/debug/visualdl.html>`_：介绍如何利用 Visual DL 工具可视化训练过程

    - `预测部署 <../user_guides/howto/inference/index.html>`_：介绍如何应用训练好的模型进行预测


基于 Fluid 复现的多领域经典模型：

    - `Fluid 模型库 <../user_guides/models/index.html>`_


==============
     目录
==============

..  toctree::
    :maxdepth: 2

    howto/prepare_data/index
    howto/configure_simple_model/index
    howto/training/index
    howto/evaluation_and_debugging/index
    howto/inference/index
    models/index.rst
    design_idea/fluid_design_idea.md

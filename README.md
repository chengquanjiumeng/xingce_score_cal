# 综基历年真题做题记录
一个用于记录福建省行政职业能力测试历年真题做题过程的Python脚本，自动计算总分并记录错题及其正确选项，并将结果保存到Excel文件中。

# 功能
  1.记录错题号及其错选项和正确选项
  
  2.计算并记录总分
  
  3.将结果保存到Excel文件中，并按照格式输出

# 安装
  1.克隆这个仓库
    git clone https://github.com/chengquanjiumeng/xingce_score_cal.git
  
  2.安装所需的Python库
    
  使用以下命令安装openpyxl库：
      
      pip install openpyxl

# 使用
  1.运行脚本
  
  确保你已经安装了所需的Python库。然后，运行以下命令启动脚本：
      
      python xingce_score_cal.py
  
  2.输入信息
  
  输入真题的年份和月份。
    
  输入错题号（1-120），然后输入错选项和正确选项。
    
  使用'0'来取消上一次的错题输入。
    
  输入'end'完成记录并保存到Excel文件中。

# 示例
  
  请输入真题的年份: 2015
  
  请输入真题的月份: 3
  
  输入错题号(1-120)    '0'_上次输错不算  'end'_输入完毕
  
  -> 1
  
  输入错选项（A, B, C, D）:
  
  -> B
  
  输入正确选项（A, B, C, D）:
  
  -> C
  
  ...

# 文件说明
  行测历年真题做题记录.xlsx：保存所有的做题记录，包括题号、错选项和正确选项。
  
  xingce_score_cal.py：主要的Python脚本，负责数据录入和保存。

# 贡献
  欢迎任何贡献，提交问题或功能请求，或者直接提交代码。
  
  1.Fork本仓库
  
  2.创建一个新分支
  
  3.提交你的修改
  
  4.发送Pull Request

# 联系
  如有任何问题或建议，请联系 3081334972@qq.com 或在GitHub Issues中提出。

# 许可证
  本项目采用 MIT许可证 开源协议。

emotion.txt：专业领域情感词典的搭建，结合学生评论数据的特点和知网hownet、台湾大学NTUSD、大连理工情感词汇本体、清华大学褒贬义词典进行完善
introductions.txt：导论的专业领域词典，结合导论书本内容进行完善
units/unit1-7.txt：7个章节的知识点词典，结合导论书的章节信息来完善
输入：
1、课前、课后、每周总结环节的学生评论文本（必须输入）；
2、课前、课后、每周总结环节的权重数组weight（可选择是否输入）；
3、课前、课后环节的课程内容难度数组dif（可选择是否输入）；
输出：
1、学习过程中的情感值数组-得出学生在课程学习过程中的情感变化；
2、情感均值-得出学生整体的情感极性；
3、情感值方差-得出学生情感波动状况（大小）；
完成的工作：
1、学生评论文本情感倾向的标记；
2、搭建专业领域词汇词典、情感词汇词典、停用词词典；
3、搭建网络模型RNN、CNN、LSTM、Bi-LSTM，并进行结果的对比；
4、多维融合-本文添加了权重；
5、持续过程的情感分析-本文得出学习过程的学生情感变化趋势；
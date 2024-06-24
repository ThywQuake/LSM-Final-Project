# LSM期末报告代码部分

该说的内容已经在报告文档中说了, 这里展示的是一些之外的内容

本次分析主要采用的库有 numpy, matplotlib, seaborn, pandas, netCDF4, causal_ccm
其中, causal_ccm 较为不常见, 可以用`pip install causal_ccm`进行下载

其实一开始模拟的时间范围是20年, 本来打算做20年的CCM分析, 但是发现有两个弊病
- 运行时间太长了
- 长时间序列的CCM分析会逐渐抹消年内变化, 转向年际变化, 这对我的分析目标是略有不利的
因此决定采用3年作为分析的时间范围, 一方面避免了初期的spin up的参数不真实, 另一方面也缩短了运行时间(赶ddl人士落泪)

另外, 本来还想分析土壤不同层含水量/根系分布/植被类型的一些因果, 但是限于时间和篇幅没法展开了QAQ

最后, 感谢老师/助教看到这里!

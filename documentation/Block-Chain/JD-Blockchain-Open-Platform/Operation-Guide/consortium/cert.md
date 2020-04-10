# 证书管理
在京东云版本中，建链完毕后系统会自动建立一些证书。但是需要网络创建者根据节点数量手工建立各个节点的证书。证书名称必须与节点名称一致。比如，选择1个节点，那么节点名称就是peer0。如果选择4个节点，节点名称既是peer0、peer1、peer2、peer3。打开证书管理tab页即可看到所有证书列表，在此页面可以查看证书详情或者下载证书，如要新申请证书，需要在证书管理tab页上点击*申请证书*按钮，即可申请。同时，可以输入证书名称，点击*查询*按钮，查询符合名称要求的证书。

![图片](../../../../../image/JD-Blockchain-Open-Platform/Getting-Started/Pic/consortium27.png)

证书申请页面分为基本信息和更多信息部分，具体展示如下：

![图片](../../../../../image/JD-Blockchain-Open-Platform/Getting-Started/Pic/consortium28.png)

此页面字段说明如下：

|参数名|	必填项|	规则|
|----------|:----------:|------|
|证书名称|	是|	可以输入证书名称，必须英文，不超过20|
|证书密码|	是|	证书密码，数字输入|
|证书类型|	是|	可以选择peer和user|
|域名	|是|	如有域名的特殊要求，可以写入域名|
|区域	|是|	有特殊的区域要求，可以输入区域信息|
|地址|	是|	有特殊的地址需求，可以输入地址信息|
|部门|	是|	有特殊的部门需求，可以输入部门信息|

完成证书创建后，可以在列表页面查看到证书信息，在此页面，可以点击证书名称查看证书的详细内容。

![图片](../../../../../image/JD-Blockchain-Open-Platform/Getting-Started/Pic/consortium29.png)

同样，针对每一个证书，都有响应的操作权限，证书管理的操作权限仅为下载。点击*下载*按钮，可以下载证书内容至本地保存。
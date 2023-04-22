展映AI产品系列体验：

[展映AI产品示例](http://zyinfo.pro)

版本功能说明：

| |免费版（单服务器）|基础版|高级版|
|:----|:----|:----|:----|
|会议记录 + 总结<br>[在线体验](http://m.zyinfo.pro)|仅使用第三方接口<br>每月不超过50小时|仅使用第三方接口<br>每月不超过500小时|提供完全的本地部署服务，无限制|
|语音对话|包含|包含|包含|
|AI 对话|包含|包含|包含|
|存储载入对话环境|包含|包含|包含|
|存储载入公用对话环境|包含|包含|包含|
|    通用智能系统|    无代码生成服务|    无代码生成服务|包含任务代码自动生成<br>还能根据网站文档批量生成软件代码|
|    创建任务|    无|    无|包含<br>未来持续更新通用智能服务|
|运行任务|包含|包含|包含|
|提交AI插件|无|无|包含|
|更新官方AI插件|手动更新|自动更新|自动更新|
|对话中调用AI插件|包含|包含|包含|
|对话中自动匹配AI插件|无|包含|包含|
|    文件知识库索引|    无|包含<br><br>（限制最多1千万条）|包含<br>部署本地的知识库，视服务器配置，基本无限制|
|网页内容批量导入|无|包含|包含|
|网站文档批量生成软件代码 记录并索引，不限语言|    无|    无|    包含|
|对外提供API服务|无|无|包含|
|对话记录知识库索引|无|包含<br>可实现智能客服|包含<br>可实现智能客服|
|调用预设的对话知识库|无|包含|包含|
|微信客服接口|无|包含|包含|
|本地服务联通|无|包含|包含|
|AI服务部署|无本地AI服务|无本地AI服务|部署本地AI服务|
|展映相关AI产品|无|提供部分体验、优惠价格|优先内部测试体验、优惠价格|
|产品更新、升级|手动更新|通知更新|通知更新|
|    文字转图像|包含<br>OpenAI 提供|包含<br>OpenAI 提供|包含<br>未来可能增加新的产品，免费升级|
|数字人主播、客服|可有限体验|选配，部分体验<br>优惠报价|选配，后续提供<br>额外优惠报价|
|自然语言知识库引擎|无|包含<br>公用接口|包含<br>本地接口|
| <br><br>价格|部署服务1～ 2万<br><br>自行部署不收费<br>使用免费，但需提供公司资料以便记录|    <br>部署 5~10万<br>使用授权3万/年|部署 30~100万，<br>根据需求，不含服务器<br>使用授权 10~50万/年|

 

免费版安装方式：

1、下载部署文件

	展映企业AI本地服务 免费版 v1.1.rar 链接：

	[hayoou.com/ybz1](http://box.hayoou.com/1682096812993/%E5%B1%95%E6%98%A0%E4%BC%81%E4%B8%9AAI%E6%9C%AC%E5%9C%B0%E6%9C%8D%E5%8A%A1%20%E5%85%8D%E8%B4%B9%E7%89%88%20v1.1.rar)

	

	百度网盘：

	链接：[https://pan.baidu.com/s/1m5VcnTCoNGTPrcwq8g57PQ?pwd=5566](https://pan.baidu.com/s/1m5VcnTCoNGTPrcwq8g57PQ?pwd=5566)

	提取码：5566

	

2、设置

	如需要运行AI插件，安装python 3.7～3.10 版本，复制 python 为 python3，确保python3命令可用。

	需要本地连接外网，确保本地环境都在外网，请购买企业海外专线或配置Proxy_url。

	 

3、  服务器防火墙设置：

放通8880，8881，8882，8883，8886 端口

	 

4、基础版可安装本地索引服务（联系我们）

	

	 

5、配置文件（申请相关key，ssl证书）

	修改：settings.txt

● OpenAI_API_key: 第三方OpenAI 接口(必填）

● Local_AI_server:本地AI服务接口（高级版可填）

● Local_AI_system:本地AI 系统（高级版可填）

● Local_AI_model:本地AI 模型（高级版可填）

● API_domain 你的API 域名 (必填）

● Site_domain 你的网站域名(与API域名一致）(必填）

● Default_openid 默认zyinfoai，暂不修改

● Main_API_Server_ID 默认zyinfoai，暂不修改

● User_default_max_chat_cnt 每个用户最大免费聊天次数

● OpenID_default_max_chat_cnt：公开 API 接口的新账号默认 最大聊天次数

● OpenID_Max_relate_data_cnt ：公开API 接口的 默认最大关联聊天数据库更新次数

● SSL_key_path ssl证书key路径(必填）

● SSL_cert_path ssl证书路径(必填）

● ZY_AI_auth_key 联系我们 提供，测试使用 test (必填）

● Company_name_short 公司名称

● Ali_voice_key： 阿里云 语音实时识别服务key (必填）

● Ali_voice_secret：阿里云 语音实时识别服务secret (必填）

● User_agreement_url：用户协议

● Temp_file_dir：临时文件夹

● Max_upload_file_text_size_trier：体验用户最大上传文件大小

● Max_upload_pdf_file_page_trier：体验用户上传最大pdf页数

● Wechat_kf ：微信客服相关配置

● Azure_voice_recognize_subscription：微软 Azure 语音识别、合成（需要语音对话可填）

● Azure_voice_recognize_region：微软 Azure 语音识别、合成 region

● AGI_use_docker：false

● Google_search_key：谷歌搜索key (必填）

● Google_search_cx：谷歌搜索自定义场景 (必填）

● Proxy_url: 代理节点，连接到本地的代理。

● Recharge_key:充值指令

● 更多参数需要基础版或高级版。

	 

用户充值，增加对话次数（新增内部用户）：

	发送 示例：比如 Recharge_key=-zyinfo-

	发送：chag-zyinfo-100@userid

	100是充值金额，userid 是用户名

	任意对话中发送即可。

	格式：chag{Recharge_key}{金额}@用户名

 

高级版新增：

API账号管理等功能

	 

若测试 test.zyinfo.pro ，请修改 本地 hosts 文件

127.0.0.1       test.zyinfo.pro

	 

	9、运行 mainapi.exe

	10、使用Chrome 浏览器打开（替换成你的域名）

	会议记录：

	通用智能：

	[https://test.zyinfo.pro/agi](https://test.zyinfo.pro/agi)

11、  使用参考：

[展映智慧助手AI插件市场接入指南](https://docs.qq.com/doc/DS0lNaHFXcWJ0d3Fr)

[展映智慧助手数据版AI对话接口](https://docs.qq.com/doc/DS0dWdmdNRkRWc2JJ)

[智慧助手 指令使用说明](https://docs.qq.com/doc/DS1VTblp4U1lyZWds)

联系我们：

微信youkpan

深圳展映科技有限公司 [zyinfo.pro](http://zyinfo.pro)


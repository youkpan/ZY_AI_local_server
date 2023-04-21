版本功能说明：

|    |免费版|基础版|高级版|
|:----|:----|:----|:----|
|会议记录 + 总结|有（仅提供chatGPT接口）|有（仅提供chatGPT接口）|提供完全的本地部署服务|
|语音对话|有|有|有|
|AI 对话|有|有|有|
|存储载入对话环境|有|有|有|
|存储载入公开对话环境|有|有|有|
|通用智能系统|无代码生成|无代码生成|代码生成|
|创建任务|无|无|有|
|运行任务|有|有|有|
|提交插件|无|有|有|
|更新插件|手动更新|自动更新|自动更新|
|运行插件|有|有|有|
|文件知识库记录索引|无|有<br>（限制最大1千万条）|有<br>部署本地的知识库|
|对外提供API服务|无|无|有|
|对话记录索引|无|有<br>可实现智能客服|有<br>可实现智能客服|
|微信客服接口|无|有|有|
|本地服务联通|无|有|有|
|AI服务部署|无本地AI服务|无本地AI服务|部署本地AI服务|
|展映相关AI产品|无|提供部分体验、优惠价格|优先通知体验、优惠价格|
|数字人|无|部分体验<br>额外报价|后续提供<br>额外优惠报价|
|    价格|部署 2万<br>自己部署免费<br>免费使用|部署 5万<br>后续3万/年|部署 50万，不提供服务器<br>后续授权 10万/年|


免费版安装方式：

1、下载部署文件

展映企业AI本地服务 免费版 v1.0.rar 链接：

[hayoou.com/ybys](http://box.hayoou.com/1682070326703/%E5%B1%95%E6%98%A0%E4%BC%81%E4%B8%9AAI%E6%9C%AC%E5%9C%B0%E6%9C%8D%E5%8A%A1%20%E5%85%8D%E8%B4%B9%E7%89%88%20v1.0.rar)

2、设置外网

需要本地连接外网，确保本地环境都在外部服务

3、修改相关内容 

（website 文件夹，替换test.zyinfo.pro 为你的域名)

4、安装本地索引服务：

[https://shimo.im/docs/Wr3DVmp7oGT2dokJ](https://shimo.im/docs/Wr3DVmp7oGT2dokJ)

5、配置文件（申请相关key，ssl证书）

修改：settings.txt

        * OpenAI_API_key: OpenAI chatGPT 接口
        * Local_AI_server:本地服务接口（免费版不填）
        * API_domain 你的API 域名
        * Site_domain 你的网站域名
        * Default_openid 默认openid，暂不修改
        * Main_API_Server_ID 默认openid，暂不修改
        * User_default_max_chat_cnt 每个用户最大免费聊天次数
        * OpenID_default_max_chat_cnt API 接口的 最大默认聊天次数
        * OpenID_Max_relate_data_cnt  API 接口的 最大关联聊天数据库更新数
        * SSL_key_path ssl证书路径
        * SSL_cert_path ssl证书路径
        * ZY_AI_auth_key 联系我们 提供
        * Company_name_short 公司名称
        * Ali_voice_key： 阿里云 语音实时识别服务key
        * Ali_voice_secret：阿里云 语音实时识别服务secret
        * User_agreement_url：用户协议
        * Temp_file_dir：临时文件夹
        * Max_upload_file_text_size_trier：用户体验最大上传文件大小
        * Max_upload_pdf_file_page_trier：用户体验最大pdf页
        * Wechat_kf ：微信客服相关配置
        * Azure_voice_recognize_subscription：微软 Azure 语音识别
        * Azure_voice_recognize_region：微软 Azure 语音识别
        * AGI_use_docker：false
        * Google_search_key：谷歌搜索
        * Proxy_url: 代理节点，连接到本地的代理。
用户充值：

发送 示例：chag100@userid

100是充值金额，userid 是用户名

任意对话中发送即可。

格式：chag{金额}@用户名

高级版新增：

API账号管理等功能

若测试 test.zyinfo.pro ，请修改 本地 hosts 文件

127.0.0.1       test.zyinfo.pro

9、运行 mainapi.exe

10、使用Chrome 浏览器打开（替换成你的域名）

会议记录：

[https://test.zyinfo.pro/ai/meeting/](https://test.zyinfo.pro/ai/meeting/)

通用智能：

[https://test.zyinfo.pro/agi](https://test.zyinfo.pro/agi)

联系我们：

微信youkpan

深圳展映科技有限公司 [zyinfo.pro](http://zyinfo.pro)


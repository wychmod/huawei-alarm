# 华为云告警机器人

## 项目配置
### 机器人配置
[robot]
app_id: 飞书机器人app_id
app_secret: 飞书机器人app_secret
tenant_token_url=https://open.feishu.cn/open-apis/auth/v3/tenant_access_token/internal : 飞书机器人获取tenant_token的url
chat_message_url=https://open.feishu.cn/open-apis/im/v1/messages?receive_id_type=chat_id : 飞书机器人发送消息的url
chat_info_url=https://open.feishu.cn/open-apis/im/v1/chats?page_size=20 : 飞书机器人获取群组信息的url
get_user_id_url=https://open.feishu.cn/open-apis/contact/v3/users/batch_get_id?user_id_type=user_id : 飞书机器人获取用户id的url
user_message_url=https://open.feishu.cn/open-apis/im/v1/messages?receive_id_type=user_id : 飞书机器人发送消息的url

### 数据库配置
[pgsql]
host=127.0.0.1 : 数据库地址
port=5432 : 数据库端口
dbname=fastapi : 数据库名称
user=postgres : 数据库用户名
passwd=123456 : 数据库密码
echo=true : 是否打印sql语句

## 通过华为云告警进行配置
https://digital-brain.feishu.cn/docx/EnsadU5tvofP3WxPFaKcQ4r1nQg 详情查看这个文档
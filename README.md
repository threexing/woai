
提示：

部署到kintohub时，v2ray可以从网络地址读取文件配置，使用自定义的CONFIG更加灵活，支持tor网络，去掉了球童
部署时需要填写子文件夹路径选项为kinto，部署超时建议设置为五分钟
默认配置是https://github.com/threexing/woai/kinto/config.json，建议自行复制修改内容后放到GIST，然后设置CONFIG变量为GIST的RAW地址
部署后直接访问外部访问返回404或Bad Request都表示部署成功

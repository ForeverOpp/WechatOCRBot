# 微信OCR机器人
- ## 简介
    这是一个基于Python的，对微信电脑端客户端进行OCR识别以便进行自动化操作的机器人。

  
- ## 功能
    - [ ] 自动适应分辨率
    - [ ] 自动调整窗口位置
    - [ ] 识别消息
    - [ ] 回复指定消息
    - [ ] 转发消息
    - [ ] 对指定消息进行其他渠道转发（如Bark，Telegram等）
    
- ## 项目结构
    - Forward.py
    
        负责对消息进行转发。
    
    - main.py
    
        程序主逻辑。
       
    - MessageSender.py
        
        消息转发接口，后期扩展发送方式可以对这个文件进行修改。
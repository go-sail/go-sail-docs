---
sidebar_position: 4
---

# 常量  
阐述什么是常量。  
### 简介  
在Go-Sail中，一些系统常量被定义并存储在contents包下，以供某些特定场景使用。  
- **code**  
它用于定义业务响应代码或错误代码。  
    :::tip  
    `RegisterCode()` 函数将为注入自定义错误代码和错误消息提供强大的帮助。  
    我们将在后续章节中详细介绍其目的和用法。
    :::  
- **error**  
它用于定义错误代码和错误消息。它还支持 i18n。  
- **i18n**  
用于定义语言编码，采用ISO-3166-1标准。  
- **keys**  
目前用于定义公钥和私钥的前缀和后缀标识符。  
- **sail**  
包含框架的徽标字符和版本号。  
- **status**  
用于响应成功和失败的布尔值。  
- **time**  
目前，定义了全球各个时区的时区字符和日期打印模板。  
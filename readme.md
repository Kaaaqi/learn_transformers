# 学习记录   
使用up主的训练代码，修改为对llama3.2 3b 的训练  显存大概占用11.5个G
其中需要配置:tokenizer.pad_token=tokenizer.added_tokens_decoder[128004]
不知道是不是对的 

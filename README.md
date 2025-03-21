# flow3 介绍
由 netX 领投的 $22M 融资

注册rf：https://dashboard.flow3.tech?ref=GJ3bvNYSG

# Flow3 Bot 使用教程
```json
[
    {
        "Private_Key": "solana的私钥1",
        "proxy": "http://192.168.2.7:50010"
    },
    {
        "Private_Key": "solana的私钥1",
        "proxy": "http://dandan:dandan@192.168.2.7:50010"
    },
    {
        "Private_Key": "solana的私钥2",
        "proxy": "socks5://192.168.2.7:50020"
    },
    {
        "Private_Key": "solana的私钥1",
        "proxy": "socks5://dandan:dandan@192.168.2.7:50010"
    }
]
```
注意配置文件{}{}之间需要一个逗号, 最后一个{}不要有逗号

推荐使用vscode的json拓展：https://marketplace.visualstudio.com/items?itemName=mohsen1.prettify-json

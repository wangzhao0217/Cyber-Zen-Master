# 赛博禅师

一个基于DeepSeek的哲理问答思维链多步推理工作流。

## 使用方法

使用conda环境配置相应依赖包：

```
pip install openai
```

在`llm_client.py`中的`API_KEY`变量配置DeepSeek官方API密钥。

在主程序`main.py`的入口的`topics`变量中，以列表形式填入你想问的一个或多个问题，并使用如下命令运行：

```
python main.py
```

## 输出位置

最终结果和中间各步骤推理过程，会存入`output`文件夹中。每个问题的最终输出会保存在以问题命名的文件夹下的`stage3/self_expression.txt`文件中。

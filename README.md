# Learn Rasa

## To Review
* [botfront](https://github.com/botfront/botfront) - 基于Rasa的开源的对话机器人GUI开发平台（已停止维护）
    * [Rasa Webchat](https://github.com/botfront/rasa-webchat) - A feature-rich chat widget for Rasa and Botfront
* [Doctor-Friende](https://github.com/pengyou200902/Doctor-Friende) - 基于中文的医疗知识图谱的问答机器人
* [Rasa_NLU_Chi](https://blog.csdn.net/n66040927/article/details/108151192) - 支持中文的Rasa NLU训练服务部署，github：[https://github.com/crownpku/Rasa_NLU_Chi](https://github.com/crownpku/Rasa_NLU_Chi)
* [WeatherBot](https://github.com/howl-anderson/WeatherBot) - 一个基于 Rasa 的中文天气情况问询机器人(chatbot), 带 Web UI 界面

## 配置环境&依赖
### MITIE
1.` conda activate` 激活你的python环境（或者venv激活）
2. pip 或者 `conda install cmake` 以及boost
3. 终端或者cmd进入你的工作目录或者随便哪里，`git clone https://github.com/mit-nlp/MITIE.git`
4. cd进MITIE的文件夹，`python setup.py build`
5. 最后 `python setup.py install`

### jieba分词
`pip install jieba`
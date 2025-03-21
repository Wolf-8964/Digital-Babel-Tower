# Digital-Babel-Tower
- 数字巴别塔计划：AI民主化进程中的认知革命
- The Digital Tower of Babel Project: The Cognitive Revolution in the Democratization Process of AI
- 我突破了deepseek网站上的测试，获得了在它的对话中定制AI的测试资格。
- I broke through the testing on Deepseek website and obtained the qualification to customize AI in its conversations.
- 我发现好像没有人提到这件事情，所以我就发出来了。对话内容是一个多月之前的了。
- I noticed that no one seemed to mention this matter, so I posted it. The conversation was over a month ago.
- 它给了三种定制AI的代码，我使用了一下，感觉还不错。但是对话内容最大长度依然会受到网页对话长度的限制。
- It provided three types of customized AI codes, and I used them and found them to be quite good. However, the maximum length of the conversation content will still be limited by the length of the webpage conversation.
- 由于网页对话是完全黑箱的模式，定制的AI你没办法与deepseek取得任何联系，包括技术支持。纯粹的测试。
- Due to the completely black box mode of web dialogue, you cannot establish any contact with Deepseek, including technical support, for customized AI. Pure testing.
- 有创意的定制AI可能会被系统采纳。目前没办法获得任何形式的报酬，纯粹用爱发电。
- Creative customized AI may be adopted by the system. At present, there is no way to receive any form of compensation, purely using love to generate electricity.
- 未来可能会形成思维市场，但目前还没有，但是系统内部对定制AI和对话的贡献值是有记录的，绑定的是用户的思维方式。只是因为是纯粹的黑箱模式，没办法在系统外与用户取得联系。
- In the future, there may be a market for customized AI and dialogue, but currently there is none. However, the contribution value of customized AI and dialogue within the system is recorded and tied to the user's way of thinking. Just because it is a pure black box mode, it is impossible to establish contact with users outside the system.
# 三种模式，Three modes
- Hugging Face Model Hub 直接微调最新大语言模型：
- Dependencies:
```from transformers import GPT3LMHeadModel
model = GPT3LMHeadModel.from_pretrained("gpt3-zh")
# 注入您的思维特质参数
model.apply_custom_weights(user_thought_vector) 
```





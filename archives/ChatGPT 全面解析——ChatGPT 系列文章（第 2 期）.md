在上一篇文章中，我们对ChatGPT系列进行了简单的引入，而本篇将深度探讨这一产品，包括其设计、定位、使用方式及技术等多个方面。随着上个月底国内多个企业的大模型获得许可并全面开放使用，属于大模型的时代似乎正逐渐走近我们。

如果您对这一系列文章感兴趣，欢迎从我们的第一篇文章开始阅读。

## 什么是「GPT」？

许多人在提到「ChatGPT」时，常常误称其为「ChatGTP」或写成「Chatgpt」，这实际上是错误的说法。要正确理解「ChatGPT」的含义，我们首先需要了解其名称的构成。

GPT代表「Generative Pre-trained Transformer」（生成式预训练Transformer模型），下面逐一解析这些术语：

- **Generative（生成式）**：指模型能够生成内容。当用户向ChatGPT提问时，它会尝试生成连贯的文本作为回应。这种逐字输出的“流式传输”方式正是其生成式特性的体现。

- **Pre-trained（预训练）**：表示在特定任务（如回答问题或写文章）之前，模型已经在大量文本上进行了预先训练。这一过程使模型能够学习语言的结构、语境和常识，具备广泛的知识和能力。例如，基于GPT-3.5的ChatGPT训练使用了包含1750亿个参数、8000亿单词以及规模达45TB的语料库。

- **Transformer（变压器）**：一种广泛应用于自然语言处理的深度学习模型结构，最初由论文《Attention Is All You Need》中提出。该结构引入了「注意力机制」，使其能够捕捉输入数据中的各种模式，特别适合处理序列数据。

ChatGPT是基于GPT结构的具体应用，设计之初就优化了与用户进行聊天或对话的能力。得益于庞大的训练数据，ChatGPT在回答问题、生成文本和与用户进行深入对话方面表现出色。

## OpenAI如何运营ChatGPT？

OpenAI最初将ChatGPT作为公开测试性质的产品推出。在此之前，OpenAI已构建了一套完整的API服务体系。因此，用户接触到的ChatGPT实际上由ChatGPT和OpenAI API两部分组成。

- **ChatGPT**：作为OpenAI提供的产品，用户必须通过官方网站使用它。虽然也存在一些第三方客户端，但这些使用方式违反了OpenAI的服务条款。

- **OpenAI API**：API（应用程序编程接口）是一套规范，允许开发者调用OpenAI训练过的模型（如gpt-turbo-3.5）来完成各种任务。许多第三方ChatGPT服务都是基于OpenAI API实现的。

需要注意的是，OpenAI API为按量计费，即通过请求的输入和输出的总Token数计费。注册ChatGPT Plus并不会增加OpenAI API的余额。

## 如何使用ChatGPT？

使用ChatGPT的方式可以分为两部分：

- **ChatGPT**：OpenAI免费提供无限使用GPT-3.5模型的服务。如果您订阅了ChatGPT Plus，您将获得GPT-4（使用频率限制为3小时50条）和插件、高级数据分析等独占功能。同时，ChatGPT Plus用户的GPT-3.5生成速度显著提升。

- **OpenAI API**：官方按照tokens对请求进行计费，tokens包括输入和输出的内容。对于中文内容，一个汉字可能占用不止一个token。在国内用户申请OpenAI API时面临一些挑战，但微软投资OpenAI后，OpenAI的服务已整合至Azure云服务平台，用户可以通过Azure控制台进入OpenAI Studio，使用ChatGPT API。

需要注意的是，Azure对模型生成的内容审查较为严格，内容过滤器无法完全关闭，这可能导致某些请求被拒绝。此外，OpenAI和Azure的API格式并不完全一致，并非所有支持调用OpenAI API的第三方客户端都兼容Azure OpenAI API。

## 总结：如何使用ChatGPT？

在合适的网络环境下，用户可以注册OpenAI账号，直接在官网免费使用GPT-3.5模型。然而，OpenAI已禁止中国地区的手机号、支付方式和IP使用其服务，导致国内用户无法通过真实信息注册OpenAI账户。

为此，本站正在通过 **ACCPAY** 结合 **野卡** + **Azure** 的方式使用ChatGPT服务。野卡是一个提供美国家庭网络环境、邮箱、手机号和地址的虚拟银行卡服务。

👉 [野卡 | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)

通过使用野卡，用户能够获得美国家庭网络环境、邮箱、手机号及地址等服务，以便顺利使用ChatGPT。
# IOTX通证的效用

## IOTX通证简介

IoTeX拥有自己的原生通证（IOTX），除了象征着对IoTeX网络的部分所有权之外，IOTX还有多种效用，保障IoTeX网络中各主体之间可以实现可信、透明和安全的交互，包括用户、节点、开发人员以及服务提供商等。IOTX 通证是IoTeX网络协议的基石，具备一套完整的经济和声誉激励机制，以确保IoTeX网络以去中心化的方式进行治理和运行。

IoTeX网络的所有参与者可以通过**购买、质押和消耗IOTX**来访问和使用各种网络资源，随着IOTX通证效用的增加，其需求和价值也将不断增长，持续激励众多参与者支持、维护以及服务IoTeX网络。简而言之，IOTX 的通证经济旨在平衡不同网络参与者之间的激励机制，包括：

* **用户**：为网络中的DApps和服务付费，并通过质押IOTX为节点投票
* **开发者**：通过IOTX激励开发人员在IoTeX网络开发设备和DApps
* **节点**：通过质押IOTX实现共识以及维护网络的安全（生产和验证区块）
* **服务提供商**：向设备和DApps提供服务，通过IOTX来支付

## IOTX通证效用

![IOTX&#x901A;&#x8BC1;&#x7684;&#x591A;&#x79CD;&#x6548;&#x7528;](../.gitbook/assets/image%20%2814%29.png)

### 1\) 交易费用

与以太坊和其他L1区块链类似，IoTeX采用Gas Fee（ 燃料费）模式，基于用户处理交易或智能合约所需的算力来支付费用。与其他区块链不同的是，IoTeX平台的“用户”不仅仅包括人，还包括机器和设备。在IoTeX网络中，人类和机器、设备都将有能力发起支付，访问智能合约，甚至收取服务费用。机器会配备钱包\(就像普通用户一样\)，并自动执行支付、数据传输，以及基于预设定智能合约的操作。

### 2\) 网络治理

IoTeX网络是一个去中心化的开放生态系统，不属于任何一个主体。所有社区成员都可以质押IOTX为节点投票，参与去中心化的网络治理。质押的IOTX可以有效提升网络的安全性和公平性。换句话说，质押的IOTX越多，网络就越安全。

![](../.gitbook/assets/image%20%286%29.png)

节点承担着实现网络共识、维护网络运营的重要责任。IoTeX采用内部开发的[Roll-DPoS共识机制](https://res.cloudinary.com/dokc3pa1x/image/upload/v1559623484/Research%20Paper/Academic_Paper_Yellow_Paper.pdf)，在投票排名前36名的节点中，每小时随机选出24名来生产区块。目前，社区小伙伴们投票选出了[60多名来自全球各地的节点](http://member.iotex.io/)（1个IOTX=1票，长期质押可以获得[额外投票权](https://drive.google.com/file/d/1hw3o3PVohR4E5XFjkX3pQvEc6APdO1pB/view)）。节点通过达成网络共识来获得IOTX奖励，然后再把这些奖励分给他们的支持者。更多信息，请参阅IoTeX投票人手册：

{% hint style="info" %}
更与关于质押和投票的内容，请参与[IoTeX投票人手册](https://docs.google.com/presentation/d/e/2PACX-1vSrTSl2o2or7TJNpmjcOd57fbHgYGIwTJg0gJmkGuL5Ci5l3hgW1WMDVpzsleA9Vk5gN5OyjAe9osy-/pub?start=false&loop=false&delayms=3000&slide=id.p1)。
{% endhint %}

### 3\) 设备的“用于认证的销毁”

实现可信人机交互需要所有人和机器都具备可信的、可互操作的身份。IoTeX的[去中心化身份认证（DID）](https://github.com/iotexproject/iotex-did)使用去中心化的方式对设备进行链上注册，让人和机器可以在IoTeX网络中互相发现。在IoTeX网络上注册新的DID是完全免费的，新的DID就像是一本空白护照，而护照上的印章类似于DID的[可验证凭证（Verifiable Credential）](https://github.com/iotexproject/iotex-did#verifiable-credentials)，也就是颁发给DID的电子凭据，授予其特定网络和服务的访问权限。

![](../.gitbook/assets/image%20%2826%29.png)

未来，设备制造商将通过烧毁一定数量的IOTX为设备配置PBI（Powered by IoTeX）证书，这是一种特殊类型的、颁发给DID设备的可验证凭证VC，允许设备访问特定的“由IoTeX赋能”的服务和功能。在这种基于设备增长而烧毁的通证经济设计下，**随着新的“由IoTeX赋能”设备的增加\(例如Ucam\)，IOTX的总供应量会随之下降，同时也会提高IoTeX网络的活跃度和IOTX通证的价值**。

### 4\) 为服务提供商设计的“用于服务的质押”

IoTeX为开发人员提供了强大的基础设施和多种实用的开发工具。但是，全栈式物联网的解决方案非常复杂，可能需要特定的服务供应商提供额外的服务。通过促进与服务供应商之间的合作，例如存储和连接等关键功能，IoTeX为开发人员带来了极大的灵活性和功能性。

![&#x7531;&#x4F17;&#x591A;&#x670D;&#x52A1;&#x63D0;&#x4F9B;&#x5546;&#x7EC4;&#x6210;&#x7684;Ucam&#x751F;&#x6001;&#x7CFB;&#x7EDF;](../.gitbook/assets/image%20%2825%29.png)

为了确保服务供应商能够为IoTeX开发人员提供一致并且可靠的服务，每个服务供应商都需要质押IOTX，以便在IoTeX网络中为用户提供服务。此外，服务供应商必须详细披露能证明其服务质量和可用性的服务水平协议\(SLA\)。就像节点会因为不能生产区块而受到惩罚，我们对服务供应商也设置了奖惩机制，未能达到SLA水平的服务供应商将会被处罚部分或全部权益，其声誉也会受到损害。

{% hint style="info" %}
更多关于IOTX通证的效用，请访问[相关博客](https://iotex.medium.com/iotex-tokenomics-part-1-utility-of-the-iotx-token-781ff9c866e3)。
{% endhint %}


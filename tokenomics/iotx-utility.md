---
description: IOTX通证的效用
---

# IOTX Token Utility

## Introduction to $IOTX

IOTX通证简介

The IoTeX Network is fueled by the **native IOTX token**. In addition to representing fractional ownership of the IoTeX Network, IOTX has multiple uses \(or “utility”\) to enable trusted and transparent interactions between various stakeholders, including users, Delegates, developers, and service providers. The IOTX token is the lifeblood of the IoTeX protocol and instills economic and reputational incentives to ensure the IoTeX Network is governed/maintained in a decentralized fashion.

IoTeX stakeholders can **spend, stake, and/or burn IOTX** in order to access network resources. As the utility of IOTX grows, the demand and value of IOTX will also grow, providing continued incentives for network participants to maintain and grow the network. As such, IOTX tokenomics are designed to balance incentives across multiple types of stakeholders:

* **Users** pay for DApps/services and stake/vote for Delegates with IOTX
* **Developers** power their devices/DApps and incentives via IOTX
* **Delegates** stake IOTX in order to be eligible to produce blocks
* **Service Providers** offer services to devices/DApps, paid in IOTX



IoTeX拥有自己的原生通证（IOTX），除了象征着对IoTeX网络的部分所有权之外，IOTX还有多种效用，保障IoTeX网络中各主体之间可以实现可信、透明和安全的交互，包括用户、节点、开发人员以及服务提供商等。IOTX 通证是IoTeX网络协议的基石，具备一套完整的经济和声誉激励机制，以确保IoTeX网络以去中心化的方式进行治理和运行。

IoTeX网络的所有参与者可以通过购买、质押和消耗IOTX来访问和使用各种网络资源，随着IOTX通证效用的增加，其需求和价值也将不断增长，持续激励众多参与者支持、维护以及服务IoTeX网络。简而言之，IOTX 的通证经济旨在平衡不同网络参与者之间的激励机制，包括：



 •用户：为网络中的DApps和服务付费，并通过质押IOTX为节点投票

•开发者：通过IOTX激励开发人员在IoTeX网络开发设备和DApps

•节点：通过质押IOTX实现共识以及维护网络的安全（生产和验证区块）

•服务提供商：向设备和DApps提供服务，通过IOTX来支付

## $IOTX Utility

**IOTX通证效用**

![Multiple Utility of IOTX Token](../.gitbook/assets/image%20%2814%29.png)

IOTX通证的多种效用

### 1\) Gas Fees

Similar to Ethereum and other Layer 1 blockchains, IoTeX employs a gas fee model, where “gas” is paid by users in proportion to the computational capacity required to process a transaction or smart contract. Unlike other blockchains, the “users” of the IoTeX platform are not limited to only people, but also machines/devices. In the IoTeX Network, both humans and machines/devices will have the ability to send payments, access smart contracts, and even charge for services. Machines will be equipped with wallets \(just like a human user\) and execute automated payments, data transfers, and more based on pre-programmed smart contracts.



1）交易费用

与以太坊和其他L1区块链类似，IoTeX采用Gas Fee（ 燃料费）模式，基于用户处理交易或智能合约所需的算力来支付费用。与其他区块链不同的是，IoTeX平台的“用户”不仅仅包括人，还包括机器和设备。在IoTeX网络中，人类和机器、设备都将有能力发起支付，访问智能合约，甚至收取服务费用。机器会配备钱包\(就像普通用户一样\)，并自动执行支付、数据传输，以及基于预设定智能合约的操作。

### 2\) Network Governance

IoTeX is a decentralized ecosystem that is not owned or governed by any single entity. To facilitate decentralized governance, all IOTX holders are able to stake \(“deposit”\) their IOTX in order to elect Delegates and participate in network-wide votes. Those that stake IOTX also increase the security and fairness of the network — the more IOTX that is staked, the harder it is to attack the network.  


2）网络治理

IoTeX网络是一个去中心化的开放生态系统，不属于任何一个主体。所有社区成员都可以质押IOTX为节点投票，参与去中心化的网络治理。质押的IOTX可以有效提升网络的安全性和公平性。换句话说，质押的IOTX越多，网络就越安全。

![](../.gitbook/assets/image%20%286%29.png)

Delegates perform the important task of managing consensus on behalf of the entire network. IoTeX uses [Roll-DPoS](https://res.cloudinary.com/dokc3pa1x/image/upload/v1559623484/Research%20Paper/Academic_Paper_Yellow_Paper.pdf), an in-house consensus mechanism where 24 of the top 36 voted Delegates are randomly selected to produce blocks every hour. There are currently [60+ Delegates](http://member.iotex.io/) from around the world that are elected by IoTeX stakeholders \(1 staked IOTX = 1 vote, with [bonus votes](https://drive.google.com/file/d/1hw3o3PVohR4E5XFjkX3pQvEc6APdO1pB/view) for pre-defined stake durations\). Ultimately, Delegates receive IOTX rewards for managing consensus, which they often pass on to their voters.

  
节点承担着实现网络共识、维护网络运营的重要责任。IoTeX采用内部开发的Roll-DPoS共识机制，在投票排名前36名的节点中，每小时随机选出24名来生产区块。目前，社区小伙伴们投票选出了60多名来自全球各地的节点（1个IOTX=1票，长期质押可以获得额外投票权）。节点通过达成网络共识来获得IOTX奖励，然后再把这些奖励分给他们的支持者。  

{% hint style="info" %}
For more on staking/voting, see our [Voter Handbook](https://t.iotex.me/voter_handbook).

更多信息，请参阅IoTeX投票人手册：
{% endhint %}

### 3\) Burn-to-Certify for Devices

Enabling trusted human-machine interactions requires trusted, interoperable identities. IoTeX utilizes [decentralized identity \(DID\)](https://github.com/iotexproject/iotex-did), which is registered to the blockchain and enables humans and machines to “discover and be discovered” in the IoTeX Network. Creating a new DID on IoTeX is free — you can think of it as an empty passport. A stamp for your passport is akin to a [verifiable credential \(VC\)](https://github.com/iotexproject/iotex-did#verifiable-credentials), which is a digital credential that grants a DID access to specific resources and services on IoTeX.



3）设备的“用于认证的销毁”

实现可信人机交互需要所有人和机器都具备可信的、可互操作的身份。IoTeX的去中心化身份认证（DID）使用去中心化的方式对设备进行链上注册，让人和机器可以在IoTeX网络中互相发现。在IoTeX网络上注册新的DID是完全免费的，新的DID就像是一本空白护照，而护照上的印章类似于DID的可验证凭证（Verifiable Credential），也就是颁发给DID的电子凭据，授予其特定网络和服务的访问权限。

![](../.gitbook/assets/image%20%2826%29.png)

In the future, device manufacturers will burn IOTX in order to obtain a “Powered by IoTeX” \(PBI\) Certificate, a special VC that allows a device-DID to access useful, device-focused services and capabilities. Under this Burn-to-Certify tokenomics design, the **total supply of IOTX will decrease with every new “Powered by IoTeX” device**, driving increased value for IOTX with every new device.

未来，设备制造商将通过烧毁一定数量的IOTX为设备配置PBI（Powered by IoTeX）证书，这是一种特殊类型的、颁发给DID设备的可验证凭证VC，允许设备访问特定的“由IoTeX赋能”的服务和功能。‌在这种基于设备增长而烧毁的通证经济设计下，随着新的“由IoTeX赋能”设备的增加\(例如Ucam\)，IOTX的总供应量会随之下降，同时也会提高IoTeX网络的活跃度和IOTX通证的价值。

### 4\) Stake-to-Service for Service Providers

IoTeX offers a robust foundation for developers; however, full-stack IoT solutions may require additional capabilities from service providers that offer a specialized service. By facilitating connections to service providers, such as storage and connectivity, IoTeX greatly enhances flexibility and functionality for developers.



4\)为服务提供商设计的“用于服务的质押”

IoTeX为开发人员提供了强大的基础设施和多种实用的开发工具。但是，全栈式物联网的解决方案非常复杂，可能需要特定的服务供应商提供额外的服务。通过促进与服务供应商之间的合作，例如存储和连接等关键功能，IoTeX为开发人员带来了极大的灵活性和功能性。

![Service Provider Ecosystem for Ucam](../.gitbook/assets/image%20%2825%29.png)

To ensure service providers deliver consistent and reliable services to developers, service providers will be required to stake IOTX to obtain the right to provide services in the IoTeX Network. In addition, service providers must define service level agreements \(SLAs\) that detail their specific quality/availability guarantees. Just as Delegates are penalized for failing to produce blocks, service providers that fail to meet their SLAs will have some or all of their stake slashed and reputation damaged.



为了确保服务供应商能够为IoTeX开发人员提供一致并且可靠的服务，每个服务供应商都需要质押IOTX，以便在IoTeX网络中为用户提供服务。此外，服务供应商必须详细披露能证明其服务质量和可用性的服务水平协议\(SLA\)。就像节点会因为不能生产区块而受到惩罚，我们对服务供应商也设置了奖惩机制，未能达到SLA水平的服务供应商将会被处罚部分或全部权益，其声誉也会受到损害。

{% hint style="info" %}
For full details on IOTX utility, see our [detailed blog](https://iotex.medium.com/iotex-tokenomics-part-1-utility-of-the-iotx-token-781ff9c866e3).



更多有关IOTX效用的详细信息，请查阅我们的官方公众号。
{% endhint %}


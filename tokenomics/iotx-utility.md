# IOTX Token Utility

## Introduction to $IOTX

The IoTeX Network is fueled by the **native IOTX token**. In addition to representing fractional ownership of the IoTeX Network, IOTX has multiple uses \(or “utility”\) to enable trusted and transparent interactions between various stakeholders, including users, Delegates, developers, and service providers. The IOTX token is the lifeblood of the IoTeX protocol and instills economic and reputational incentives to ensure the IoTeX Network is governed/maintained in a decentralized fashion.

IoTeX stakeholders can **spend, stake, and/or burn IOTX** in order to access network resources. As the utility of IOTX grows, the demand and value of IOTX will also grow, providing continued incentives for network participants to maintain and grow the network. As such, IOTX tokenomics are designed to balance incentives across multiple types of stakeholders:

* **Users** pay for DApps/services and stake/vote for Delegates with IOTX
* **Developers** power their devices/DApps and incentives via IOTX
* **Delegates** stake IOTX in order to be eligible to produce blocks
* **Service Providers** offer services to devices/DApps, paid in IOTX

## $IOTX Utility

![Multiple Utility of IOTX Token](../.gitbook/assets/image%20%2814%29.png)

### 1\) Gas Fees

Similar to Ethereum and other Layer 1 blockchains, IoTeX employs a gas fee model, where “gas” is paid by users in proportion to the computational capacity required to process a transaction or smart contract. Unlike other blockchains, the “users” of the IoTeX platform are not limited to only people, but also machines/devices. In the IoTeX Network, both humans and machines/devices will have the ability to send payments, access smart contracts, and even charge for services. Machines will be equipped with wallets \(just like a human user\) and execute automated payments, data transfers, and more based on pre-programmed smart contracts.

### 2\) Network Governance

IoTeX is a decentralized ecosystem that is not owned or governed by any single entity. To facilitate decentralized governance, all IOTX holders are able to stake \(“deposit”\) their IOTX in order to elect Delegates and participate in network-wide votes. Those that stake IOTX also increase the security and fairness of the network — the more IOTX that is staked, the harder it is to attack the network.

![](../.gitbook/assets/image%20%286%29.png)

Delegates perform the important task of managing consensus on behalf of the entire network. IoTeX uses [Roll-DPoS](https://res.cloudinary.com/dokc3pa1x/image/upload/v1559623484/Research%20Paper/Academic_Paper_Yellow_Paper.pdf), an in-house consensus mechanism where 24 of the top 36 voted Delegates are randomly selected to produce blocks every hour. There are currently [60+ Delegates](http://member.iotex.io/) from around the world that are elected by IoTeX stakeholders \(1 staked IOTX = 1 vote, with [bonus votes](https://drive.google.com/file/d/1hw3o3PVohR4E5XFjkX3pQvEc6APdO1pB/view) for pre-defined stake durations\). Ultimately, Delegates receive IOTX rewards for managing consensus, which they often pass on to their voters.

{% hint style="info" %}
For more on staking/voting, see our [Voter Handbook](https://t.iotex.me/voter_handbook).
{% endhint %}

### 3\) Burn-to-Certify for Devices

Enabling trusted human-machine interactions requires trusted, interoperable identities. IoTeX utilizes [decentralized identity \(DID\)](https://github.com/iotexproject/iotex-did), which is registered to the blockchain and enables humans and machines to “discover and be discovered” in the IoTeX Network. Creating a new DID on IoTeX is free — you can think of it as an empty passport. A stamp for your passport is akin to a [verifiable credential \(VC\)](https://github.com/iotexproject/iotex-did#verifiable-credentials), which is a digital credential that grants a DID access to specific resources and services on IoTeX.

![](../.gitbook/assets/image%20%2826%29.png)

In the future, device manufacturers will burn IOTX in order to obtain a “Powered by IoTeX” \(PBI\) Certificate, a special VC that allows a device-DID to access useful, device-focused services and capabilities. Under this Burn-to-Certify tokenomics design, the **total supply of IOTX will decrease with every new “Powered by IoTeX” device**, driving increased value for IOTX with every new device.

### 4\) Stake-to-Service for Service Providers

IoTeX offers a robust foundation for developers; however, full-stack IoT solutions may require additional capabilities from service providers that offer a specialized service. By facilitating connections to service providers, such as storage and connectivity, IoTeX greatly enhances flexibility and functionality for developers.

![Service Provider Ecosystem for Ucam](../.gitbook/assets/image%20%2825%29.png)

To ensure service providers deliver consistent and reliable services to developers, service providers will be required to stake IOTX to obtain the right to provide services in the IoTeX Network. In addition, service providers must define service level agreements \(SLAs\) that detail their specific quality/availability guarantees. Just as Delegates are penalized for failing to produce blocks, service providers that fail to meet their SLAs will have some or all of their stake slashed and reputation damaged.

{% hint style="info" %}
For full details on IOTX utility, see our [detailed blog](https://iotex.medium.com/iotex-tokenomics-part-1-utility-of-the-iotx-token-781ff9c866e3).
{% endhint %}


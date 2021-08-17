# Ledger Nano应用程序

硬件钱包[Ledger Nano S](https://www.ledger.com/products/ledger-nano-s)和[Ledger Nano X](https://shop.ledger.com/pages/ledger-nano-x)是区块链领域中公认的安全存储方式。使用Ledger Nano，即使用户在不熟悉（或不受信任）的PC上操作，您的数字资产也是安全的。

### 开始之前

请确保:

* 已安装Ledger Live并处于[可使用状态](https://support.ledger.com/hc/en-us/articles/360006395233-Take-your-first-steps)
* [初始化](https://support.ledger.com/hc/en-us/articles/360000613793?docs=true)您的Ledger Nano设备
* [安装](https://support.ledger.com/hc/en-us/articles/360002731113-Update-Ledger-Nano-S-firmware?docs=true)最新的Ledger固件

### 在您的设备上安装IoTeX Ledger应用程序

为保障设备的正常运行，您需要在设备上安装**IoTeX Ledger应用程序**，生成本地IoTeX帐户以及用于区块链的电子签章。

请按以下说明安装IoTeX Ledger应用程序：

#### 1. 安装并打开官方[Ledger Live](https://www.ledger.com/ledger-live)应用程序；

#### 2. 启用开发者模式



在Ledger Live中，打开“**设置（Settings）**”→ “功能（**Experimental features**）”→ 开启“开发者模式（**Developer mode**）”。

注意：只有在Ledger发布正式版本的IoTeX应用程序之前，才需要此项操作。

#### 3. 将您的Ledger设备连接到Ledger Live

在Ledger Live中，打开“**管理器（Manager）**”，连接并**解锁**您的Ledger Nano设备：

![&#x8FDE;&#x63A5;&#x5E76;&#x89E3;&#x9501;&#x60A8;&#x7684;&#x8BBE;&#x5907;](../.gitbook/assets/image%20%2822%29.png)

#### 4. 允许账本管理器（Ledger Manager）访问您的设备

  
 您需要在设备上点击 “允许账本管理器（_Allow Ledger Manager）_”：同时点击设备上的两个按钮即可：

![&#x5141;&#x8BB8;&#x8D26;&#x672C;&#x7BA1;&#x7406;&#x5668;&#x8BBF;&#x95EE;&#x60A8;&#x7684;&#x8BBE;&#x5907;](../.gitbook/assets/image%20%284%29.png)

#### 5. 安装IoTeX Ledger应用程序   在Ledger Live “**管理器（Manager）**”中，选择“应用程序目录（**App Catalog**）”，在应用程序中找到“IoTeX”，然后单击旁边的“安装（Install）”：

![&#x5728;App catalog&#x4E2D;&#x627E;&#x5230;&#x5E76;&#x5B89;&#x88C5;IoTeX App ](../.gitbook/assets/image%20%283%29.png)

随后将会弹出安装窗口，设备上将显示“正在处理…（Processing）”，等待应用程序安装完毕即可。

### 连接Ledger Nano与ioPay桌面钱包

You can use the IoTeX “[ioPay Desktop](http://iopay.iotex.io/desktop)” wallet with your Ledger device: it supports transfers of native IOTX coins, transfers of XRC20 tokens, staking actions and execution of smart contacts. See the instructions below to connect your Ledger Nano to ioPay Desktop wallet app:

IoTeX的[ioPay桌面钱包](https://iopay.iotex.io/desktop)可以与Ledger设备一起使用，支持IOTX原生通证、XRC20通证的转换、质押以及智能合约的执行。详情请参阅以下说明：  


1.[安装](https://iopay.iotex.io/desktop)并打开ioPay桌面钱包应用程序

2.连接并解锁您的Ledger Nano设备

3.在您的Ledger设备中打开IoTeX应用程序

4.首次连接可能会提示您输入新的IoTeX地址，如下图所示：

![](https://lh3.googleusercontent.com/WvHSmtJ5vHpHluwDl-Esu19WAjsG9aC2dOkhUr_AHUZ8ad7qKV-fRYs1yk04rKiZDUoAiOzOW0QjrU-Xj6OY7ul-KlbZgArL12AyW0chXrd9NSZY68nnJYXD0C7JfVdGcrLetUgw)

之后您可以随时查看此地址。

1. 在Ledger Nano设备上确认IoTeX地址，您可以点击右边按钮（针对Nano S）或同时点击两个按钮（针对Nano X）；
2. 在ioPay桌面钱包中，选择“连接账本（Connect Ledger）”，然后单击“解锁（Unlock）”即可：

![](https://lh4.googleusercontent.com/_MFZ0ENQgKcsQovOGAWdF3b6z44zC_v2tEI6yhSkTQsNVci-1u5LZZYeNzngCTfjPYpg-WjFfOoN8ewFHPdd-7RaiAVec6SNxq72k9vN0kr4GrB7VJhf6v6A97CyIT8iKoabzM5L)

### 查询您的IOTX余额

使用Ledger设备解锁ioPay钱包后，您可随时在ioPay中查询Ledger设备的IoTeX地址以及您的IOTX余额：

![](https://lh3.googleusercontent.com/ktOGXghs6iRKY_mKRpDni0QMo5vtWyvqapj0gBomtvTm8xdPXnjgkmTfugc1tpJXLoAaGAVY-buQc5Au8lqgKWua7JGtPErOx-EPHJPlw9cmxPWeAYWfv_Z5v22njQlrnjp7WmRo)

### 查询您的XRC20通证余额

IoTeX是一个兼容EVM的智能合约平台，支持L2通证。IoTeX的通证标准与以太坊的通证一致：IoTeX上的XRC20和XRC721通证标准相当于以太坊上的ERC20和ERC721。如果您的Ledger Nano帐户中持有XRC20通证，可以在ioPay中查询余额：只需单击“添加通证（Add Token）”，选择XRC20通证（或输入通证合约地址），这样您就可以随时在XRC20通证界面中查看余额：

![](https://lh6.googleusercontent.com/-mI8jbexZQs1gbeQfQkvpTrm9_zyDTT5qLjQnBRGnOhup-tim_XhT01OXgmqAHOnyFd1_7BiIKISAS0JGJOrMObPjm_RpEIDIsIYaNH8fmq2rhaVJ1_grOXk-ntO24v0M0pCJDmq)

### 通过Ledger设备发送IOTX通证

发送IOTX通证非常简单，只需点击“发送（Send Action）”，填写所需信息（收件人地址和金额），然后点击“发送（Send）”，并在Ledger设备上签名确认即可：

![](https://lh3.googleusercontent.com/wk5XRIodJJQyMhGHo6PYTw_vouR5EmQMv_bLyYUPeqEFislfyUw__V6Ue52EjMnXGjTD0oPPRW1dO5mtaszk5MoMDVqfc70Jjs6itkoGxThKkQO27kgXsdrNG-Uqi0mJUmJ0cLUp)

您的Ledger Nano设备会自动显示转账信息，如金额、收件人地址、交易费用等。

![](https://lh6.googleusercontent.com/nt1oFG2VAPFBmxTg1dtDwk4Y9K6Hh0YicDdD7C8_GnABKX0oPGTP1rfqZ7MXC7Uq9tKgVSZgAllWo-Z_2FF9F1-ANn0YtKSu983QzOTSyHtzlJpd6AI0f6YEIvSk7eaxfQ4hFR40)

通过点击左右按钮切换不同界面，并查看交易详细信息。确认之后，同时按下两个按钮“签署交易（Sign transaction）”。

### 通过Ledger设备与智能合约交互

可以通过Ledger设备与智能合约轻松进行交互。点击“智能合约（Smart Contracts）”，然后选择“与合约进行交互（Interact with contract）”：

![](https://lh5.googleusercontent.com/qV1wKEPxiJLT47AXP74RE1SiJmgRlzN5w2iPalh7cxg8Pb-KidxM4CcpafUY2v7-hMJBRyfrZVxr2aKoYjgdUFJDFtX2YCb2JX17y9M3TKVUzlke7ZFyNVw-CB3yD0WodEv_BWQz)

在智能合约一栏（Smart Contract tab）中填写所需信息（合约地址、金额、ABI等），然后单击“访问（Access）”，界面会显示可使用合约的列表：

![](https://lh5.googleusercontent.com/23VXvjTl4RKGRZsu88IB_QlFgI6hE_t60qgnVTdSn8bdEMSrle9PdlyE6E8N4cb19JH_DNYAsCQ5LUXAOn40v0q5c3e40Ie8i20zbgrV6Mv6N5JYbLKrTqsNWsTUcGm2_19XGCY_)

选择您要使用的合约，填写所需参数（如果有），然后单击“执行合约（write contract）”进行确认：

![](https://lh3.googleusercontent.com/10weokz7PpI1hAwJ4ZPldScyJktmrp6HP-Is8y2AE3s2gAh7cV8OS0vxVhgL0_FIafejsBv3T8bS_yILFBTesDG2Sw3TbUYDtxRKh76HAfa_JSxj4krWM11OLzFBO2leZJlO2BW6)

在ioPay中确认操作后，您的Ledger Nano会自动显示操作信息供您核实。确认信息无误后，自动跳转到“签署交易（Sign Transaction）”或“拒绝交易（Reject Transaction）”界面，然后同时点击两个按钮确认交易。一经确认，Ledger Nano将对交易进行签名，并将信息发回给ioPay以便在网络中传播。

### 结语

 ioPay桌面钱包下载地址：[ioPay.IoTeX.io/Desktop](https://iopay-wallet.iotex.io/)。

如果您对Ledger设备或ioPay桌面钱包有任何疑问，请随时联系我们[support@iotex.io](mailto:support.iotex.io).


# Ledger Nano app

[Ledger Nano S](https://www.ledger.com/products/ledger-nano-s) and [Ledger Nano X](https://shop.ledger.com/pages/ledger-nano-x) are hardware wallets, which are considered very secure for the storage of **private keys **in the blockchain world. When using a hardware wallet like Ledger Nano, your digital assets are safe even when operating on a compromised (or untrusted) PC.

### Before you begin

Please make sure that:

* Ledger Live is [installed and ready to use](https://support.ledgerwallet.com/hc/en-us/articles/360006395233-Take-your-first-steps)
* You have [initialized](https://support.ledgerwallet.com/hc/en-us/articles/360000613793) your Ledger Nano Device
* The latest Ledger firmware is [installed](https://support.ledgerwallet.com/hc/en-us/articles/360002731113-Update-Ledger-Nano-S-firmware)

### Install the IoTeX Ledger App on your device

The **IoTeX Ledger App** needs to be installed on your device to allow it to generate a native IoTeX account and sign blockchain actions.&#x20;

Follow the instructions below to install the IoTeX Ledger App:

#### 1. Install and open the official [Ledger Live ](https://www.ledger.com/ledger-live)application.

#### 2. Connect your Ledger device to Ledger Live

In Ledger Live, open the "**Manager"**, then connect and **unlock** your Ledger Nano device:&#x20;

![Connect and unlock your device](<../.gitbook/assets/image (22).png>)

#### 3. Allow Ledger Manager on your device

You may be asked to “_Allow Ledger Manager_” on your device: do so by clicking both buttons on your device:

![Allow Ledger Manager on your device](<../.gitbook/assets/image (4).png>)

#### 4. Install the IoTeX Ledger App

In Ledger Live "**Manager"** section, select the “**App Catalog**” tab, find “_IoTeX_” among the apps  and click the “Install” button next to it:

![Find and install the IoTeX App in the App catalog ](<../.gitbook/assets/image (3).png>)

An installation window will appear and your device will display _“Processing…”: _just wait until the app installation is confirmed.

### Connect Ledger Nano to ioPay Desktop Wallet&#x20;

You can use the IoTeX “[ioPay Desktop](http://iopay.iotex.io/desktop)” wallet with your Ledger device: it supports transfers of native IOTX coins, transfers of XRC20 tokens, staking actions, and execution of smart contacts. See the instructions below to connect your Ledger Nano to ioPay Desktop wallet app:

1. [Install](http://iopay.iotex.io/desktop) and open ioPay Desktop wallet app
2. Connect and unlock your Ledger Nano device
3. On your Ledger device open the IoTeX app&#x20;
4. The first time you may be prompted with your new IoTeX address, as shown in the picture below:&#x20;

![](<../.gitbook/assets/image (58).png>)

You can review this address later at any time.

1. On your Ledger Nano device, go past the IoTeX address screen by pressing the right button (on the Nano S) or both buttons (on the Nano X) to confirm.
2. In ioPay Desktop wallet, select the tab “Connect Ledger”, then click “Unlock”:

![](https://lh4.googleusercontent.com/\_MFZ0ENQgKcsQovOGAWdF3b6z44zC\_v2tEI6yhSkTQsNVci-1u5LZZYeNzngCTfjPYpg-WjFfOoN8ewFHPdd-7RaiAVec6SNxq72k9vN0kr4GrB7VJhf6v6A97CyIT8iKoabzM5L)

### Check your IOTX balance

Once you unlocked your ioPay wallet using the Ledger Device, ioPay will conveniently show you the IoTeX address of your Ledger device, along with your IOTX balance:

![](https://lh3.googleusercontent.com/ktOGXghs6iRKY\_mKRpDni0QMo5vtWyvqapj0gBomtvTm8xdPXnjgkmTfugc1tpJXLoAaGAVY-buQc5Au8lqgKWua7JGtPErOx-EPHJPlw9cmxPWeAYWfv\_Z5v22njQlrnjp7WmRo)

### Transfer IOTX tokens through Ledger device

Sending IOTX tokens is extremely easy. Just select the “Send Action” tab, fill in the required data (recipient address and amount), and click the “Send” button to request your Ledger device to sign:

![](https://lh3.googleusercontent.com/wk5XRIodJJQyMhGHo6PYTw\_vouR5EmQMv\_bLyYUPeqEFislfyUw\_\_V6Ue52EjMnXGjTD0oPPRW1dO5mtaszk5MoMDVqfc70Jjs6itkoGxThKkQO27kgXsdrNG-Uqi0mJUmJ0cLUp)

Your Ledger Nano device will automatically display the transfer information such as the amount, the recipient address, the gas price, etc.

![](<../.gitbook/assets/image (61).png>)

Press the left and right buttons to move between each screen and review all the transaction details. After reviewing the details, you can move to the “Sign transaction” screen, and press both buttons to confirm and sign the transaction.&#x20;

### Check your XRC20 tokens balance

IoTeX is an EVM-compatible, Smart Contract platform therefore it supports “Layer 2” tokens defined as smart contracts. IoTeX defines token standards fully equivalent to those available on Ethereum: XRC20 and XRC721 tokens on IoTeX play the same role of ERC20 and ERC721 standards on Ethereum. If you own any XRC20 tokens in your Ledger Nano account, you can check your token balance in ioPay: just click the “Add Token” button to select the XRC20 token you are interested in (or input the token contract address if you know it) and the balance will be permanently added in the XRC20 tokens panel:

![](https://lh6.googleusercontent.com/-mI8jbexZQs1gbeQfQkvpTrm9\_zyDTT5qLjQnBRGnOhup-tim\_XhT01OXgmqAHOnyFd1\_7BiIKISAS0JGJOrMObPjm\_RpEIDIsIYaNH8fmq2rhaVJ1\_grOXk-ntO24v0M0pCJDmq)

### Transfer XRC20 tokens through Ledger device

Since the IoTeX Ledger App settings don't support contract executions by default, you must first enable this setting before you can transfer XRC20 tokens using your ledger device:

1. Unlock your Ledger device
2. Navigate to the _IoTeX_ app and open it
3. Navigate to the _App Settings_ menu
4. Navigate to _`Allow Contract Data`_ and enable it
5. Confirm the _Contract Data_ menu

Finally, make sure you[ added the token to the XRC20 tokens list](ledger-nano-app.md#check-your-xrc20-tokens-balance) in ioPay, and that you **selected the correct token in the Amount **field before sending:

![](<../.gitbook/assets/image (64).png>)

### Interact with a contract through Ledger device

Since the IoTeX Ledger App settings don't support contract executions by default, make sure you enabled this setting as explainde in the [XRC20 transfer section](ledger-nano-app.md#transfer-xrc20-tokens-through-ledger-device).

In ioPay Desktop, select the “Smart Contracts” tab, and then select “Interact with contract”:

![](https://lh5.googleusercontent.com/qV1wKEPxiJLT47AXP74RE1SiJmgRlzN5w2iPalh7cxg8Pb-KidxM4CcpafUY2v7-hMJBRyfrZVxr2aKoYjgdUFJDFtX2YCb2JX17y9M3TKVUzlke7ZFyNVw-CB3yD0WodEv\_BWQz)

fill in the required  information in the Smart Contract tab (contract address, value to send, ABI, etc…)  and click the “Access” button to get the list of available contract methods:

![](https://lh5.googleusercontent.com/23VXvjTl4RKGRZsu88IB\_QlFgI6hE\_t60qgnVTdSn8bdEMSrle9PdlyE6E8N4cb19JH\_DNYAsCQ5LUXAOn40v0q5c3e40Ie8i20zbgrV6Mv6N5JYbLKrTqsNWsTUcGm2\_19XGCY\_)

Now select the contract method to call, fill in the required arguments if any, and click “write contract” to execute the call:

![](https://lh3.googleusercontent.com/10weokz7PpI1hAwJ4ZPldScyJktmrp6HP-Is8y2AE3s2gAh7cV8OS0vxVhgL0\_FIafejsBv3T8bS\_yILFBTesDG2Sw3TbUYDtxRKh76HAfa\_JSxj4krWM11OLzFBO2leZJlO2BW6)

After you confirm the action in ioPay, your Ledger Nano will automatically present the action information for you to review. Make sure those information are correct and navigate to either the “Sign Transaction” or “Reject Transaction” screens, then click both buttons to confirm your choice. If you confirm, the Ledger Nano will sign the transaction and send it back to ioPay for network broadcast.

### Final Notes

IoTeX “ioPay Desktop” wallet is available at [iopay.iotex.io/desktop](https://iopay.iotex.io).&#x20;

If you encounter any issue with your Ledger device or with the ioPay desktop wallet, please drop us a line at [support@iotex.io](mailto:support.iotex.io).

# Beam wallet

## Description 

**Beam wallet** is a simple console application that allows you easily **make transactions** between two wallets.

To get started you will need:

* your wallet data:

  * **address,**
  * **passphrase,**
  * **keystore file,**

  \*\*\*\*

* **address** to which you want to transfer ETH.

## Running application

To run application open **Nethermind.BeamWallet** file.

After that you should be able to see this window: 

\(Colors of the application may vary from those shown in the pictures - it depends on your command line settings.\)

![](../.gitbook/assets/image%20%2891%29.png)

1\) The first input is the address of the **node** that you will connect to. Address of our node is **http://localhost:8545** and the value will be already provided.

2\) And in the second input you must provide **address** of your wallet - the one you want to transfer ETH from.

![](../.gitbook/assets/image%20%2883%29.png)

3\) Using the TAB key, move to the **OK** button and press Enter.

![](../.gitbook/assets/image%20%2889%29.png)

After a while caption "Syncing... Please wait for the updated balance." should change to your wallet balance and also the **QUIT** and **TRANSFER** buttons will appear. This may take a few minutes.

![](../.gitbook/assets/image%20%2887%29.png)

4\) And again, use the TAB key, move to the **TRANSFER** button and press Enter.

## Making transaction

You will see a different window where you can provide data to make the transfer.

![](../.gitbook/assets/image%20%2884%29.png)

5\) In the first input provide the **address** to which you want to send ETH.

6\) In the input below enter the **value** of ETH that you want to transfer.

7\) And in the last input enter the **passphrase** of your wallet.

{% hint style="info" %}
Before making a transaction make sure that Keystore file of your wallet is located in the **keystore** folder. It is necessary to properly unlock your account before sending the transaction. Otherwise unlocking your account will be failed.
{% endhint %}

8\) Move to the **TRANSFER** button and press ENTER. \(This is not the last step, you will be asked to confirm the transaction.\)

![](../.gitbook/assets/image%20%2885%29.png)

9\) After that, a modal with summary of the transaction will appear. Confirm \(or not\) sending the transaction.

![](../.gitbook/assets/image%20%2886%29.png)

The steps that will be taken to send the transaction will be listed below.

![](../.gitbook/assets/image%20%2888%29.png)



\*\*\*\*



\*\*\*\*








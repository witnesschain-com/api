# Flow 
![flow](https://github.com/witnesschain-com/api/assets/108800133/096b891d-082c-447e-8958-6f068b20dba8)

# Signatures

on browser can be done using Metamask as:

```js
signedMessage = await ethereum.request ({
    method : 'personal_sign',
    params : [messageToSign, publicKey],
});
```

The `messageToSign` comes from the coordinator as response of `/pre-login` api.

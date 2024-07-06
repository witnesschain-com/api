# Flow 
![flow](https://github.com/witnesschain-com/api/assets/108800133/30fb0b3d-fd78-4702-a87f-9b905d629fb5)

# Signatures

on browser can be done using Metamask as:

```js
signedMessage = await ethereum.request ({
    method : 'personal_sign',
    params : [messageToSign, publicKey],
});
```

The `messageToSign` comes from the coordinator as response of `/pre-login` api.

# APIs

Please check [APIs](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/Proof-of-X/Proof-of-Backhaul/main/api.json)

# Flow 
![flow](https://github.com/witnesschain-com/api/assets/108800133/3194eb7d-a79b-427b-8bf6-73917faed96d)

# Signatures

on browser can be done using Metamask as:

```js
signedMessage = await ethereum.request ({
    method : 'personal_sign',
    params : [messageToSign, publicKey],
});
```

The `messageToSign` comes from the coordinator as response of `/pre-login` api.

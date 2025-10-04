# e2ev2
An end to end encryption tool in a single html file. (e2ev2 stands for End 2 End v2. v1 was vibecoded and I am ashamed to admit so.)

# How to use
Exchange your public key with whoever you are chatting with. After that type your message and press encrypt to encrypt and decrypt to... decrypt.

Optionally:
[Click Here to Go to Website](https://cuhassle.github.io/e2ev2/e2ev2.html)

# Note
This has NO backend whatsoever so you will have to use an already existing backend like google chat. This project was originally intended to be used to securely send messages on google chat.

# PS
This is NOT completely safe. One problem with the web is that any browser extension can spy on you while you are typing.

# How it Works
(For the 1 person who actually cares) This uses the elliptical curve diffie hellman algorithm to exchange a key which is then used for AES-GCM symmetric encryption.

# TODO
I should: add double ratchet algorithm (changes the shared secret every time), add message history, add ability to close chats

# Credits
Me, somebody on [TN](https://discord.gg/unblock) named [gkgoat](https://github.com/gkgoat1) for support (THANK YOU SO MUCH). Also whoever made the crypto api and these functions: arrayBufferToBase64 base64ToArrayBuffer 

# GUARANTEED NO VIBECODING OR AI.
(Clearly its not vibecoded, look at commits, SCARATEK.)

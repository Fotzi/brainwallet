# brainwallet
Fotzi's Brainwallet generator.

Do not use that if you do not exactly know what you are doing. 
By using this genrator you are agreeing to the following terms and conditions.
The generator is provided on an "as is" basis, without any warranties.
We are not responsible for any losses in bitcoin that you may incur for any reason.

Basic description:
You have to adjust "mypersonalsaltgoeshere" in the code to something personal.<br />
Then, you can run the generator with a secret, like this "./addr correcthorsebatterystaple".<br />
It will combine your salt and your secret and create a brain wallet out of it. For that, the generator uses a pbkdf2 hmac scheme with 100000 iterations of sha256. But still, using an easy secret and/or salt will result in lost bitcoins (!!!!). 

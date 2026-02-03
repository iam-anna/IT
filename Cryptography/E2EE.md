### What is end-to-end encryption?
End-to-end encryption (E2EE) because it is impossible for anyone for anyone to intercept an decrypt the message. Users do not need to trust that the service will not read their messages: it is not possible for the service to do so.

### How it works?
With E2EE, the key that can encrypt and decrypt messages remais saved on a user's device. If Alice and Bob use an E2EE messaging app, the app saves a key on Alice's phone and the key on Bob's phone. Alice's phone encrypts her message with the key, then sends the encrypted message to Bob's phone. Bob's phone automatically applies the key and decrypts the message, allowing Bob to read it.

### What kind of encryption does E2EE use?
End-to-end encryptions uses *asymmetric encryption*. Which enables two parties to communicate without having to share the secret key over an insecure channel.

Asymmetric key encryption relies on using two keys instead of one: a public key and a private key. While anyone, including the messaging service, can view the public key, only one person has access to the private key. Data 
encrypted with the public key can only be decrypted with the private key.
### How does end-to-end encryptions support privacy?
E2EE ensures that no one can see messages except for the two people who are communication with each other. When implemented properly, it does not require users to trust that a service will handle their data properly. Thus, E2EE gives people total control over who can read their messages.

### What are the limitations of end-to-end encryption?
E2EE ensures protection over messages in transit. But it does not protect messages once they reach their destination. For example, if the device gets compromised (stolen or infected with malware), the messages would be vulnerable.
### E2EE Protocolos
Signal Protocol
Threema
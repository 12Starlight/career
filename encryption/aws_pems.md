# **AWS Pems**

### **Amazon EC2 key pairs and Linux Instances**

A key pair, consisting of a private key and a public key, is a set of secrity credentials that you use to prove your identity when connecting to an instance. Amazon EC2 stores the public key, and you store the private key. You use the private key, instad of a password, to securely access your instances. Anyone who possesses your private keys can connect to your instances, so it is important that you store your private keys in a secure place.

When you launch an instance, you are [promted for a key pair](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/launching-instance.html#step-7-review-instance-launch). If you plan to connect to the instance using SSH, you must specify a key pair. You can chose an existing key pair or create a new one. When your instance boots
# **AWS Pems**

### **[Amazon EC2 key pairs and Linux Instances](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-key-pairs.html)**

A key pair, consisting of a private key and a public key, is a set of secrity credentials that you use to prove your identity when connecting to an instance. Amazon EC2 stores the public key, and you store the private key. You use the private key, instad of a password, to securely access your instances. Anyone who possesses your private keys can connect to your instances, so it is important that you store your private keys in a secure place.

When you launch an instance, you are [promted for a key pair](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/launching-instance.html#step-7-review-instance-launch). If you plan to connect to the instance using SSH, you must specify a key pair. You can chose an existing key pair or create a new one. When your instance boots for the first time, the content of the public key that you specified at launch is placed on your Linux instance in an entry within `~/.ssh/authorized_keys`. When you connect to your Linux instance using SSH, to log in you must specify the private key that corresponds to the public key content. 

&nbsp;

### **[Use an Amazon EC2 Key Pair for SSH Credentials](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-plan-access-ssh.html)**

Amazon EMR cluster nodes run on Amazon EC2 instances. You can connect to cluster nodes in the same way that you can connect to Amazon EC2 instances. You can use Amazon EC2 to create a key pair, or you can import a key pair. When you create a cluster, you can specify the Amazon EC2 key pair that will be used for SSH connections to all cluster instances. You can also create a cluster without a key pair. This is usually done with transient clusters that start, run steps, and then terminate automatically.

The SSH client that you suse to connect to the cluster needs to use the private key file associated with this key pair. This is a .pem file for SSH clients using Linux, Unix, and macOS. You must set permissions so that only the key owner has permission sto access the file. See above to create an Amazon EC2 Key Pair. 

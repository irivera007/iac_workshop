# Set up puppet master

These are the files used to spin up the puppet master. 

They are included to give additional terraform examples.


Firewalls: The Puppet master server must allow incoming connections on port 8140, and agent nodes must be able to connect to the master on that port.


## Connect to Puppet master

```
ssh root@188.166.44.24 -i ~/.ssh/do_terra_rsa
```

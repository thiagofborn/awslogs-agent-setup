# awslogs-agent-setup
Use at your own risk. 

Public Domain - Do whatever you want with the code. Period. No need to mention me ever again. You can forget I ever existed.

You can find the original code at: https://s3.amazonaws.com/aws-cloudwatch/downloads/latest/awslogs-agent-setup.py

### How to use: 
```
sudo python awslogs-agent-setup.py --region us-east-1 --http-proxy http://your/proxy --https-proxy http://your/proxy --no-proxy 169.254.169.254
```

### Installing on a local host no proxy: 
```
sudo python awslogs-agent-setup.py --region us-east-1 --no-proxy 169.254.169.254
```




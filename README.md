# Commandbox-Corretto
Running ColdFusion on Corretto

# 1. Go get Corretto

https://aws.amazon.com/corretto/

# 2. Install it

It will be installed into:

`/Library/Java/JavaVirtualMachines/amazon-corretto-8.jdk/Contents/Home/lib/jvm/openjdk8-preview`


# 3. Change `server.box`

As shown. 

Type `box`
Type `start`

And for me nothing happened

# 4. Install XQuartz

https://www.xquartz.org/

Install

Restart Computer

# 5. Try it again

Type `box`
Type `start`

Good news it works

Bad news, the port specification does not work.


# Resources

- https://commandbox.ortusbooks.com/embedded-server/server.json
- https://github.com/OpenKinect/libfreenect/issues/503
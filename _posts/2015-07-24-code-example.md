---
layout: post
title: Code fencing example.
---

This is an example of code fencing

{% highlight Bash %}

#!/bin/bash

# Enable SSH
systemsetup -setremotelogin on

# Tilføj com.apple.access_ssh group
dseditgroup -o create -q com.apple.access_ssh

# Tilføj Admin group til com.apple_access_ssh
dseditgroup -o edit -a admin -t group com.apple.access_ssh
{% endhighlight%}

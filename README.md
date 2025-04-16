# Remote_Huawei

```<AccessControl AccessControlListEnable="1" AccessControlListNumberOfEntries="1">
<List NumberOfInstances="1">
<ListInstance InstanceID="1" SrcPortType="2" SrcPortName="ALL" SrcIp="" ServicePort="TELNET,HTTP,SSH" SrcMac="" ServiceProto="" ServiceProtoPort="" Priority="1" Mode="0" DynamicWanServiceType=""/>
</List>
```
![alt text](https://github.com/beryindo/Remote_Huawei/blob/main/2024-04-15_021007.jpg)



# EG8141H5
```
<AclServices HTTPLanEnable="1" HTTPWanEnable="0" FTPLanEnable="0" FTPWanEnable="0" TELNETLanEnable="1" TELNETWanEnable="0" SSHLanEnable="1" SSHWanEnable="0" HTTPPORT="80" FTPPORT="21" TELNETPORT="23" SSHPORT="22" HTTPWifiEnable="1" TELNETWifiEnable="1">
<X_HW_RemoteAccess Enable="0" Port="" Protocol="" SupportedProtocols="HTTP,HTTPS,TELNET,FTP"/>
<X_HW_LocalAccess Enable="1" Port="80,443" Protocol="HTTP,HTTPS" SupportedProtocols="HTTP,HTTPS,TELNET,FTP"/>
<AccessControl AccessControlListEnable="1" AccessControlListNumberOfEntries="1">
<List NumberOfInstances="1">
<ListInstance InstanceID="1" SrcPortType="0" SrcPortName="ALL" SrcIp="" ServicePort="" SrcMac="" ServiceProto="ICMP,ICMPV6,TCP,UDP" ServiceProtoPort="80,22,23" Priority="1" Mode="0" DynamicWanServiceType=""/>
</List>
</AccessControl>
</AclServices>
```

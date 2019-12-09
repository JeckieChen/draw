### IPv6的优势：  
1.扩展的地址空间：提供了128位的源地址和目的地址，相比与ipv4的32位地址  
2.IPv6不但有更大的地址空间，它还改变了IP协议的一些重要部分  
3.无状态自动配置：IPv6提供了配置机制，主机可以自生成一个可路由的地址  
4.nat/pat将消失：由于公众的ipv6地址数量庞大，将不再需要网络地址/端口地址翻译  
5.消除广播：IPv6不使用3层的广播地址  
  
### IPv6报文  
* version版本（4bits）：值为6
* traffic class流量类型（8bits）
* flow label 流标签（20bits）：用来标记的序列或IPv6数据包从一个源发送到一个或多个目的节点的数据包流
* payload length净荷长度（16bits）：允许一个65535字节的最大有效载荷大小
* next header下一报头（8bits）
* hop limit跳数限制（8bits）
* source address源地址（128bits）：
  ipv6数据包的IP地址是128位
  源地址必须是一个单播地址
* destination address目的地址（128bits）：
  128位的IP地址
  可以是一个单播或组播地址
  没有广播地址，这是一个所有节点的组播地址

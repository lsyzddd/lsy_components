要求传入的数组长度为3或者0

使用方式请参考：https://vux.li/#/zh-CN/components?id=xaddress

本组件简单的二次组合，支持异步获取地址码或者地区后，通过组件反向转换得到地区或者地址码.

比如传入['430000', '430400', '430407']那么可以通过 @on-get-addressNames拿到对应的省市区

比如传入['广东省', '广州市', '天河区']那么可以通过 on-get-addressIds拿到对应的地址码

前提是必须使用最新的vux的官方组件

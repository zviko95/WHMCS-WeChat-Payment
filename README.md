# WHMCS-WeChat-Payment

[![Join the chat at https://gitter.im/frankwei98/WHMCS-WeChat-Payment](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/frankwei98/WHMCS-WeChat-Payment?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
很惭愧，就做了一点微小的工作，谢谢大家。
安装方法:上传wechatpersonal.php到 /whmcs安装目录/modules/gateways/ 即可
#为什么写这个？
1、支付宝强行社交化 

2、Android版全家自启 

3、支付宝把电脑版的生活转账功能关闭了

4、基本上每个人都会把微信挂在后台吧？这样到账就可以即时通知了

#原理
提供二维码给用户 让用户通过微信转账

# 目前的缺点？
1、这是初步的版本 仅在WHMCS 6.0测试通过（理论上兼容 毕竟那么简单）

2、目前还是人工审核订单

#希望能实现
1、我需要读取订单号后2位数做验证码（比较现实）

2、接入微信支付API，实现自动化（我正在读高三 没时间 也没能力写 除非等我读大学 有空了 才想接入微信支付体系吧）

# wechatTweak
免越狱iOS设备可以安装自动抢红包的软件所需文件

libsubstrate.dylib 动态链接库是越狱机器上面用来更换内存的代码，未越狱机器没有该文件，我们需要将这文件注入到越狱应用的二进制文件中。

WeChatRedEnvelop.dylib 动态链接库是在github 上面找的开源的自动抢红包插件[免越狱版 iOS 抢红包插件](http://www.swiftyper.com/2016/12/26/wechat-redenvelop-tweak-for-non-jailbroken-iphone/) 编译生成的。

微信-6.6.6(越狱应用).ipa 文件是在pp助手越狱应用市场下载的砸过壳的ipa文件，wechatTweak 文件夹是该ipa 解压之后生成的。

我们可以直接使用的是目录 wechatTweak > Payload > Wechat 这个应用程序，然后通过 ios-app-signer 来生成自己证书签名的ipa 文件。

目录 wechatTweak > Payload > Wechat.ipa 即是使用我自己证书重签名的ipa文件。

详细安装过程见我写的文章： https://www.jianshu.com/p/5d10e03f6f62



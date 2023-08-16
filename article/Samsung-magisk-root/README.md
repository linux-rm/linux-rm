# 三星手机 magisk+root (中文,Chinese)
# Samsung Smartphones magisk+root (English,英文)

示例手机型号/Example phone model:

Samsung Galaxy S21

## `!!!!!!警告!!!!!!Warning!!!!!!`
> > ))) 手机一但root,你会拥有手机所有权,但如果操作不当,就会造成`系统不正常`,`丢失数据`甚至变成`"砖块"`.
> >
> > ))) 三星手机root前必须`解锁bootloader(BL),退出三星账户和google账户`.非中国国行的三星手机可能还需要解锁`KG锁/网络锁`(请自行查阅资料).
> > ))) 三星手机解锁bootloader后会`物理熔断` [knox](https://samsung.com/security),导致三星钱包不可用,失去保修和安全文件夹不可用,并`清除数据`.
>
> > ))) Once the phone is rooted, you will have the ownership of the phone, but if it is not operated properly, it will cause the `system to be abnormal`, `lose data` or even become a `"brick"`.
> >
> > ))) Samsung phones must unlock bootloader(BL) before rooting, exit Samsung account and Google account.Samsung phones that are not CHC may also need to unlock the `KG lock/network lock` (please consult the information by yourself).
> >
> > ))) Samsung phone will `physically fuse` [knox](https://samsung.com/security) after unlocking bootloader, resulting in Samsung pay unavailability, loss of warranty and unavailability of secure folders, and `clearing of data`.
---

# 开始/Begining
## 1. 备份/backup
> ||| 经过本人测试,[三星云](https://support.samsungcloud.com)在root后仍可以`正常使用`,所以你可以使用三星云进行备份,但`应用数据会丢失`.(包括账户信息,游戏进度,聊天记录等)
>
> ||| After my own test, [Samsung Cloud](https://support.samsungcloud.com) can still be `used normally` after rooting, so you can use Samsung Cloud for backup, but `application data will be lost`. (including account information, game progress, chat history, etc.)
>
> <img src="备份.png" width="25%" /> <img src="三星云.png" width="25%" />

## 2. `退出账户/logout(非常重要/very important)`
> <img src="退出账户.png" width="25%" />

## 3. 解锁/unlock
> ||| 设置 -> 开发者选项(关于手机 -> 软件信息 -> 编译编号_3次) -> 允许OEM解锁
>
> ||| Settings -> Developer options(About phone -> Software information -> Build number_3 times) -> OEM unlocking
>
> <img src="关于手机.png" width="20%" /><img src="软件信息.png"  width="20%" /><img src="编译编号.png" width="20%" /><img src="开发者选项.png" width="20%" /><img src="OEM解锁.png" width="20%" />


> 关机/Poweroff
>
> <img src="button/s-.svg" width="10%" /><img src="button/7s.svg" width="10%" /> <img src="关机.png" width="30%" />

> 解锁bootloader/unlock bootloader
>
> <img src="button/USB.svg" width="10%" /> <img src="button/+-.svg" width="10%" /><img src="button/7s.svg" width="10%" /><img src="warning.svg" width="25%" />
>
> <img src="button/+.svg" width="10%" /><img src="button/7s.svg" width="10%" /> <img src="unlock-UI.svg" width="25%"/> <img src="button/+.svg" width="10%" />

你可以趁这个时间下载 [odin3](Odin3_v3.14.4.tar.xz)/You can download [odin3](Odin3_v3.14.4.tar.xz) during this time.
> 如果出现黄色的感叹号`!`则证明解锁成功
>
> If an yellow exclamation mark `!` appears, the unlock is successful

## 4. 刷入官方系统(先不修补)/Flash into the official system (don't patch it first)
> 再次关机,进入下载模式/Poweroff again and enter download mode.
>
> <img src="https://img-blog.csdnimg.cn/9734be165503463ab7401b529b480f60.png" width="10%" /><img src="https://img-blog.csdnimg.cn/8dacb8e080154d8093d9825fdb8f006e.png" width="15%" /><img src="https://img-blog.csdnimg.cn/0e85b0876c604d16aee6204f1b1b3c5b.png" width="10%" /><img src="https://img-blog.csdnimg.cn/d93abf71affc4b44a73bca2dd21425f3.png" width="15%" /><img src="https://img-blog.csdnimg.cn/7d8c30c358084878872aa95e8d18e5ca.png" width="10%" />
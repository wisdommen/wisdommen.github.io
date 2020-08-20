---
layout: page
title: 自主排错
---
# 自主排错&自助修复

#### 请从上到下依次完成步骤，直到问题解决。如果在完成之前就解决问题，则不需要执行完全部步骤。

---

##### 基础部分，包括UltiLevel，UltiTools，UltiEconomy

1. 本插件未能完美支持paper，若使用paper端可能会出现各种无端bug，请谅解

2. 请检查是否安装了所有的前置插件
    
    UltiTools 前置：PlaceHolderAPI，Vault
    
    UltiLevel 前置：PlaceHolderAPI，Vault
    
    UltiEconomy 前置：无

3. 如果安装了PlaceHolderAPI，请检查是否下载了Player变量。

    若不知道或者没有安装，请在服务器内使用OP权限执行这些命令，并重启服务器。
    
    /PAPI ecloud download Player
    
    /PAPI reload
    
4. 如果你的核心版本是1.16.1的bukkit或者spigot，请检查你的核心是否为最新版本，如果不是请使用官方BuildTools构建最新版本，大部分问题可以在这里解决

5. 请检查你的UltiKits各插件的版本是否为最新版本，旧版本可能会有各种bug，强烈建议开启配置文件中的自动检测更新功能！

6. 如果你使用的是整合包，请确认一下单独使用我的插件开服会不会有问题，很有可能是和其他插件有冲突的原因。

7. 如果还有问题优先进群972992056提问，然后去GitHub提Issue。谢谢！

---

##### 礼包系统配置文件问题

1. 请至少了解一下YAML语法。

    [YAML语法快速上手](https://juejin.im/post/6844903743557746702)
    
    一些常犯的错误：
    
    1. 冒号后面无空格。（错误）
    
        所有的冒号后面都有一个空格（必须加）
       
    2. 缩进错误
    
        缩进必须对齐
        
    3. 正确/错误（布尔值）
    
        正确是true，错误是false（全部小写）
        
    4. 列表问题
    
        空列表是[]，需要加东西的话是 "-" 开头，"-" 后面有一个空格
    
2. 物品的名称请在这里查找，和原版的名称不同！

    [Spigot Material](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/Material.html)
    
3. 物品名称全部都是大写字母！空格用"_"代替！直接在上面网站查找复制粘贴就行。

4. 配置完不显示的请/reload重载插件，实在不行就重启服务器。
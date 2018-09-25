# Erlang资源大全中文版
***

### 目录
- [Erlang资源大全中文版](#awesome-erlang-cn)
    - [包管理](#包管理)
    - [发布管理](#发布管理)
    - [web框架](#web框架)
    - [HTTP](#http)
    - [测试](#测试)
    - [日志](#日志)
    - [监控](#监控)
    - [构建工具](#构建工具)
    - [网络](#网络)
    - [数据库客户端](#数据库客户端)
    - [JSON](#json)
    - [协议](#协议)
    - [消息队列](#消息队列)
    - [开发工具](#开发工具)
    - [调试](#调试)
    - [杂项](#杂项)
    - [在线教程](#在线教程)

### 包管理
*包和依赖库的管理工具*

* [hex.pm](https://hex.pm/) - 一个Erlang生态的管理工具.

### 发布管理
*发布软件的管理工具*

* [relx](https://github.com/erlware/relx) - 一个release发布工具.

### web框架
*web开发框架*

* [ChicagoBoss](https://github.com/ChicagoBoss/ChicagoBoss) - 一个从Rails获取灵感，而写的框架.
* [cowboy](https://github.com/ninenines/cowboy) - 一个小巧，高效的HTTP服务器.
* [MochiWeb](https://github.com/mochi/mochiweb) - 一个用来构建Web应用的轻便,高效的HTTP应用框架的Erlang库.
* [N2O](https://github.com/synrc/n2o) - WebSocket 应用服务器.
* [Nitrogen](https://github.com/nitrogen/nitrogen) - 一个完全用Elang编写的web应用框架(包括前端，后端).
* [Zotonic](https://github.com/zotonic/zotonic) - 高效,实时的web框架并且包括内容管理系统.
* [yaws](https://github.com/klacke/yaws) - 一个高效处理动态页面的web服务器.

### HTTP
*HTTP相关的库*

* [bullet](https://github.com/ninenines/bullet) - 一个cowboy用到的小巧，高效，稳定的类似WebSockets的协议库.
* [gun](https://github.com/ninenines/gun) - 支持 HTTP/1.1, SPDY 和Websocket的HTTP客户端.
* [hackney](https://github.com/benoitc/hackney) - 一个小巧的Erlang HTTP客户端.
* [ibrowse](https://github.com/cmullaparthi/ibrowse) - Erlang HTTP 客户端.
* [lhttpc](https://github.com/esl/lhttpc) - 一个支持 lightweight HTTP/1.1 的客户端.

## 测试 
*测试相关的库.*

* [PropEr](https://github.com/manopapad/proper) - 基于Property based testing的Erlang测试工具.
* [typhoon](https://github.com/zalando/typhoon) - 分布式系统的压力测试可视化工具

## 日志
*日志相关的库.*

* [lager](https://github.com/basho/lager) - 一个Erlang/OTP日志框架.
* [logplex](https://github.com/heroku/logplex) - Heroku log router.

## 监控
*性能监控*

* [entop](https://github.com/mazenharake/entop) - 一个像top命令一样的Erlang节点监控工具.
* [eper](https://github.com/massemanet/eper) - 一个性能相关的工具集.
* [Exometer](https://github.com/Feuerlabs/exometer) -一款监控指标的度量库，整合了folsom.
* [folsom](https://github.com/boundary/folsom) - 一个性能度量系统.

## 构建工具
*项目构建工具.*

* [rebar](https://github.com/rebar/rebar) - Erlang的构建工具,使用它可以方便的编译、测试erlang程序、内联驱动和打包Erlang发行版本.
* [rebar3](https://github.com/rebar/rebar3) - 可以管理来自[Hex.pm](https://hex.pm/)的包. 更多查看 [rebar3.org](https://www.rebar3.org/)
* [erlang.mk](https://github.com/ninenines/erlang.mk) - erlang的makefile.

## 网络
*网络相关的库和工具*

* [ranch](https://github.com/ninenines/ranch) - cowboy用到的TCP网络库.
* [barrel_tcp](https://github.com/benoitc-attic/barrel_tcp) - 低延迟的TCP网络库.
* [gen_rpc](https://github.com/priestjim/gen_rpc) - 一个Erlang-VM的RPC扩展库.


## 数据库客户端
*数据库客户端*

* [mysql-otp](https://github.com/mysql-otp/mysql-otp) - Erlang/OTP的mysql驱动.
* [epgsql](https://github.com/epgsql/epgsql) - PostgreSQL的Erlang驱动.
* [boss_db](https://github.com/ErlyORM/boss_db) - 一个数据库的虚拟层，支持多种数据库.

## JSON
*Json协议相关的库*

* [jiffy](https://github.com/davisp/jiffy) - 利用NIFs解析JSON.
* [jsx](https://github.com/talentdeficit/jsx) - 完全用erlang编写的json解析库.
* [jsonx](https://github.com/iskra/jsonx) - 用c语言实现解析json的erlang库.
* [erljson_bench](https://github.com/davisp/erljson_bench) - 各个json解析库的性能对比.

## 协议
*各种协议库*

* [erlang_protobuffs](https://github.com/basho/erlang_protobuffs) - riak数据库在用的protobuf库,支持rebar.
* [gpb](https://github.com/tomas-abrahamsson/gpb) - 对rebar3支持非常好的protobuf库.
* [msgpack-erlang](https://github.com/msgpack/msgpack-erlang) - MessagePack库.

## 消息队列
*消息队列服务器*

* [rabbitmq](https://github.com/rabbitmq/rabbitmq-server) - 支持多种协议AMQP, STOMP, MQTT, AMQP的消息代理服务器 
* [emqtt](https://github.com/emqtt/emqttd) - 百万级分布式开源物联网MQTT消息服务器 
* [vernemq](https://github.com/erlio/vernemq) - 基于Erlang/OTP的分布式MQTT消息服务器
* [ejabberd](https://github.com/processone/ejabberd) - 著名的XMPP服务器 
* [MongooseIM](https://github.com/esl/MongooseIM) - 高效的分布式XMPP服务器,ejabberd的优化版本

## 开发工具
*开发工具*

* [vimerl](https://github.com/jimenezrick/vimerl) - 编写erlang的vim插件.
* [intellij-erlang](https://github.com/ignatov/intellij-erlang) - intellij插件.
* [distel](https://github.com/massemanet/distel) - emacs,erlang IDE.

## 调试 
*调试工具*

* [recon](https://github.com/ferd/recon) - 可用于生产环境的调试工具集.

## 杂项
*杂项*

* [erlang-history](https://github.com/ferd/erlang-history) - 在Erlang的shell中加入历史记录.
* [kerl](https://github.com/kerl/kerl) - Erlang安装工具，能够轻松切换多个版本.
* [sync](https://github.com/rustyio/sync) - 一个开发时自动重编译的工具.
* [tsung](https://github.com/processone/tsung) - 支持HTTP, XMPP, LDAP,等多种协议的压力测试工具.
* [theBeamBook](https://github.com/happi/theBeamBook) - A description of the Erlang Runtime System ERTS and the virtual Machine BEAM.

## 在线教程
*一些免费的在线资源*

* [erlang.org/docs](http://www.erlang.org/docs) - 官方文档！
* [learnyousomeerlang](http://learnyousomeerlang.com/) - 非常著名的erlang在线书籍,内容非常新.
* [tutorialspoint](https://www.tutorialspoint.com/erlang/index.htm) - [tutorialspint.com](https://www.tutorialspoint.com/)网站上的erlang入门教程.

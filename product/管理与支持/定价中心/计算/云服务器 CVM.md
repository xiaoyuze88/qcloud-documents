## 云服务器 CVM 定价

CVM 提供包年包月和按量计费两种计费模式，分别适用于不同场景下的用户需求。

有关包年包月和按量计费之间的区别详情，请参见 [计费模式说明](/doc/product/439/6796)。

CVM 定价主要包括 CVM 实例价格，磁盘价格，网络价格。
其中 CVM 实例价格包括硬件（CPU、内存），硬盘价格包括磁盘（系统盘、数据盘）。

本文档将介绍 CVM 实例价格，有关磁盘价格和网络价格详情，请参见 [硬盘价格](/doc/product/439/6797),[网络价格](/doc/product/439/6798)。

### 包年包月

本文档说明云服务器包年包月的价格规则，具体价格请点击 [CVM价格计算器](https://buy.qcloud.com/calculator/cvm) 进行测算。

【注意事项】

- 单位为 元/月。
- 2016年11月1日起，云服务器包年包月预付费6个月及以上88折，1年83折，2年7折，3年5折。

### 按量计费

本文档说明云服务器按量计费的价格规则，具体价格请点击 [CVM价格计算器](https://buy.qcloud.com/calculator/cvm?devPayMode=hourly) 进行测算。

2016年7月26日12时开始，CVM按量计费实行3级阶梯价，新购、原有规格CVM实例均参照新价格体系标准。了解云服务器CVM按量计费价格调整策略 请参见 [云服务器按量计费价格调整](http://www.qcloud.com/event/unit-pricing.html) 。同时，**按照最新计费方式，CVM 按量计费实行3阶级梯价，用得越久，优惠就越大**，详情如下：

|阶段|第一阶梯|第二阶梯|第三阶梯|
|---|---|---|---|
|使用时长(小时)  |0< T ≦96|96< T ≦360| T >360|
>注: T 为用户连续使用按量计费云服务器的时长。

|阶段|第一阶梯|第二阶梯|第三阶梯|
|---|---|---|---|
|价格(元／小时)  |P |50% × P | 34% × P|
> 注: P 为按量计费云服务器的第一阶梯的单价。

![](//mc.qcloudimg.com/static/img/2b8e3a898dab0454d77d99a0e1c1eb07/image.jpg)

以1核2GB配置为例，第一阶梯价格为0.42元/小时，第二阶梯价格为0.42×(1-50%)=0.21元/小时，第三阶梯价格为0.42×(1-50%-16%)=0.14元/小时

有关按量计费更多详情，请参见 [计费模式说明](/doc/product/439/6796)。

【注意事项】

- 单位为 元/小时。
- <font color="red">价格计算器所示均为第一阶梯价格，第二阶梯价格 ＝ 第一阶梯价格×50%，第三阶梯价格 ＝ 第一阶梯价格 × 34%</font>。
- 阶梯规则只适用在同一个配置下，如果配置发生变更，费用将从新配置的第一阶梯开始重新计费。以云服务器为例，原始配置为2核4GB，使用到第100小时，已经进入阶梯定价的第II阶梯，调整配置为1核2GB后，计费从1核2GB的第I阶梯计算。

## 购买限制

### 包年包月

针对每个用户，腾讯云包年包月 CVM 实例每个地域分配了固定的配额。

- 每个用户在每个可用区，每月均可新购买（非净增）的包年包月的 CVM 实例配额如下。即每个用户每个月都可在以下可用区新增购买以下数量的 CVM 实例。

| 广州二区 |广州三区| 上海一区 |北京一区| 香港一区| 新加坡一区|北美一区 |
|:---------:|:---------:|:---------:|:---------:|:---------:|:---------:|:---------:|
| 150 | 150|150 | 150 |100 |100 |100 |

- 包年包月 CVM 实例配额数量仅包含<font color="red">新购买</font>机器数量，存量以及到期机器数量不在计算范围内。计算规则如下：

| 新购机器数量 |存量机器数量| 到期机器数量 |
|:---------:|:---------:|:---------:|
|ｖ| × | × |

- 每个配额的计算周期均为自然月。例如：2016年2月的计算周期为：2月1日00:00:00-2月29日 23:59:59

- 若您需要开通更多预付费的主机，可通过[配额申请链接](http://manage.qcloud.com/dbexp/apply.php?product=cvmmonthlyquota)提出申请，我们将在对您的实际需求进行评估后为您提升配额。提升配额有效期为当自然月，在次月1日，配额将恢复原始值。 

- 如出现疑似异常/恶意提升配额，腾讯云有权否决退货申请，腾讯云在法律范围保持最终解释权。

### 按量计费 

- 购买按量计费云服务器前，请前往<a href="https://console.qcloud.com/developer">用户中心</a>进行资质认证。未进行资质认证的用户将不能购买按量计费的云服务器。</font>

购买按量计费 CVM 实例时，以下特性均<font color="red">不支持</font>：
代理商代付
代金券消费
五天无理由退款
切换为包年包月模式
采用共享核的云主机
带宽包用户，后付费月结用户

- 每个用户在每个可用区<font color="red">总共</font>可购买的按量计费云服务器数量有一定配额： 


| 广州二区 |广州三区| 上海一区 |北京一区| 香港一区| 新加坡一区|北美一区 |
|:---------:|:---------:|:---------:|:---------:|:---------:|:---------:|:---------:|
| 30 | 30 | 30 | 30 |20 |30 |20 |

## 购买指导

### 包年包月

1.登录[腾讯云服务购买页](http://manage.qcloud.com/shoppingcart/shop.php?tab=cvm)

2.选购页计费模式可以选择【包年包月】。

3.选择[地域](/doc/product/213/3921))、可用区、主机类型，根据需要选定硬件、带宽或流量，即可确认订单。

- 网络较平稳的用户（如下图一）推荐选择按带宽计费。若选择按固定带宽，则不限流量，计费方式为【硬件+带宽】（包年包月）

- 网络波动大的用户（如下图二）推荐选择按使用流量计费。若选择按使用流量，则可自由选择带宽峰值，计费方式为【硬件（包年包月）+ 流量（按实际使用流量）】。

4.您可以通过余额支付、财付通支付、微信支付、QQ钱包支付等方式对订单进行支付。
  
5.订单支付后立即开通服务器，10分钟左右即可看到IP地址，进行登录管理。

图一
![](//mccdn.qcloud.com/img567f92c595947.png)
图二
![](//mccdn.qcloud.com/img567f92c272b26.png)
 
### 按量计费
 
1.登录[腾讯云服务购买页](http://manage.qcloud.com/shoppingcart/shop.php?tab=cvm)
 
2.选购页计费模式可以选择【按量付费】。

3.选择[地域](/doc/product/213/3921)、主机类型，根据需要选定硬件、带宽或流量，即可确认订单。

- 网络较平稳的用户推荐选择按带宽计费。若选择按固定带宽，则不限流量，计费方式为【硬件+带宽】（费用固定，按小时计算）。

- 网络波动大的用户推荐选择按使用流量计费。若选择按使用流量，则可自由选择带宽峰值，计费方式为【硬件（固定费用按小时计算）+ 流量（按实际使用流量）】。

4.您可以通过余额支付、财付通支付、微信支付、QQ钱包支付等方式对订单进行支付。

5.订单支付后立即开通服务器，10分钟左右即可看到IP地址，进行登录管理。（开通按量云服务器后，请确保您的账户余额充足）

### API购买

购买云服务器见参见[创建实例（包年包月）](https://www.qcloud.com/doc/api/229/%E5%88%9B%E5%BB%BA%E5%AE%9E%E4%BE%8B%EF%BC%88%E5%8C%85%E5%B9%B4%E5%8C%85%E6%9C%88%EF%BC%89)和[创建实例（按量计费）](https://www.qcloud.com/doc/api/229/%E5%88%9B%E5%BB%BA%E5%AE%9E%E4%BE%8B%EF%BC%88%E6%8C%89%E9%87%8F%E8%AE%A1%E8%B4%B9%EF%BC%89)

### 购买方式切换

#### 切换说明

以下说明仅针对腾讯云服务器的购买方式。

- 点击“立即切换”后，将进入切换过程，将在3小时内暂时锁定不能购买和退还后付费的云服务器；需要尽快支付完成切换后即解除锁定。
- 切换过程及切换后，均不影响您的业务运行。切换后，只支持包年包月的预付费购买，不能再切换回当前后付费月结的购买方式。
- 切换支付方式后，系统会将尚未支付的后付费订单置为无效，将不可再继续支付。
- 本月已冻结的云服务器费用，会在下月月结时解除冻结，并扣除切换当月内后付费的云服务器使用费用。

#### “后付费”购买方式与“预付费”购买方式的对比

||切换前（后付费）|	切换后（预付费）|
|--|--|--|
|模式对比|	当前的后付费月结。|	包年包月的预付费模式。|
|购买|	冻结一个月费用，不真正扣费；复杂难理解。|	按照选择的购买时长直接扣除费用。|
|月结|	每月5日对上月的云服务器使用进行月结，上月冻结费用解冻，根据实际使用天数扣除费用，冻结本月费用。|	无月结过程。|
|云费用预算|	根据实际使用天数收费，做预算不准确、操作较困难。|	先支付再使用，预算简单清晰。|
|续费|	无续费，不使用了需要退还。|	云服务器有到期时间，需要在到期时间前续费，购买继续使用的时长。|

## CVM 实例配置

有关详情，请参见[CVM 实例配置](/doc/product/439/6800)。

## CVM 硬件配置调整

>注：
当数据盘、系统盘为本地盘时，硬件配置（CPU，内存）不可升降。
当数据盘、系统盘为云硬盘时，提供硬件配置（CPU，内存）调整功能。

下文提及的配置升级与配置降级均为系统盘与数据盘是云硬盘的情况下。

### 配置升级

当用户的业务扩大，需要提升云服务器的硬件配置时，可以在控制台通过配置调整实现。对于所有云服务器类型，配置升级的生效时间均为即时生效；即当用户升级配置并支付可能产生的费用后，云服务器将立即按新的配置运行。升级次数无限制。

具体升级方式请参考[调整 CVM 实例配置](/doc/product/439/6804)

### 配置降级

当用户的业务缩减，需要降低云服务器的硬件配置时，可以在控制台通过配置调整实现。对于不同类型的云服务器，具体的降级方式不同

#### 包年包月

购买了包年包月的云服务器实例后，用户随时可以降配。但每个帐号(UIN)累计只能提3单降配单，累计降配机器不能超过3个云服务器实例。降配时，降配的金额将计算成降配后配置的等效的时长，延长此云服务器的到期时间。

截止配置降级的时刻，用户实际支付费用的剩余价值与目标配置剩余价值的差值若大于零，则将该差值折算为目标配置所支持的时长来延长该服务器的到期时间；若该差值小于或等于零，将不会调整用户云服务器到期时间（通常为用户支付时使用折扣或代金券情况）。

- 退款项说明：符合配置降级规则的申请，将按照用户购买时的消费实际花费的非抵扣券部分（包括现金、分成、赠送金额、返货等，抵扣券部分不返还）的剩余价值折算为新配置的等效使用时长。 
- 每个帐号最多只能无条件退还3单，每个用户累计限三台服务器，超出限制部分的订单不能再做配置降级。 
- 在次数限制内，用户降配后仍然可以升配降配。 
- 如出现疑似异常/恶意配置降级，腾讯云有权否决配置降级流程，腾讯云在法律范围保持最终解释权。 

具体降级方式请参考[调整 CVM 实例配置](/doc/product/439/6804)

#### 按量计费

购买了按量计费的云服务器实例后，用户随时可以降配。降级次数无限制。

具体降级方式请参考[调整 CVM 实例配置](/doc/product/439/6804)

## 到期提醒

### 包年包月 CVM

- 到期预警
包年包月的资源会在到期前7天开始，隔天向您推送到期预警，预警消息将通过邮件及短信的方式通知到腾讯云账户的创建者以及所有协作者。

- 欠费预警
包年包月的资源到期当天及每隔天向您推送欠费隔离预警，预警消息将通过邮件及短信的方式通知到腾讯云账户的创建者以及所有协作者。

### 按量计费 CVM 
 
 ![](//mccdn.qcloud.com/img567f91951599d.png)
 
- 余额预警
系统每天会根据您名下按量付费资源过去24小时的消费情况以及账户余额情况，预估余额可支撑的时间。若可支撑时间小于5天，我们将会向您推送余额预警。预警消息将通过邮件及短信的方式通知到腾讯云账户的创建者以及所有协作者。

- 欠费预警
按量计费资源每个整点进行扣费。在您的账户被扣为负值时（上图中点1），我们将通过邮件及短信的方式通知到腾讯云账户的创建者以及所有协作者。

- 欠费处理
从余额扣为负值时刻起，**2**小时内云主机可继续使用且继续扣费。

2小时后（上图中点2）服务器将自动关机且停止扣费。

自动关机后24小时内，若您的账户余额未充值到大于0，不可对其开机；若充值到余额大于0，计费将继续，可对其开机。

自动关机后，余额小于0达到24小时（上图中点3），按量计费主机将回收，所有数据将会被清理，且不可找回。

【注意事项】
- 按量计费资源不再使用时**请及时销毁**，以免继续扣费。
- 您的实际资源消耗可能不断变化，因此余额预警可能存在一定的误差。

### 按流量计费网络
 
- 余额预警
流量消耗波动大，预测困难，不提供余额预警。

- 欠费预警
按流量计费网络每个整点进行扣费。在您的账户被扣为负值时，我们将通过邮件及短信的方式通知到腾讯云账户的创建者以及所有协作者。

- 欠费处理
从余额扣为负值时刻起，**2**小时内可继续使用按流量计费网络且继续扣费。
当账户冲正后，流量服务会恢复，请检查网络设置，并恢复受影响主机与负载均衡的绑定关系。

## 回收机制

### 包年包月
- 云服务资源到期前七天，系统会给您发送续费提醒通知。 
- **2016年6月23日起，CVM包年包月回收停服时间将由 到期后7天 调整为 到期当天。**[点击了解变更详情](http://bbs.qcloud.com/thread-19118-1-1.html)
- 余额充足的情况下，您已设置自动续费的设备在到期当日会照常执行自动续费。
- 若您的云服务器在到期前（包括到期当天）未进行续费，系统将在到期时间点开始对其作停服处理（设备断网关机，仅保留数据）。
- 到期次日至到期后7天，您仍可以在回收站对设备进行续费找回。
- 若您的云服务器在到期7天后（包括第7天）未进行续费，系统将在到期后第8天的0点开始对资源释放，**数据将被清除且不可恢复**。
- 云服务器进入回收站后将被强制解除与负载均衡的挂载关系。 

### 按量计费
- 主机回收时，我们将通过邮件及短信的方式通知到腾讯云账户的创建者以及所有协作者。
- 主机销毁/回收后，数据将会被清除且不可找回。
- 云服务器被隔离后（欠费两小时以上）会强制解除与负载均衡的挂载关系。

		

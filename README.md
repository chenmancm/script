## 说明
目前教程都是针对iOS端的，不需要越狱，安卓百度叮咚助手。

大润发和山姆目前只有监控没有重写（我这边这2个平台都没法配送，无法详细测试）

## 如何使用
可能有风险，使用需谨慎

- [详细教程](https://github.com/wu491925129/script/blob/main/%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B.md)
- [重写教程](https://github.com/wu491925129/script/blob/main/%E9%87%8D%E5%86%99%E6%95%99%E7%A8%8B.md)
- [大润发运力监控](https://github.com/wu491925129/script/blob/main/%E5%A4%A7%E6%B6%A6%E5%8F%91%E8%BF%90%E5%8A%9B%E7%9B%91%E6%8E%A7.md)
- [山姆超市运力监控](https://github.com/wu491925129/script/blob/main/%E5%B1%B1%E5%A7%86%E8%B6%85%E5%B8%82%E8%BF%90%E5%8A%9B%E7%9B%91%E6%8E%A7.md)

## 更新记录

**0413** 新增大润发运力监控，见 --> [大润发运力监控.md](https://github.com/wu491925129/script/blob/main/%E5%A4%A7%E6%B6%A6%E5%8F%91%E8%BF%90%E5%8A%9B%E7%9B%91%E6%8E%A7.md)

**0413** 新增山姆会员超市运力监控，见 --> [山姆超市运力监控.md](https://github.com/wu491925129/script/blob/main/%E5%B1%B1%E5%A7%86%E8%B6%85%E5%B8%82%E8%BF%90%E5%8A%9B%E7%9B%91%E6%8E%A7.md)

---
**0412** 详细详细教程新增视频播放

---

**0410** 新增购物车商品监控，监控操作逻辑与运力监控一致，监控代码见详细教程.md文档，设置推送阀值，当购物车中失效商品被站点上架数量超过推送阀值时，推送消息。

---

**0410** 优化监控通知，展示所有有运力配送的时间段，开重写后建议选择通知的第二个时间段；
优化自动获取配送时间，优化送达时间弹框，禁止弹出；

**更新指南**：

监控：更新详细教程.md中的代码

重写：更新全部脚本

---

**0409** 监控代码新增推送可配送时间

---

**0409** 更新订单下单重写规则，日期失效状况不会弹框，可以直接点击结算，下单更快。

---
**0408** 更新订单校验重写规则，详情看重写教程.md文档，重写开启之后结算页面不会弹出繁忙的弹框，配合获取时间重写规则可以一直点击结算，下单更快。

## bug fix
**0411** 修复购物车监控日志输出异常的问题

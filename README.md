# PayPal 收款账单 · 业务线账号与客户承担手续费

资金中台「业务入账 → Paypal账单管理」创建账单原型。

## GitHub Pages

https://maxmabiz.github.io/fund-paypal-bill/

## 本地预览

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

打开 http://127.0.0.1:8765/index.html

## 本期能力

- 创建第一步：选中业务线后弱提示开具账号
- 创建第三步：客户承担手续费（默认关闭；开启后按银联汇率测算预计收款金额）

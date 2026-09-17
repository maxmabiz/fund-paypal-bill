# PayPal 收款账单 · 业务线账号与商户承担手续费

资金中台「业务入账 → Paypal账单管理」创建账单原型。

## GitHub Pages

https://maxmabiz.github.io/fund-paypal-bill/

## 本地预览

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

打开 http://127.0.0.1:8765/index.html

## 本期能力

- 创建第一步：选择业务线后进入填写商户 ID
- 创建第三步：商户承担手续费（默认关闭；开启后按银联汇率测算预计收款金额）
- 列表：备注后展示「商户承担手续费」「手续费金额」，并可按是否承担手续费筛选

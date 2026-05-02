# PinoyVitality — Telegram Supplement Bot

## 启动

```bash
cd ~/Projects/ph-supplement-bot
pip install python-telegram-bot python-dotenv
python bot.py
```

## 配置

编辑 `.env` 文件：
- `BOT_TOKEN` — 你的 Telegram Bot Token
- `USDT_WALLET` — 你的 TRC20 USDT 收款地址
- `GCASH_NUMBER` — 你的 GCash 收款号码
- `ADMIN_ID` — 你的 Telegram 数字 ID（用于接收订单通知）

获取你的 Telegram ID：给 @userinfobot 发消息即可获取。

## 客户命令

- `/start` — 欢迎页
- `/products` — 查看产品
- `/order` — 下单
- `/track` — 查询订单
- `/support` — 联系客服

## 管理员命令

- `/dashboard` — 查看所有订单
- `/confirm ORD-0001` — 确认付款
- `/ship ORD-0001 TRACKING123` — 标记发货

## 数据

订单和客户数据存储在 `data/` 目录下的 JSON 文件中。

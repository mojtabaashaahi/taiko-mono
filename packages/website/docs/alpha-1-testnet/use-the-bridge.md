---
sidebar_position: 3
---

# 🌉 Use the bridge استفاده از پُل

The bridge contract can be found: قرارداد پل را می توان یافت

- Deployed on L1: https://l1explorer.a1.taiko.xyz/address/0x3612E284D763f42f5E4CB72B1602b23DAEC3cA60
- Deployed on L2: https://l2explorer.a1.taiko.xyz/address/0x0000777700000000000000000000000000000002

## Test the bridge بررسی پل

Use the [bridge](https://bridge.a1.taiko.xyz/) for the following actions: از پل برای کارهای زیر استفاده کنید

- Bridge ETH between Ethereum A1 and Taiko A1   پل بین اتر اتریوم آ1 و تایکو آ1
- Bridge HORSE between Ethereum A1 and Taiko A1   پل اسب بین اتریوم آ1 و تایکو آ1

## Why is my L2 -> L1 transfer taking so long? چرا انتقال من بین لایه2 به لایه1 زیاد طول میکشد؟

The transfer from L2 to L1 can take a while because Taiko has a several hours delay in syncing block headers to allow uncle proof generation time, and we need the synced header to match so the Merkle proof of the message being sent on L2 is valid on L1.

انتقال از لایه2 به لایه1 میتواند کمی طول بکشد زیرا تایکو در همگام سازی  هدرهای بلوک برای زمان تولید دسترسی اثبات آنکل، چند ساعت تاخیر دارد، و ما به هدرهای همگام سازی مطابق نیاز داریم بنابر این اثبات مرکل برای شروع ارسال پیام در لایه2 بر روی لایه1 معتبر است.    

## Bridge contract explained توضیحات قرارداد پل

Read the bridge documentation on our GitHub: https://github.com/taikoxyz/taiko-mono/tree/main/packages/protocol/contracts/bridge.

مستندات پل را در گیت هاب ما بخوانید: https://github.com/taikoxyz/taiko-mono/tree/main/packages/protocol/contracts/bridge.  

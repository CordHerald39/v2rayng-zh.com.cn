---
title: "Signal 安卓换机卡在二维码或连接中：保留旧聊天再核对直接转移流程"
description: "Signal 安卓换机卡在二维码或连接中：保留旧聊天再核对直接转移流程。按适用条件、操作步骤和失败分支处理，保留官方参考入口。"
date: "2026-10-05"
category: "tutorials"
updated: "2026-10-05"
author: "v2rayNG 配置手册 内容编辑"
draft: false
label: "海外社交"
---

安卓换到另一部安卓、旧机还在，却停在二维码或扫码后的连接过程时，先按当前直接转移核对条件：不要把历史当成可在两台各留一份，也不要一上来就卸掉新机应用。适用前提是旧机仍在身边、能打开 Signal 并看到聊天，且相机可用。处理方向：两机更新到 7.68.4 或更高，打开 Wi‑Fi 与蓝牙、允许存储访问，新机可收短信或来电完成注册；新机初始界面选 Restore or transfer 出示二维码，由旧机点相机图标扫描。转移是移动不是复制，完成后旧机失去主注册，过程本身不生成备份。不要混用旧教程里「搜索设备」一类截图。流程见 [Android to Android Device Transfer](https://support.signal.org/hc/en-us/articles/10066808631066-Android-to-Android-Device-Transfer)，卡住时对照 [Troubleshooting Device Transfers](https://support.signal.org/hc/en-us/articles/10075160307482-Troubleshooting-Device-Transfers)。

## 适用条件：安卓对安卓，且必须旧机还在

直接转移只在 Android 到 Android 之间，且两机都要在身边并解锁。旧机丢失、损坏、已恢复出厂或相机不能用，这条路不可用。安卓与 iPhone 互转不属于本流程，官方写明只能改用 Signal Secure Backups，此处不写跨系统步骤。

两边打开 Wi‑Fi 和蓝牙，允许访问存储，过程中保持靠近。旧机必须能查看消息历史。新机要能接收短信或来电以完成注册。转移专页要求两边 7.68.4 或更高；故障排查还要求尽量更新到当前版本，过旧可能无法开始或中途失败。

直接转移不借助 Signal Secure Backups 搬历史。完成后历史从旧机移除，也不会顺带生成备份。若希望事后仍有备份，可在转移前或转移后启用 Signal Secure Backups。开始转移时旧机也可选择是否先做一次，这是可选项。

## 新机出码、旧机扫描，不要套旧界面

当前步骤是新机出二维码、旧机扫描。

新机安装并打开 Signal，选 Restore or transfer，再选 I have my old phone 即可看到码。旧机打开 Signal，点相机图标扫描。旧机再点 Transfer account，按提示选择是否先做 Secure Backup，然后选 From your old phone。把新机靠近旧机，两边点 continue。核对两边验证数字一致后，点 Yes, the numbers match 并继续。

完成后旧机出现黄色横幅，提示该设备不再注册：同一时间只能有一台主注册设备。之后可卸载旧机 Signal，专页举例为系统设置 > 应用 > Signal > 卸载，菜单因机型而异。

两台安卓不能把聊天合并后再同时保留主注册；历史被移走，旧机变为未注册。

## 扫码失败、连不上，以及新机里已经有聊天

扫不上码：确认旧机相机正常、两机靠近且未锁屏或切走应用。码在新机 Restore or transfer 界面，相机在旧机，不要对调。

停在连接或传输中：保持亮屏解锁、距离近；用较稳定的 Wi‑Fi 或设备间本地连接，避开弱网和 VPN；避免低电或省电模式。若中断且未完成，聊天可能无法恢复，官方写明失败后没有额外恢复途径。动手前可先启用 Signal Secure Backups 作为退路。

若新机已经完成初始设置、里面已有聊天：先认清边界再决定。直接转移只在新机初始设置出现；要重新进入，故障排查给出的办法是卸载新机 Signal 再重装。卸载会丢掉新机本地已有对话，且不能与旧机历史合并。若那些对话也要留，先确认能否接受损失，不要把删数据当成第一步。

旧机不在、已重置或相机损坏时，不要反复扫码。本文只覆盖旧机仍在的安卓对安卓。不保证商店版本、机型菜单或网络一定能完成，以两机上实际出现的 Restore or transfer 为准。

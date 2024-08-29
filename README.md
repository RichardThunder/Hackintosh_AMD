<!--
 * @Author: richardthunder yuetingpei888@gmail.com
 * @Date: 2024-06-13 16:29:53
 * @LastEditors: richardthunder yuetingpei888@gmail.com
 * @LastEditTime: 2024-07-19 15:07:47
 * @FilePath: /Hackintosh_AMD/README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# 黑苹果 AMD
## 硬件配置
- Ryzen r5 5600
- 华擎x370 gaming k4
- 显卡 RX6700XT
- 有线网卡 intel I211 ~~(无法连接)~~
- 无线网卡 intel 8265AC
- 硬盘 WD SN720 1TB SSD

## 系统版本
macos 14.5 Sonoma

## 存在问题
- 有线网卡 i211 不工作 使用外接usb网卡替代)
- handoff 不能使用(只能接收剪贴板内容)
- airdrop 只能接收文件不能发送




# Hackintosh_AMD
Hackintosh_AMD
## hardware
- Ryzen r5 5600 
- Asrock  X370 Gaming K4
- Radeon RX6700xt (AMD)
- Intel I211 Onboard network interface card
- Intel 8265AC wireless
- WD SN720 1TB SSD
## System
  macos 14.5 Sonoma

## Problem existing
- I211 not work(use external network interface card)
- handoff not work
- airdrop not work

## UPDATE
添加了 对I211板载网卡的支持 来源 https://github.com/donatengit/AppleIGB/issues/19#issuecomment-2227514964
下载链接  https://github.com/user-attachments/files/16229077/AppleIGB-RELEASE.kext.zip

降级到macos 13 ventura

# HP-Pro-SFF-400-G9-Desktop

# The overall configuration list of my black Apple host is as follows:

| Part Type     | Part Model 
|---------------|----------------------------------------------|
| Opencore      |  1.0.5                                       |
| Version       |  macOS Sequoia15.XX                          |
| Motherboard   |  HP-Pro-SFF-400-G9-Desktop                   |
| Hard disk     |  Coiorful CN600 1T M2                        |
| Graphics      |  Radeon RX550/550 Series 4G                  |
| CPU           |  Intel i3 12100F                             |
| Memory        |  ADATA 2667 16G*2 DDR4                       |
| Wireless      |  Intel(R) Ethernet Connection (17) I219-LM   |
| Realtek Audio |  Realtek ALC256/ALC3246                      |
|               |                                              |

Support the full range of CPU models, i5-12400 , i7-12700 , i3 12100F ,  i3-12300 , etc

HP-Pro-SFF-400-G9 Series Motherboards MacOS 15.XX Completeness:

CPU Normal Turbo Frequency (i5/i7/i3/etc.)

Onboard audio is normal

The graphics card supports HDMI/DP display output

The front and rear 3.5 audio outputs are normal

Sleep wake-up is normal

The wired NIC Intel® I219-LM is in normal use

The boot can support independent graphics (RX550/RX460 and other series) by default.

I won't talk about them one by one

# OpenCore Configuration

# ACPI

| ACPIs                    |
|--------------------------|
|  SSDT-AWAC               |
|  SSDT-PLUG               |
|  SSDT-EC                 | 
|                          |

# Drivers

| Driver Name     |
|-----------------|
| HfsPlus         |
| OpenCanopy      |
| OpenRuntime     |
| ResetNvramEntry |
| ToggleSipEntry  |

# Bootstrap

| Bootstrap Name     |
|--------------------|
| Bootstrap          |
|                    |

# Kexts

| Kext Name                             |
|---------------------------------------|
| AppleALC.kext                         |
| CPUFriend.kext                        |
| CPUFriendDataProvider.kext            |
| CpuTopologyRebuild.kext               |
| CpuTscSync.kext                       |
| FeatureUnlock.kext                    |
| HibernationFixup.kext                 |
| XHCI-unsupported.kext                 |
| IntelMausi.kext                       |
| NVMeFix.kext                          |
| Lilu.kext                             | 
| SMCProcessor.kext                     | 
| SMCSuperIO.kext                       | 
| WhateverGreen.kext                    | 
| VirtualSMC.kext                       | 
| RestrictEvents.kext                   | 
| RadeonBoost.kext                      | 
| RadeonSensor.kext                     |
| RTCMemoryFixup.kext                   | 
| USBInjectAll.kext                     | 
| I won't talk about them one by one    |

# BIOS Setup Reference:

Secure Boot 关闭

CSM         关闭

Resizable BAR  关闭

Above 4G Decoding 开启

AHCI  开启

## 关于打赏

如果您认可我的工作，请通过打赏支持我后续的更新(自觉打赏的人真少啊，免费的东西长久不了,现已改为需要密码解压，需微信或支付宝打赏入群。打赏记得留言备注你的qq号，然后申请入群时，填写你的留言为验证答案就是，我确认后会通过你的验证的。PS:之所以设置打赏，并不是为了赚大钱，当然大家打赏的多是有一些零花钱。主要是维护更新不易，每次系统一更新，有问题的话，就要工作时间之外花时间去调试，解决问题。普通群最多500人，无门槛的入群，不够用，有些机友对无门槛进入还不珍惜，进退群很随意，不看相关说明，上来就问问题的又多。不多说了，理解不理解的，就这样吧。

|  微信                                                                                 |
|---------------------------------------------------------------------------------------|
| ![1](https://github.com/user-attachments/assets/06d87fea-0d11-4bf4-b9ed-034dc7f53d06) |
|                                                                                       |
| ![1](https://github.com/user-attachments/assets/b99e75b4-69d3-450a-aae4-1a610760372d) |                                              |                                                                                       |


若有其他问题请加Q群： 738882434



# Laptop Upgrades

Want to upgrade your laptop but not sure what to get or what’s compatible? Just follow this guide, and you should find exactly what you're looking for.

This guide covers upgrading **RAM**, **storage**, and the **Wi-Fi card**.

## 1. RAM Upgrade

Adding more RAM is one of the quickest ways to make your computer feel faster. It helps with multitasking, keeps things running smoothly, and prevents apps from slowing down when you’ve got a lot open.

To know what kind of RAM you need, follow these steps:

<details>

<summary><strong>Method 1: Crucial Memory Selector</strong></summary>

Go to [Crucial’s Upgrade Tool](https://www.crucial.com/upgrades), enter your system details, and it will recommend compatible RAM. It also lists the maximum supported memory for your system. Systems with soldered RAM won’t show ram upgrade recommendations since the memory can’t be replaced normally.

{% hint style="warning" %}
**Make sure the listed details match your system specs, or you might end up with the wrong generation of memory.**
{% endhint %}

</details>

<details>

<summary><strong>Method 2: Check Installed RAM Manually</strong></summary>

Open **Task Manager** → **Performance Tab** → **Memory**. Below the memory graph, you’ll see something like: `Speed: XXXX MT/s`. (In this guide, MT/s and MHz are used interchangeably.)

Compare the speed with the table below:

| Speed    | Generation | Supported RAM      |
| -------- | ---------- | ------------------ |
| 3200MT/s | DDR4       | DDR4 3200MHz CL22  |
| 4800MT/s | DDR5       | DDR5-4800 MHz CL40 |
| 5200MT/s | DDR5       | DDR5 5600MHz CL46  |
| 5600MT/s | DDR5       | DDR5-5600MHz CL46  |

</details>

<details>

<summary>FAQS</summary>

**1. Do I need the exact same RAM stick if I already have one installed?**

➜ No. As long as the **CL** and **frequency** match, you can mix brands.

**2. The RAM installed is 5600 MHz, but it’s running at 4800 MHz?**

➜Either you have mismatched RAM sticks, or your CPU doesn’t support the higher speed.

**3. What’s the maximum memory my laptop supports?**

➜It depends on the CPU. Check your CPU’s spec sheet for details. Staying within **64GB** is recommended for compatibility.

**4. Can I use RAM sticks with different capacities?**

➜Yes, but it’s not recommended. They’ll run in **flex mode**, which is slower than dual channel.

**5. Can I use DDR5 RAM in a DDR4 system or vice versa?** ➜No. RAM from different generations isn’t interchangeable and won’t fit in your laptop.

**6. Can I replace both existing RAM sticks with lower cl ones?** ➜Yes.

</details>

## 2. Storage Upgrade

Most models after 2021 support **Gen4 NVMe SSDs**. Older models can use them too, but speeds will be limited to Gen3.

**The M.2 2280 slot does not support SATA SSDs.** SATA drives only work on laptops made before 2021.

### Best Gen4 SSDs (sorted by speed)

These drives are reliable for any workload:

1. Samsung 990 Pro
2. WD SN850X
3. Crucial T500 Pro
4. Acer Predator GM7000
5. Lexar NM790
6. SK Hynix Platinum P41
7. Sabrent Rocket 4 Plus
8. Kingston KC3000

### Budget Gen4 SSDs (sorted by speed)

Drives marked **DRAM-less** are fine for storage and games but not ideal as boot drives:

1. Crucial P5 Plus
2. WD SN770 (DRAM-less)
3. Silicon Power UD90 (DRAM-less)
4. Crucial P3 Plus (DRAM-less)
5. WD SN580 (DRAM-less)
6. Samsung 980 (DRAM-less)
7. Kingston NV2 (DRAM-less)

## 3. Wi-Fi Card Upgrade

If your laptop has a MediaTek or Realtek card and you’re facing issues, replace it with an Intel AX210 or AX200. If you already have an Intel card, there’s usually no need to upgrade unless you want faster speeds and want to upgrade to Wi-Fi 6 or Wi-Fi 7.

| Wi-Fi Card          | Intel Systems (11th Gen +) | AMD & Older Intel (10th Gen or older) |
| ------------------- | -------------------------- | ------------------------------------- |
| Ax200               | ✅                          | ✅                                     |
| Ax201               | ✅                          | ❌                                     |
| Ax210               | ✅                          | ✅                                     |
| Ax211               | ✅                          | ❌                                     |
| Ax411               | ✅                          | ❌                                     |
| Intel Killer AX1690 | ✅                          | ❌                                     |

## Windows 11 IoT Enterprise to Windows 11 IoT Enterprise LTSC transformation

Windows 11 IoT Enterprise LTSC is set to be released in Q2 2024. IoT Enterprise LTSC versions of Windows are known for having less bloat and better performance on lower-end machines.

Currently, only Windows 11 IoT Enterprise is available, which is identical to Windows 11 except for a few exclusive enterprise features. Like any non-LTSC version, it still has the Microsoft Store and other standard apps. I chose Windows 11 IoT Enterprise just for fun, but the same can be done with the original Windows 11.

It is possible to debloat Windows to its “bare bones,” but this comes at the cost of losing system stability and essential features such as Windows Defender and Windows Updates.

My approach is to get all the benefits of the system while still getting as close as possible to the stability of Windows 11 IoT Enterprise. This statement may not be entirely accurate because the system is not LTSC, but you get the point.


You can follow these simple steps to enjoy a better Windows experience:

1. Clone the repository or download and extract it.

2. Open "win11-iot-debloat.txt" and copy all contents with Ctrl + A.

![Second Step](https://i.imgur.com/xd2TSv4.png)

3. Open Terminal/Powershell with Administrator rights and press right click in the terminal and press "Paste Anyway" if asked.

![Third Step](https://i.imgur.com/ZvNJiKo.png)

4. Press Enter and Enjoy the debloated experience, in case of any errors, you can ignore them, they indicate that certain component is in use and others are depending on it and there is nothing wrong with this error.

5. Done! 🥳🎉

## Where to get Windows 11 IoT Enterprise?
Unfortunately it's not legal to provide any download links, but I can certainly provide you hashes and ISO name.

```
Name:
en-us_windows_11_iot_enterprise_version_22h2_updated_sep_2022_x64_dvd_efad8b7e.iso
SHA1/SHA256:
a27e017232b4f7aaaa8ab5b10ff0b852db1e9557216e896bc32fc390c316e138
```

## References
Official Windows LTSC Retailer that proves my point by showing the system.
https://youtu.be/6CTOA-AjuI8
Windows 10 IoT Enterprise LTSC with "Get-AppxPackage –AllUsers | Select Name, PackageFullName" in powershell.
My experience and knowledge.


Good luck!
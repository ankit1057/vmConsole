![](./images/banner.png)

# vmConsole
[https://youtu.be/6bslZ7EzA3I](url) **Tutorial Here**
A free and open-source application that enables you to run [Alpine Linux]
distribution in a virtual machine on your Android device. Thousands of packages
available for installation from online repositories make vmConsole a powerful
tool for software developers, testers, system administrators and just Linux
fans.

This application is built on top of [QEMU] x86_64 system emulator and should
be compatible with majority of devices running Android 7.0 and higher. Your
device is not required to be rooted or have custom firmware installed. KVM
acceleration is not supported meaning that performance will be low.

vmConsole is exactly console, aka "terminal" application. Input and output are
being performed through Xterm-compatible terminal screen. Don't beg for Xorg
or Wayland support.

<p align="center">
  <a href="https://github.com/sylirre/vmConsole/releases/latest">
    <img src="images/get-it-on-github.png" width="256px">
  </a>
</p>

**Proper Linux administration skills are needed in order to use vmConsole!**

Typical use-cases of vmConsole application:

- Exploring the world of Linux =)
- Programming
- Testing software
- Hacking
- Running TOR hidden services
- Crawling / archiving web sites

The most important information about application usage is embedded as MOTD
shown during vmConsole login. Other information is easily discoverable if
you have some mid-level Linux skills. Also there is a [Wiki] which describes
some basics.

It is highly recommended to visit [Alpine Linux Wiki].

<p align="center">
  <img src="images/demo_btop.png" width="256px">
  <img src="images/demo_docker.png" width="256px">
  <img src="images/demo_metasploit.png" width="256px">
</p>

## About project

vmConsole is a combination of a terminal emulator based on [Termux], [QEMU]
system emulator (x86_64) and tiny, but production-grade Linux distribution.
It has begun as experiment and some released variants were known as Alpine
Term or vShell. So far the vmConsole works much better than analogs like
[Limbo PC] or [UserLAnd].

This is a personal public project which means it is free and open-source,
but I don't accept feature requests and so on. Android application development
is not my expertise area and I'm not interested in spending extra time on
figuring out how to implement features that I will not use. I use vmConsole as
replacement for PC (laptop) when I don't have access to the latter and it
works really well, not considering performance issues. Don't ask me why I
have chosen x86_64 instead of aarch64 emulated system architecture.

I may rewrite Git history from time to time because it stores few binary files
which take noticeable disk space. Coding quality is very far from perfect.
I know that but don't care, the app works and this is good.

The vmConsole app is distributed under GPL v3.0 license.

I don't care whether you use or not, like vmConsole app or were disappointed
by it. As I said, this is a personal project and it does what I need. Think
about that before sending me a blaming email regarding support. If you have
lost your data, then only you are responsible for mistakes and misread
terminal messages. Remember that [author] does not owe anything for you.

## Credits

- [Alpine Linux]: the operating system used in vmConsole.
- [ConnectBot]: the recommended SSH client for use with vmConsole.
- [QEMU]: the emulator and virtualizer, a core of vmConsole.
- [Termux]: the famous terminal emulator for [Android OS], vmConsole uses
  certain parts of it.

[author]: https://github.com/sylirre
[Android OS]: https://www.android.com
[Alpine Linux]: https://alpinelinux.org
[Alpine Linux Wiki]: https://wiki.alpinelinux.org/wiki/Main_Page
[ConnectBot]: https://github.com/connectbot/connectbot
[Limbo PC]: https://github.com/limboemu/limbo
[QEMU]: https://qemu.org
[Termux]: https://termux.dev
[UserLAnd]: https://github.com/CypherpunkArmory/UserLAnd
[Wiki]: https://github.com/sylirre/vmConsole/wiki

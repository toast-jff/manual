# Toast manual.

related links:
- [discussion on reddit](https://www.reddit.com/r/osdev/comments/1giiep1/discussion_of_a_bumping_idea_from_my_head_about/)

problem behind the idea: (Thanks to everyone left a comment here)
- unnecessarity of put torrent in kernel level, cause if i want speed up during the installation part, a network UEFI/BIOS support for torrent is enough.
- same for use torrent base package manager.


> [!NOTE]  
> toast till 11/05/2024 is just a idea, there's no any official bootable image or distribution.
> and toast is almost useless without internet.

> next generation of operating system.

Toast stand for tos (torrent operating system).

## Overview

in author's idea the tos operating system use it's self package manager or call it downloader? to organize everything.

including config, binary file, sharing file 

author's expect for tos is a distribute system, as the torrent protocol will be embedded in the kernel level.

## Notice

toast is an operating system, reference to the recent activity in linux(10/25/2024) i decided to use special license.

> TODO

## dig into toast.

the kernel level has a built in torrent stuff, the kernel itself manage the whole system as a torrent seed.

there's two level of torrent stuff
- kernel level
- user level

the classic application of kernel level torrent is the bootable iso file, yes, the boot file is a quite small file compare to most distro's install guide. 
the classic application of user level torrent is its package manager(tpg)

of course the bootable file can not be as simple as the torrent file, you need net driver to connect the whole internet. but the other part is just the same as a small and simple torrent file.

customization? yes of course there's customization, 

in the toast's world, there's no server, every compute unit runs on tos is a seeding server.


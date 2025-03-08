---
title: "Kuroko is in edge/community on Alpine aports"
---

Well, it took a while but it worked.

Kuroko is now in edge/community on Alpine. It took a while to get here. Total of 2 merge requests.

[testing/kuroko: new aport (!78565)](https://gitlab.alpinelinux.org/alpine/aports/-/merge_requests/78565)
[community/kuroko: move from testing (!80770)](https://gitlab.alpinelinux.org/alpine/aports/-/merge_requests/80770)

With this addition, I've been trying to learn Kuroko. I know, I know. Adding a language to Alpine aports when you don't even know how to program for it sounds like a terrible idea.

Along with learning Kuroko, I'm making a distro with Kuroko in userspace and musl as the libs. Unfortunately, os.system in Kuroko doesn't seem to work on the distro (err code -1) but it works on Arch and Alpine?

It's a weird case but it's a thing I'll probably be able to fix.

Anyways, more to come in the works. I still need to post about [Arikoto](https://arikoto.nerdnextdoor.net) (my operating system development project) and other misc things that I'm involved in.

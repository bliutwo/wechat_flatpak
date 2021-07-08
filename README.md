# Attempt to Install WeChat on Linux

So I want to figure out how to install WeChat on Linux because one giant pain in the ass is that while I love using Linux, not having WeChat severely limits my communication with some certain family and friends.

So I'm going to try the following:

- [x] Make a Github repo for this.
- [x] Do research to see what solutions currently exist.
  - Some links are below.
  - Not all links have been thoroughly processed.
- [x] ~~Install WeChat as fast as possible (probably WINE) on an Ubuntu VM~~
  - Eh, I've done it before, and honestly it's a pain in the ass.
- [x] ~~Install WeChat as fast as possible (probably WINE) on a *Fedora* VM~~
  - Probably the same issues as before, but also I don't want to dedicate too much space to a VM.
- [ ] Install WeChat in a podman container.
- [ ] Figure out how to package WINE into a Flatpak
- [ ] Install WeChat on WINE on a Flatpak
- [ ] Submit it to Flathub


## (Potentially) Useful links / Research

- [Winepak Is A Flatpak Repository For Windows (Wine) Games And Applications](https://www.linuxuprising.com/2018/06/winepak-is-flatpak-repository-for.html)
- [Bottles](https://flathub.org/apps/details/com.usebottles.bottles): "Run Windows software"
  - For some reason, when running the Flatpak version of Bottles, the "runner" wouldn't install.
- [Winepak](https://www.winepak.org/): "Making Microsoft Windows applications Just Work™ under Linux"
  - NOTE: The winepak repository of applications doesn't look actively maintained or updated.
- [Fedora Classroom: Containers 101 with Podman](https://fedoramagazine.org/fedora-classroom-containers-101-podman/)
- [(Youtube video) Containers 101 with Podman on Fedora 29](https://www.youtube.com/watch?v=lc2rR_0Ie5g)
- [Flatpak docs: Introduction to Flatpak](https://docs.flatpak.org/en/latest/introduction.html)

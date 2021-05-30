### Hi there 👋
#### This is 135e2's github profile :)
- Living in: :cn:
- ArchLinux User
- :point_right: Currently maintaining an ArchLinux repo mirror of [Liquorix Kernel](https://liquorix.net) for Chinese users
- [Experimental]Now we use onedrive as the backend storage, which will be mirrored every 1 hour
- You can add it manually to /etc/pacman.conf following [this](https://wiki.archlinux.org/title/Unofficial_user_repositories#liquorix):
>[liquorix]  
Server = https://mirror.135e2.eu.org/onedrive-mirror/liquorix-archlinux

- Anyway, you can stick with the old repo too (which will be synced every 6 hours):
>[liquorix]  
Server = https://mirror.135e2.eu.org/archlinux/$repo/$arch  

And also my own repo:
* Import PGP Key:  
`pacman-key -r 5443E4D4C99F250F --keyserver keys.openpgp.org`
* Trust it:  
`pacman-key --lsign-key 5443E4D4C99F250F --keyserver keys.openpgp.org`
>[135e2]  
Server = https://mirror.135e2.eu.org/archlinux/$repo/$arch  
#SigLevel = Never

[![135e2's GitHub stats](https://github-readme-stats.vercel.app/api?username=135e2&theme=vue&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)

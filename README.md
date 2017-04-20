Docker Hacklab
===

> My personal hacklab

Quick Start
---

```
$ docker run -d --name hacklab --net=host --privileged -it stoneo/docker-hacklab
 _  _   _   ___ _  ___      _   ___
| || | /_\ / __| |/ / |    /_\ | _ )
| __ |/ _ \ (__| ' <| |__ / _ \| _ \
|_||_/_/ \_\___|_|\_\____/_/ \_\___/
https://github.com/stoneo/docker-hacklab
```

Run other vuln scanners
---

```bash
docker run -d --name nessus -p 8834:8834 infoslack/nessus
docker run -d --name openvas -p 443:443 -p 9390:9390 -p 9391:9391 mikesplain/openvas
```

Run vulnerable web application
---

`docker run -d --name dvwa -it -p 80:80 vulnerables/web-dvwa`

Doxing/OSINT
---

- http://www.peekyou.com/
- https://pipl.com/

Exploit database
---

- http://cve.mitre.org/
- http://0day.today/
- https://nvd.nist.gov/
- http://www.securityfocus.com/bid/
- https://www.exploit-db.com/

Other resources
---

- https://gexos.github.io/Hacking-Tools-Repository/
- https://github.com/enaqx/awesome-pentest
- https://github.com/Hack-with-Github/Awesome-Hacking
- https://github.com/sindresorhus/awesome#security
- https://github.com/carpedm20/awesome-hacking
- https://penetration-testing.zeef.com/jeroen.rijken
- http://sectools.org/
- http://pwnwiki.io/
- https://www.cybrary.it/
- http://null-byte.wonderhowto.com/
- https://hackademics.fr
- https://github.com/gchq/CyberChef
- https://github.com/danielmiessler/SecLists
- https://pentest-tools.com/
- https://instant-hack.io/
- http://zenk-security.com/
- https://www.hacksplaining.com/
- http://pentestmonkey.net/cheat-sheet/sql-injection/mysql-sql-injection-cheat-sheet
- https://www.youtube.com/user/Hak5Darren/videos
- https://www.youtube.com/user/DEFCONConference/videos
- https://www.youtube.com/user/BlackHatOfficialYT/videos
- https://www.youtube.com/user/JackkTutorials/videos
- https://www.youtube.com/channel/UCO51Z4c1R8EPHZioGwgBmDw/videos
- https://www.youtube.com/playlist?list=PLkRo97mCIn9lgvE7AskNsmwJVOlJX2zaI
- https://www.youtube.com/channel/UC286ntgASMskhPIJQebJVvA/videos
- https://www.youtube.com/user/gaytony10/playlists
- https://www.youtube.com/user/bhargavtandel/videos

License
---

MIT

Free Software, Hell Yeah !

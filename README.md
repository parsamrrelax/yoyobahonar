# Outline Bridge Server

1. Aval outline manager ro ru ye systemi joz hostet nasb kon.
2. Bad docker va docker-compose ro ru hostet nasb kon.

### Debian Based Systems
```
apt install docker docker-compose -y
```
### Arch Based Systems
```
pacman -S docker docker-compose -y
```
### Fedora Based Systems
```
dnf install docker docker-compose -y
```

Bayad root bashi ta command haye bala ro ejra koni.
Age nemiduni root hasti ya na type kon ==whoami== . age javabesh root bood rooti.
Age nisti avale har dastoor ==sudo== bezar.

3. In repository ro clone kon be serveret.
```
git clone https://github.com/parsamrrelax/yoyobahonar
```
4. outline ro ke nasb kardi az settingesh hostname ro bardar.
5. dakhele foldere in repository sho. va code python ro run kon
```
cd yoyobahonar
./setup.py
```
    age servet python nadare tebghe dastooraye 2 package python va python3 ro nasb kon.
6. vaghti code azat porsid chizi k tu 4 copy kardi ro benevis inja.
7. vaghti azat port khast ye port delkhah ke darhale estefade nist behesh bede. man 1000 dadam.
8. age hagh hagh hagh gerefti kar karde.
9. docker ro biar bala
```
docker-compose up -d
```
10. boro tu barname outlinet va domainet ya ip khodet va portet ro tu settingesh jaygozin kon.
11. access key haye ghadimi ro pak kon va jadid besaz ba har esmi ke mikhay.
12. sharing is caring my brother.

Chizayi k azashoon estefade kardam:

    GitHub:
        Image: ghcr.io/getimages/v2fly-core:v4.45.2
        URL: https://github.com/orgs/getimages/packages/container/package/v2fly-core
        Digest: sha256:289fc9451f21a265f95615e29f05ea23bc32026db152863eee317738813521d7
    Docker Hub:
        Image: v2fly/v2fly-core:v4.45.2
        URL: https://hub.docker.com/r/v2fly/v2fly-core/tags
        Digest: sha256:289fc9451f21a265f95615e29f05ea23bc32026db152863eee317738813521d7

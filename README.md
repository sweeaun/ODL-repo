# ODL-repo
Repo testing 


Steps:
1) repo init -b ODL-base -u https://github.com/sweeaun/ODL-repo
2) repo sync
3) cd odl
4) source oe-init-build-env
5) export TEMPLATECONF=$PWD/meta-yocto/meta-poky/conf
6) Modify conf/bblayer.conf according
7) bitbake core-image-minimal

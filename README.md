# DA153
DirectAdmin is programmed to be the fastest running control panel available. ... DirectAdmin avoids downtime by automatically recovering from crashes.

installation

yum -y update

yum install wget gcc gcc-c++ flex bison make bind bind-libs bind-utils openssl openssl-devel perl quota libaio \
yum install libcom_err-devel libcurl-devel gd zlib-devel zip unzip libcap-devel cronie bzip2 cyrus-sasl-devel perl-ExtUtils-Embed \
yum install autoconf automake libtool which patch mailx bzip2-devel lsof glibc-headers kernel-devel expat-devel db4-devel

CentOS 7

yum install psmisc net-tools systemd-devel libdb-devel perl-DBI xfsprogs rsyslog logrotate crontabs file

wget https://raw.githubusercontent.com/PakCyberpyrates/DA153/master/setup.sh

chmod 755 setup.sh

./setup.sh


For update or any bug issue  kindly report at nullBase
https://www.nullbase.org/forums/DirectadminRelease/

SysV init script for redis-sentinel. redis-server package doesn't have one. Uses `start-stop-daemon`, works only in Debian/Ubuntu.

**P.S.** If this code is useful for you - don't forget to put a star on it's [github repo](https://github.com/selivan/redis-sentinel-sysv-service).

**UPD**: Init script appeared in packages from [ppa:chris-lea/redis-server](https://launchpad.net/~chris-lea/+archive/ubuntu/redis-server) since redis version 3.2.

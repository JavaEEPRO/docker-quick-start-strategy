# docker-quick-start-strategy
  starting with docker 

simple steps for installing (and testing) docker at target machine, and future deploying container there (with testing)

#  1. check bios setting for virtual machine isEnabled (default:false)
#  2. download toolbox (instead of docker)







# show all created volumes
docker volume ls

# set new volume 
 mount --help
Usage: mount [OPTION] [<win32path> <posixpath>]
       mount -a
       mount <posixpath>

Display information about mounted filesystems, or mount a filesystem

  -a, --all                     mount all filesystems mentioned in fstab
  -c, --change-cygdrive-prefix  change the cygdrive path prefix to <posixpath>
  -f, --force                   force mount, don't warn about missing mount
                                point directories
  -h, --help                    output usage information and exit
  -m, --mount-entries           write fstab entries to replicate mount points
                                and cygdrive prefixes
  -o, --options X[,X...]        specify mount options
  -p, --show-cygdrive-prefix    show user and/or system cygdrive path prefix
  -V, --version                 output version information and exit

Valid options are: acl,auto,binary,bind,cygexec,dos,exec,ihash,noacl,nosuid,notexec,nouser,override,posix=0,posix=1,sparse,text,user


# remove unused volumes
docker volume prune

folders : 

      /boot : used by boot loader(grub.cfg)
      /root : user home directory. It is not same as /
      /dev : system devices (peripheral devices as files)
      /etc : configuration files. any kind of app runs on linux(eg :dns)
              take backup before modify
      /bin -> /usr/bin : Everday user commands like ls, pwd ...
      /sbin -> /usr/bin : system/filesystem commands
      /opt : optional add-on applications (not part of os, third party like oracle)
      /proc : running process (only exist in memory)
      /lib -> usr/lib : c prog lib needed by commands and apps
              strace -e open pwd
      /tmp : temporary files
      /var : system logs(application log: troubleshoot/debug)
      /run : system daemon that start very early (eg: systemd and udev)
              to store temporary runtime files like pid files : process id
      /mnt : to mound external filesystem (eg NFS)
      /media : for cdrom mounts

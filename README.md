# command-center

Commonly available command-line tools for Linux distros listed somewhat categorically.

## Help

- `man` - format and display the on-line manual pages ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/man.md), [die](https://linux.die.net/man/1/man), [manned](https://manned.org/man))
- `info` - read info docs ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/info.md), [die](https://linux.die.net/man/1/info), [manned](https://manned.org/info))
- `whatis` - search the whatis database for complete words ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/whatis.md), [die](https://linux.die.net/man/1/whatis), [manned](https://manned.org/whatis))
    - `apropos` - search the whatis database for string ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/apropos.md), [die](https://linux.die.net/man/1/apropos), [manned](https://manned.org/apropos))

## Terminal

- `printf` - format and print data ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/printf.md), [manned](https://manned.org/printf))
- `printenv` - print all or part of environment ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/printenv.md), [die](https://linux.die.net/man/1/printenv), [manned](https://manned.org/printenv))
- `clear` - clear the terminal screen ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/clear.md), [die](https://linux.die.net/man/1/clear), [manned](https://manned.org/clear))
- `tty` - print the file name of the terminal connected to standard input ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/tty.md), [die](https://linux.die.net/man/1/tty), [manned](https://manned.org/tty))
- `stty` - change and print terminal line settings ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/stty.md), [die](https://linux.die.net/man/1/stty), [manned](https://manned.org/stty))
- `setterm` - set terminal attributes ([manned](https://manned.org/setterm))
- `screen` - screen manager with VT100/ANSI terminal emulation ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/screen.md), [die](https://linux.die.net/man/1/screen), [manned](https://manned.org/screen))
- `cd` - Change the current working directory ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/cd.md), [manned](https://manned.org/cd))
- `alias` - define or display aliases ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/alias.md), [manned](https://manned.org/alias))
    - `unalias` - remove alias definitions ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/unalias.md), [manned](https://manned.org/unalias))
- `locale` - get locale-specific information ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/locale.md), [manned](https://manned.org/locale))
- `tput` - initialize a terminal or query terminfo database ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/tput.md), [manned](https://manned.org/tput))
    - `reset` - terminal initialization ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/reset.md), [manned](https://manned.org/reset))
    - `tset` - terminal initialization ([manned](https://manned.org/tset))
- `getopts` - parse utility options ([manned](https://manned.org/getopts))
- `read` - read from standard input into shell variables ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/read.md), [manned](https://manned.org/read.1posix))
- `true` - do nothing, successfully ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/true.md), [manned](https://manned.org/true))
- `false` - do nothing, unsuccessfully ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/false.md), [manned](https://manned.org/false.1))

### History

- `fc` - process the command history list ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/fc.md), [manned](https://manned.org/fc))
- `history` - GNU History Library ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/history.md), [manned](https://manned.org/history))

### Typescripts

- `script` - make typescript of terminal session ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/script.md), [manned](https://manned.org/script))
- `scriptreplay` - play back typescripts, using timing information ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/scriptreplay.md), [manned](https://manned.org/scriptreplay.1))
- `scriptlive` - re-run session typescripts, using timing information ([manned](https://manned.org/scriptlive.1))

## Hardware

### Hardware Information

- `lshw` - list hardware information ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/lshw.md), [die](https://linux.die.net/man/1/lshw), [manned](https://manned.org/lshw))
- `lscpu` - list CPU architecture information ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/lscpu.md), [die](https://linux.die.net/man/1/lscpu), [manned](https://manned.org/lscpu))
    - `cat /proc/cpuinfo`
- `lspci` - list all PCI devices ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/lspci.md), [die](https://linux.die.net/man/8/lspci), [manned](https://manned.org/lspci))
- `lsusb` - list USB device info ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/lsusb.md), [die](https://linux.die.net/man/8/lsusb), [manned](https://manned.org/lsusb.1))
- `free` - display amount of free and used memory in the system ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/free.md), [die](https://linux.die.net/man/1/free), [manned](https://manned.org/free))
- `lsmem` - list the ranges of available memory with their online status ([manned](https://manned.org/lsmem))
- `nproc` - print the number of processing units available ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/nproc.md), [manned](https://manned.org/nproc))

### Hardware Configuration

- `chcpu` - configure CPUs ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/chcpu.md), [die](https://linux.die.net/man/8/chcpu), [manned](https://manned.org/chcpu))
- `chmem` - configure memory ([manned](https://manned.org/chmem))
- `eject` - eject removable media ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/eject.md), [manned](https://manned.org/eject))

## System

### System Information

- `uname` - print system information ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/uname.md), [die](https://linux.die.net/man/1/uname), [manned](https://manned.org/uname))
    - `arch` - print machine hardware name (same as `uname -m`) ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/arch.md), [manned](https://manned.org/arch))
- `setarch` - change reported architecture in new program environment and/or set personality flags ([manned](https://manned.org/setarch))
- `last` - show listing of last logged in users / last reboot ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/last.md), [die](https://linux.die.net/man/1/last), [manned](https://manned.org/last))
- `lslogins` - display information about known users in the system
- `uptime` - tell how long the system has been running ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/uptime.md), [die](https://linux.die.net/man/1/uptime), [manned](https://manned.org/uptime))
- `runlevel` - output previous and current runlevel ([die](https://linux.die.net/man/8/runlevel), [manned](https://manned.org/runlevel))
- `dmesg` - print or control the kernel ring buffer ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/dmesg.md), [die](https://linux.die.net/man/1/dmesg), [manned](https://manned.org/dmesg))
- `logger` - enter messages into the system log ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/logger.md), [manned](https://manned.org/logger))

### System State

- `login` - sign on ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/login.md), [die](https://linux.die.net/man/1/login), [manned](https://manned.org/login))
  - `newgrp` - log in to a new group ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/newgrp.md), [manned](https://manned.org/newgrp))
- `sulogin` - single-user login ([manned](https://manned.org/sulogin))
- `reboot` - reboot or stop the system ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/reboot.md), [die](https://linux.die.net/man/8/reboot), [manned](https://manned.org/reboot))
- `shutdown` - bring the system down ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/shutdown.md), [die](https://linux.die.net/man/8/shutdown), [manned](https://manned.org/shutdown))
- `poweroff` - reboot or stop the system ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/poweroff.md), [die](https://linux.die.net/man/8/poweroff), [manned](https://manned.org/poweroff))
- `rtcwake` - enter a system sleep state until specified wakeup time ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/rtcwake.md), [manned](https://manned.org/rtcwake))
- `telinit` - change system runlevel ([die](https://linux.die.net/man/8/telinit), [manned](https://manned.org/telinit))
- `ctrlaltdel` - set the function of the Ctrl-Alt-Del combination ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/ctrlaltdel.md), [manned](https://manned.org/ctrlaltdel))

### System Date/Time

- `date` - print or set the system date and time ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/date.md), [die](https://linux.die.net/man/1/date), [manned](https://manned.org/date))
- `cal` - displays a calendar ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/cal.md), [die](https://linux.die.net/man/1/cal), [manned](https://manned.org/cal))
- `calendar` - reminder service (holidays, meetings, ...) ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/calendar.md), [die](https://linux.die.net/man/1/calendar), [manned](https://manned.org/calendar))
- `sleep` - delay for a specified amount of time ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/sleep.md), [die](https://linux.die.net/man/1/sleep), [manned](https://manned.org/sleep))
- `hwclock` - time clocks utility ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/hwclock.md), [manned](https://manned.org/hwclock))

### Namespaces

- `nsenter` - run program in different namespaces ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/nsenter.md), [manned](https://manned.org/nsenter.1))
- `lsns` - list namespaces ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/lsns.md), [manned](https://manned.org/lsns))
- `unshare` - run program in new namespaces ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/unshare.md), [manned](https://manned.org/unshare))

## Users/Groups

### Users

#### User Information

- `logname` - print current user's login name ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/logname.md), [die](https://linux.die.net/man/1/logname), [manned](https://manned.org/logname))
- `id` - print real and effective user and group IDs  ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/id.md), [die](https://linux.die.net/man/1/id), [manned](https://manned.org/id))
    - `whoami` - print effective userid. same as `id -un` ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/whoami.md), [die](https://linux.die.net/man/1/whoami), [manned](https://manned.org/whoami))
- `w` - show who is logged on and what they are doing ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/w.md), [die](https://linux.die.net/man/1/w), [manned](https://manned.org/w))
- `who` - show who is logged on ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/who.md), [die](https://linux.die.net/man/1/who), [manned](https://manned.org/who))
  - `utmpdump` - dump UTMP and WTMP files in raw format ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/utmpdump.md), [manned](https://manned.org/utmpdump))
- `users` - print the user names of users currently logged in to the current host ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/users.md), [die](https://linux.die.net/man/1/users), [manned](https://manned.org/users))
- `finger` - user information lookup program ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/finger.md), [die](https://linux.die.net/man/1/finger), [manned](https://manned.org/finger))
    - `pinky` - lightweight finger ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/pinky.md), [manned](https://manned.org/pinky))

#### User Management

- `useradd` - create a new user or update default new user information  ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/useradd.md), [die](https://linux.die.net/man/8/useradd), [manned](https://manned.org/useradd))
    - `newusers` - update and create new users in batch ([die](https://linux.die.net/man/8/newusers), [manned](https://manned.org/newusers))
- `usermod` - modify a user account ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/usermod.md), [die](https://linux.die.net/man/8/usermod), [manned](https://manned.org/usermod))
- `userdel` - delete a user account and related files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/userdel.md), [die](https://linux.die.net/man/8/userdel), [manned](https://manned.org/userdel))
- `passwd` - update user's authentication ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/passwd.md), [die](https://linux.die.net/man/1/passwd), [manned](https://manned.org/passwd))
- `chsh` - change your (or another user's) login shell ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/chsh.md), [die](https://linux.die.net/man/1/chsh), [manned](https://manned.org/chsh))
- `chpasswd` - update passwords in batch mode ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/chpasswd.md), [die](https://linux.die.net/man/8/chpasswd), [manned](https://manned.org/chpasswd))
- `vipw` - edit the password file ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/vipw.md), [manned](https://manned.org/vipw))
- `vigr` - edit the group file ([manned](https://manned.org/vigr))
- `chfn` - change your (or another user's) finger information ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/chfn.md), [die](https://linux.die.net/man/1/chfn), [manned](https://manned.org/chfn))

#### User Communication

- `wall` - write a message to all users ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/wall.md), [manned](https://manned.org/wall))
- `mesg` - display (or do not display) messages from other users ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/mesg.md), [manned](https://manned.org/mesg))
- `write` - send a message to another user ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/write.md), [die](https://linux.die.net/man/1/write), [manned](https://manned.org/write))

#### User Substituion/Masquerading

- `su` - run a shell with substitute user and group IDs ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/su.md), [die](https://linux.die.net/man/1/su), [manned](https://manned.org/su))
- `runuser` - run a shell with substitute user and group IDs ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/runuser.md), [die](https://linux.die.net/man/1/runuser), [manned](https://manned.org/runuser))
- `setpriv` - run a program with different Linux privilege settings ([manned](https://manned.org/setpriv))
- `sudo` - execute a command as another user ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/sudo.md), [die](https://linux.die.net/man/8/sudo), [manned](https://manned.org/sudo))
- `visudo` - edit the sudoers file ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/visudo.md), [die](https://linux.die.net/man/8/visudo), [manned](https://manned.org/visudo))
- `sudoreplay` - replay sudo session logs ([die](https://linux.die.net/man/8/sudoreplay), [manned](https://manned.org/sudoreplay))
    - `sudoreplay -l user millert` - list sessions ran by user millert
    - `sudoreplay -l user bob command vi` - list sessions run by user bob with a command containing the string vi

### Groups
    
- `groups` - print the groups a user is in  ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/groups.md), [die](https://linux.die.net/man/1/groups), [manned](https://manned.org/groups))
- `groupadd` - create a new group ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/groupadd.md), [die](https://linux.die.net/man/8/groupadd), [manned](https://manned.org/groupadd))
- `groupmod` - modify a group definition on the system ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/groupmod.md), [die](https://linux.die.net/man/8/groupmod), [manned](https://manned.org/groupmod))
- `groupdel` - delete a group ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/groupdel.md), [die](https://linux.die.net/man/8/groupdel), [manned](https://manned.org/groupdel))


## Processes/Tasks/Commands

### Process Information

- `strace -p <pid> -p <pid> ...` - trace one or more currently running process IDs ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/strace.md), [die](https://linux.die.net/man/1/strace), [manned](https://manned.org/strace))
- `ps` - report a snapshot of the current processes ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ps.md), [die](https://linux.die.net/man/1/ps), [manned](https://manned.org/ps))
- `pgrep` - look up processes based on name and other attributes ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/pgrep.md), [die](https://linux.die.net/man/1/pgrep), [manned](https://manned.org/pgrep))
    - `pgrep -a <pattern>` - list complete command line
    - `pgrep -f <pattern>` - use full process name to match
- `top` - display Linux tasks ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/top.md), [die](https://linux.die.net/man/1/top), [manned](https://manned.org/top))
    - `htop` - interactive process viewer ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/htop.md), [die](https://linux.die.net/man/1/htop), [manned](https://manned.org/htop))
    - `iotop` - simple top-like I/O monitor ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/iotop.md), [die](https://linux.die.net/man/1/iotop), [manned](https://manned.org/iotop))
- `pstree` - display a tree of processes ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/pstree.md), [die](https://linux.die.net/man/1/pstree), [manned](https://manned.org/pstree))
- `taskset` - retrieve or set a process's CPU affinity ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/taskset.md), [die](https://linux.die.net/man/1/taskset), [manned](https://manned.org/taskset))
- `fuser` - show which processes use the named files, sockets, or filesystems ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/fuser.md), [die](https://linux.die.net/man/1/fuser), [manned](https://manned.org/fuser))

### Update Process Information

- `renice` - alter priority of running processes ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/renice.md), [die](https://linux.die.net/man/1/renice), [manned](https://manned.org/renice))
- `chrt` - manipulate real-time attributes of a process ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/chrt.md), [die](https://linux.die.net/man/1/chrt), [manned](https://manned.org/chrt))
- `choom` - display and adjust OOM-killer score ([manned](https://manned.org/choom))
- `prlimit` - get and set process resource limits ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/prlimit.md), [manned](https://manned.org/prlimit))

### Kill/Signal Process

- `kill` - terminate a process ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/kill.md), [die](https://linux.die.net/man/1/kill), [manned](https://manned.org/kill))
- `killall` - kill processes by name ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/killall.md), [die](https://linux.die.net/man/1/killall), [manned](https://manned.org/killall))
- `pkill` - signal processes based on name and other attributes ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/pkill.md), [die](https://linux.die.net/man/1/pkill), [manned](https://manned.org/pkill))

### Run Command

- `xargs` - build and execute command lines from standard input ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/xargs.md), [manned](https://manned.org/xargs))
- `time` - time a simple command or give resource usage ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/time.md), [die](https://linux.die.net/man/1/time), [manned](https://manned.org/time))
- `timeout` - run a command with a time limit ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/timeout.md), [die](https://linux.die.net/man/1/timeout), [manned](https://manned.org/timeout))
- `setsid` - run a program in a new session ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/setsid.md), [manned](https://manned.org/setsid))
- `strace` - run a command and trace system calls and signals ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/strace.md), [die](https://linux.die.net/man/1/strace), [manned](https://manned.org/strace))
- `nice` - run a command with modified scheduling priority ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/nice.md), [die](https://linux.die.net/man/1/nice), [manned](https://manned.org/nice))
- `nohup` - run a command immune to hangups, with output to a non-tty ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/nohup.md), [die](https://linux.die.net/man/1/nohup), [manned](https://manned.org/nohup))
- `env` - run a command in a modified environment ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/env.md), [die](https://linux.die.net/man/1/env), [manned](https://manned.org/env))
- `watch` - run a command periodically, displaying its output ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/watch.md), [die](https://linux.die.net/man/1/watch), [manned](https://manned.org/watch))
- `daemonize` - run a program as a Unix daemon ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/daemonize.md), [die](https://linux.die.net/man/1/daemonize), [manned](https://manned.org/daemonize))

### Jobs/Schedule Command

- `fg` - run jobs in the foreground ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/fg.md), [manned](https://manned.org/fg))
- `bg` - run jobs in the background ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/bg.md), [manned](https://manned.org/bg))
- `jobs` - display status of jobs in the current session ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/jobs.md), [manned](https://manned.org/jobs))
- `wait` - wait for process to change state ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/wait.md), [manned](https://manned.org/wait))
- `at` - executes commands at a specified time ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/at.md), [die](https://linux.die.net/man/1/at), [manned](https://manned.org/at))
    - `atq` - list pending jobs ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/atq.md), [die](https://linux.die.net/man/1/atq), [manned](https://manned.org/atq))
    - `atrm` - remove jobs by ID ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/atrm.md), [die](https://linux.die.net/man/1/atrm), [manned](https://manned.org/atrm))
    - `batch` - executes commands when system load levels permit ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/batch.md), [die](https://linux.die.net/man/1/batch), [manned](https://manned.org/batch))
- cron
    - `crontab` - maintain crontab files for individual users ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/crontab.md), [die](https://linux.die.net/man/1/crontab), [manned](https://manned.org/crontab))

### Inter-Process Communication

- `ipcmk` - make various IPC resources ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/ipcmk.md), [manned](https://manned.org/ipcmk))
- `ipcs` - show information on IPC facilities ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ipcs.md), [manned](https://manned.org/ipcs.1))
- `lsipc` - show information on IPC facilities currently employed in the system ([manned](https://manned.org/lsipc))
- `ipcrm` - remove certain IPC resources
 ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/ipcrm.md), [manned](https://manned.org/ipcrm))
## Networking

### Network Configuration

- `ip` - show / manipulate routing, devices, policy routing and tunnels ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/ip.md), [die](https://linux.die.net/man/8/ip), [manned](https://manned.org/ip))
    - `iptunnel` - creates, deletes, and displays configured tunnels ([die](https://linux.die.net/man/8/iptunnel), [manned](https://manned.org/iptunnel))
- `ifconfig` - configure a network interface ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ifconfig.md), [die](https://linux.die.net/man/8/ifconfig), [manned](https://manned.org/ifconfig))
    - replaced by `ip addr`, `ip link`, and `ip -s link`
- `route` - show / manipulate the IP routing table ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/route.md), [die](https://linux.die.net/man/8/route), [manned](https://manned.org/route))
    - replaced by `ip route`
- `iptables` - administration tool for IPv4/IPv6 packet filtering and NAT ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/iptables.md), [die](https://linux.die.net/man/8/iptables), [manned](https://manned.org/iptables))
    - `ip6tables` - administration tool for IPv6 packet filtering and NAT ([die](https://linux.die.net/man/8/ip6tables), [manned](https://manned.org/ip6tables))
- `ipset` - administration tool for IP sets ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/ipset.md), [die](https://linux.die.net/man/8/ipset), [manned](https://manned.org/ipset))
- `tc` - show / manipulate traffic control settings ([die](https://linux.die.net/man/8/tc), [manned](https://manned.org/tc))

### Remote Administration

- `ssh` - OpenSSH SSH client (remote login program) ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ssh.md), [die](https://linux.die.net/man/1/ssh), [manned](https://manned.org/ssh))
    - `scp` - secure copy (remote file copy program) ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/scp.md), [die](https://linux.die.net/man/1/scp), [manned](https://manned.org/scp))
    - `sftp` - secure file transfer program ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/sftp.md), [die](https://linux.die.net/man/1/sftp), [manned](https://manned.org/sftp))
    - `ssh-agent` - authentication agent ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ssh-agent.md), [die](https://linux.die.net/man/1/ssh-agent), [manned](https://manned.org/ssh-agent))
        - `ssh-add` - adds RSA or DSA identities to the authentication agent ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ssh-add.md), [die](https://linux.die.net/man/1/ssh-add), [manned](https://manned.org/ssh-add))
    - `ssh-keygen` - authentication key generation, management and conversion ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ssh-keygen.md), [die](https://linux.die.net/man/1/ssh-keygen), [manned](https://manned.org/ssh-keygen))
- `telnet` - user interface to the TELNET protocol ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/telnet.md), [die](https://linux.die.net/man/1/telnet), [manned](https://manned.org/telnet))


### Transfer

- `wget` - non-interactive network downloader  ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/wget.md), [die](https://linux.die.net/man/1/wget), [manned](https://manned.org/wget))
- `curl` - transfer a URL ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/curl.md), [die](https://linux.die.net/man/1/curl), [manned](https://manned.org/curl))
    - `curl -O` - download a file
- `ftp` - Internet file transfer program ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ftp.md), [die](https://linux.die.net/man/1/ftp), [manned](https://manned.org/ftp))

### DNS/WHOIS

- `dig` - DNS lookup utility ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/dig.md), [die](https://linux.die.net/man/1/dig), [manned](https://manned.org/dig))
- `host` - DNS lookup utility ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/host.md), [die](https://linux.die.net/man/1/host), [manned](https://manned.org/host))
- `nslookup` - Internet name servers interactively ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/nslookup.md), [die](https://linux.die.net/man/1/nslookup), [manned](https://manned.org/nslookup))
- `hostname` - show or set the system's host name ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/hostname.md), [die](https://linux.die.net/man/1/hostname), [manned](https://manned.org/hostname))
    - `hostname -I` - all addresses for the host
    - `hostname -i` - addresses for the host name
    - `domainname` - show or set the system's NIS/YP domain name ([die](https://linux.die.net/man/1/domainname), [manned](https://manned.org/domainname))
    - `dnsdomainname` - show the system's DNS domain name ([die](https://linux.die.net/man/1/dnsdomainname), [manned](https://manned.org/dnsdomainname))
- `whois` - client for the whois service ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/whois.md), [die](https://linux.die.net/man/1/whois), [manned](https://manned.org/whois))

### Investigation/Discovery/Exploration

- `ping` - send ICMP ECHO_REQUEST to network hosts ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ping.md), [die](https://linux.die.net/man/8/ping), [manned](https://manned.org/ping))
    - `ping6` (IPv6) ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ping6.md), [die](https://linux.die.net/man/8/ping6), [manned](https://manned.org/ping6))
- `ss` - another utility to investigate sockets ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/ss.md), [die](https://linux.die.net/man/8/ss), [manned](https://manned.org/ss))
- `netstat` - Print network connections, routing tables, interface statistics, masquerade connections, and multicast memberships. This  program  is mostly obsolete.  ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/netstat.md), [die](https://linux.die.net/man/8/netstat), [manned](https://manned.org/netstat))
    - replacement for `netstat` is `ss`
    - replacement for `netstat -r` is `ip route`
    - replacement for `netstat -i` is `ip -s link`
    - replacement for `netstat -g` is `ip maddr`.
- `traceroute` - print the route packets trace to network host ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/traceroute.md), [die](https://linux.die.net/man/8/traceroute), [manned](https://manned.org/traceroute))
- `tracepath` - traces path to a network host discovering MTU along this path ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/tracepath.md), [die](https://linux.die.net/man/8/tracepath), [manned](https://manned.org/tracepath))
- `nc` / `netcat` - arbitrary TCP and UDP connections and listens ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/nc.md), [die](https://linux.die.net/man/1/nc), [manned](https://manned.org/nc))
- `nmap` - Network exploration tool and security / port scanner ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/nmap.md), [die](https://linux.die.net/man/1/nmap), [manned](https://manned.org/nmap))
- `tcpdump` - dump traffic on a network ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/tcpdump.md), [die](https://linux.die.net/man/8/tcpdump), [manned](https://manned.org/tcpdump))


## Streams/Pipes

- `tee` - read from standard input and write to standard output and files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/tee.md), [die](https://linux.die.net/man/1/tee), [manned](https://manned.org/tee)) 
- `sed` - stream editor for filtering and transforming text ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/sed.md), [die](https://linux.die.net/man/1/sed), [manned](https://manned.org/sed))
- `awk` - pattern scanning and processing language ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/awk.md), [die](https://linux.die.net/man/1/awk), [manned](https://manned.org/awk))

## Filesystems

### Information

- `cat /proc/filesystems` - list filesystems your kernel supports
- `df` - report filesystem disk space usage ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/df.md), [die](https://linux.die.net/man/1/df), [manned](https://manned.org/df))
- `stat -f` - display file or file system status  ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/stat.md), [die](https://linux.die.net/man/1/stat), [manned](https://manned.org/stat))
- `findfs` - find a filesystem by label or UUID  ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/findfs.md), [die](https://linux.die.net/man/8/findfs), [manned](https://manned.org/findfs))
- `findmnt` - list all mounted filesytems or search for a filesystem ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/findmnt.md), [die](https://linux.die.net/man/8/findmnt), [manned](https://manned.org/findmnt))
 
### Block Devices

- `lsblk` - list block devices ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/lsblk.md), [die](https://linux.die.net/man/8/lsblk), [manned](https://manned.org/lsblk))
- `blkid` - command-line utility to locate/print block device attributes ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/blkid.md), [die](https://linux.die.net/man/8/blkid), [manned](https://manned.org/blkid))
- `blkdiscard` - discard sectors on a device ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/blkdiscard.md), [manned](https://manned.org/blkdiscard))
- `blkzone` - run zone command on a device ([manned](https://manned.org/blkzone))
- `blockdev` - call block device ioctls from the command line ([manned](https://manned.org/blockdev))
- `losetup` - set up and control loop devices ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/losetup.md), [manned](https://manned.org/losetup))
- `raw` - bind a Linux raw character device ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/raw.md), [manned](https://manned.org/raw.8))
- `zramctl` - set up and control zram devices ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/zramctl.md), [manned](https://manned.org/zramctl))

### Partitions

- `fdisk` - partition table manipulator for Linux  ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/fdisk.md), [die](https://linux.die.net/man/8/fdisk), [manned](https://manned.org/fdisk))
  - `fdisk -l` - display partitions and exit
- `cfdisk` - display or manipulate a disk partition table ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/cfdisk.md), [die](https://linux.die.net/man/8/cfdisk), [manned](https://manned.org/cfdisk))
- `parted` - a partition manipulation program ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/parted.md), [die](https://linux.die.net/man/8/parted), [manned](https://manned.org/parted))
- `addpart` - tell the kernel about the existence of a partition ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/addpart.md), [manned](https://manned.org/addpart))
- `resizepart` - tell the kernel about the new size of a partition ([manned](https://manned.org/resizepart))
- `delpart` - tell the kernel to forget about a partition ([manned](https://manned.org/delpart.8))
- `partx` - tell the kernel about the presence and numbering of on-disk partitions ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/partx.md), [manned](https://manned.org/partx))
- `sfdisk` - display or manipulate a disk partition table ([manned](https://manned.org/sfdisk))

### Mounting

- `mount` - mount a filesystem ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/mount.md), [die](https://linux.die.net/man/8/mount), [manned](https://manned.org/mount))
- `mountpoint` - see if a directory or file is a mountpoint ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/mountpoint.md), [manned](https://manned.org/mountpoint))
- `unmount` - unmount a filesystem ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/umount.md), [die](https://linux.die.net/man/2/umount), [manned](https://manned.org/umount))
   
### Repair/Create/Check/Debug

- `fsck` - check and repair a Linux filesystem ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/fsck.md), [die](https://linux.die.net/man/8/fsck), [manned](https://manned.org/fsck))
- `mkfs` - build a Linux filesystem ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/mkfs.md), [die](https://linux.die.net/man/8/mkfs), [manned](https://manned.org/mkfs))
- ext2/ext3/ext4
  - `mke2fs` - create an ext2/ext3/ext4 filesystem ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/mke2fs.md), [die](https://linux.die.net/man/8/mke2fs), [manned](https://manned.org/mke2fs))
  - `debugfs` - ext2/ext3/ext4 file system debugger ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/debugfs.md), [die](https://linux.die.net/man/8/debugfs), [manned](https://manned.org/debugfs))
  - `e2fsck` - check a Linux ext2/ext3/ext4 file system ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/e2fsck.md), [die](https://linux.die.net/man/8/e2fsck), [manned](https://manned.org/e2fsck))
  - `e2image` - Save critical ext2/ext3/ext4 filesystem metadata to a file ([tldr](https://github.com/    tldr-pages/tldr/blob/main/pages/linux/e2image.md), [die](https://linux.die.net/man/8/e2image), [manned](https://manned.org/e2image))
- `fsfreeze` - suspend access to a filesystem (Ext3/4, ReiserFS, JFS, XFS) ([manned](https://manned.org/fsfreeze))
- `fstrim` - discard unused blocks on a mounted filesystem ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/fstrim.md), [manned](https://manned.org/fstrim))
- `wipefs` - wipe a signature from a device ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/wipefs.md), [manned](https://manned.org/wipefs))

### Swaps

- `mkswap` - set up a Linux swap area ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/mkswap.md), [manned](https://manned.org/mkswap))
- `swaplabel` - print or change the label or UUID of a swap area ([manned](https://manned.org/swaplabel))
- `swapon` - start swapping to file/device ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/swapon.md), [manned](https://manned.org/swapon))
- `swapoff` - stop swapping to file/device ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/swapoff.md), [manned](https://manned.org/swapoff))

## Files/Directories


### Creation

- `mkdir` - make directories ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/mkdir.md), [die](https://linux.die.net/man/1/mkdir), [manned](https://manned.org/mkdir))
    - `mkdir -p` - make directory and any missing parent directories
- `ln` - make links between files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ln.md), [die](https://linux.die.net/man/1/ln), [manned](https://manned.org/ln))
  - `link` - create a link to a file/directory ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/link.md), [die](https://linux.die.net/man/1/link), [manned](https://manned.org/link))
- `fallocate` - preallocate or deallocate space to a file ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/fallocate.md), [manned](https://manned.org/fallocate))
- `mktemp` - create a temporary file or directory ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/mktemp.md), [manned](https://manned.org/mktemp))
- `mkfifo` - make FIFOs (named pipes) ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/mkfifo.md), [manned](https://manned.org/mkfifo))

### Search

- `which` - shows the full path of (shell) commands ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/which.md), [die](https://linux.die.net/man/1/which), [manned](https://manned.org/which))
- `whereis` - locate the binary, source, and manual page files for a command ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/whereis.md), [die](https://linux.die.net/man/1/whereis), [manned](https://manned.org/whereis))
- `find` - search for files in a directory hierarchy ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/find.md), [die](https://linux.die.net/man/1/find), [manned](https://manned.org/find))
- `grep` - print lines matching a pattern ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/grep.md), [die](https://linux.die.net/man/1/grep), [manned](https://manned.org/grep))
- `look` - display lines beginning with a given string ([manned](https://manned.org/look))
- `namei` - follow a pathname until a terminal point is found ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/namei.md), [manned](https://manned.org/namei))

### Move/Rename/Copy

- `mv` - move (rename) files/directories ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/mv.md), [die](https://linux.die.net/man/1/mv), [manned](https://manned.org/mv))
  - `rename` - rename multiple files at once ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/rename.md), [die](https://linux.die.net/man/1/rename), [manned](https://manned.org/rename))
- `cp` - copy files/directories ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/cp.md), [die](https://linux.die.net/man/1/cp), [manned](https://manned.org/cp))
  - `dd` - convert and copy a file ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/dd.md), [die](https://linux.die.net/man/1/dd), [manned](https://manned.org/dd))
  - `install` - copy files and set attributes ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/install.md), [manned](https://manned.org/install))
- `hardlink` - link multiple copies of a file ([manned](https://manned.org/hardlink))

### Removal/Shredding

- `rm` - remove files/directories ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/rm.md), [die](https://linux.die.net/man/1/rm), [manned](https://manned.org/rm))
  - `unlink` - call the unlink function to remove the specified file ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/unlink.md), [manned](https://manned.org/unlink))
- `rmdir` - remove empty directories ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/rmdir.md), [die](https://linux.die.net/man/1/rmdir), [manned](https://manned.org/rmdir))
- `shred` - overwrite a file to hide its contents, and optionally delete it ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/shred.md), [die](https://linux.die.net/man/1/shred), [manned](https://manned.org/shred))
- `truncate` - shrink or extend the size of a file to the specified size ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/truncate.md), [manned](https://manned.org/truncate))


### Information

- `ls` - list directory contents ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/ls.md), [die](https://linux.die.net/man/1/ls), [manned](https://manned.org/ls))
    - `dir` - list directory contents (same as `ls -Cb`)
    - `vdir` - list directory contents (same as `ls -lb`)
    - `dircolors` - set up color for `ls`
- `lsof` - list open files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/lsof.md), [die](https://linux.die.net/man/8/lsof), [manned](https://manned.org/lsof))
- `stat` - display file or file system status  ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/stat.md), [die](https://linux.die.net/man/1/stat), [manned](https://manned.org/stat))
- `basename` - strip directory and suffix from filenames ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/basename.md), [die](https://linux.die.net/man/1/basename), [manned](https://manned.org/basename))
- `dirname` - strip non-directory suffix from file name ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/dirname.md), [die](https://linux.die.net/man/1/dirname), [manned](https://manned.org/dirname))
- `pathchk` - check whether file names are valid or portable ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/pathchk.md), [manned](https://manned.org/pathchk))
- `pwd` - print name of current/working directory ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/pwd.md), [die](https://linux.die.net/man/1/pwd), [manned](https://manned.org/pwd))
- `du` - estimate file space usage ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/du.md), [die](https://linux.die.net/man/1/du), [manned](https://manned.org/du))
- `fincore` - count pages of file contents in core ([manned](https://manned.org/fincore))
- `wc` - print newline, word, and byte counts for each file ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/wc.md), [die](https://linux.die.net/man/1/wc), [manned](https://manned.org/wc))
- `file` - determine file type ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/file.md), [die](https://linux.die.net/man/1/file), [manned](https://manned.org/file))
- `test` - check file types and compare values ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/test.md), [manned](https://manned.org/test))

### Permissions/Locks/Timestamps

- `touch` - change file timestamps ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/touch.md), [die](https://linux.die.net/man/1/touch), [manned](https://manned.org/touch))
    - `touch -m` - update the modification timestamp
- `chmod` - change file mode bits ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/chmod.md), [die](https://linux.die.net/man/1/chmod), [manned](https://manned.org/chmod))
- `chown` - change file owner and group ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/chown.md), [die](https://linux.die.net/man/1/chown), [manned](https://manned.org/chown))
- `chgrp` - change group ownership ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/chgrp.md), [die](https://linux.die.net/man/1/chgrp), [manned](https://manned.org/chgrp))
- `flock` - manage locks from shell scripts ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/flock.md), [manned](https://manned.org/flock))
- `lslocks` - list local system locks ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/lslocks.md), [manned](https://manned.org/lslocks))
- `chattr` - change file attributes on a Linux file system ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/chattr.md), [die](https://linux.die.net/man/1/chattr), [manned](https://manned.org/chattr))
- `lsattr` - list file attributes on a Linux second extended file system ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/lsattr.md), [die](https://linux.die.net/man/1/lsattr), [manned](https://manned.org/lsattr))

### Viewing

- `less` - Less is a program similar to `more`, but which allows backward movement in the file as well as forward movement.  ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/less.md), [die](https://linux.die.net/man/1/less), [manned](https://manned.org/less))
    - `lesskey` specify key bindings for less  ([die](https://linux.die.net/man/1/lesskey), [manned](https://manned.org/lesskey))
- `cat` - concatenate files and print on the standard output ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/cat.md), [die](https://linux.die.net/man/1/cat), [manned](https://manned.org/cat))
    - `tac` - concatenate and print files in reverse ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/tac.md), [die](https://linux.die.net/man/1/tac), [manned](https://manned.org/tac))
- `tail` - output the last part of files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/tail.md), [die](https://linux.die.net/man/1/tail), [manned](https://manned.org/tail))
- `head` - output the first part of files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/head.md), [die](https://linux.die.net/man/1/head), [manned](https://manned.org/head))
- `xxd` - make a hexdump or do the reverse ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/xxd.md), [die](https://linux.die.net/man/1/xxd), [manned](https://manned.org/xxd))
- `hexdump` - display file contents in hexadecimal, decimal, octal, or ascii  ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/hexdump.md), [manned](https://manned.org/hexdump))
- `od` - dump files in octal and other formats ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/od.md), [manned](https://manned.org/od))

### Text Manipulation

- `rev` - reverse lines characterwise ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/rev.md), [manned](https://manned.org/rev))
- `uniq` - report or omit duplicate lines ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/uniq.md), [die](https://linux.die.net/man/1/uniq), [manned](https://manned.org/uniq))
- `tr` - translate or delete characters ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/tr.md), [die](https://linux.die.net/man/1/tr), [manned](https://manned.org/tr))
- `cut` - remove sections from each line of files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/cut.md), [die](https://linux.die.net/man/1/cut), [manned](https://manned.org/cut))
- `paste` - merge lines of files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/paste.md), [die](https://linux.die.net/man/1/paste), [manned](https://manned.org/paste))
- `sort` - sort lines of text files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/sort.md), [die](https://linux.die.net/man/1/sort), [manned](https://manned.org/sort))
    - `comm` - compare two sorted files line by line ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/comm.md), [die](https://linux.die.net/man/1/comm), [manned](https://manned.org/comm))
    - `tsort` - perform topological sort ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/tsort.md), [die](https://linux.die.net/man/1/tsort), [manned](https://manned.org/tsort))
- `shuf` - generate random permutation ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/shuf.md), [manned](https://manned.org/shuf))
- `join` - join lines of two files on a common field ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/join.md), [die](https://linux.die.net/man/1/join), [manned](https://manned.org/join))
- `fmt` - simple optimal text formatter ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/fmt.md), [die](https://linux.die.net/man/1/fmt), [manned](https://manned.org/fmt))
- `fold` - wrap each input line to fit in specified widt ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/fold.md), [die](https://linux.die.net/man/1/fold), [manned](https://manned.org/fold))
- `expand` - convert tabs to spaces ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/expand.md), [die](https://linux.die.net/man/1/expand), [manned](https://manned.org/expand))
- `unexpand` - convert spaces to tabs ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/unexpand.md), [die](https://linux.die.net/man/1/unexpand), [manned](https://manned.org/unexpand))
- `column` - columnate lists ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/column.md), [die](https://linux.die.net/man/1/column), [manned](https://manned.org/column))
    - `(printf "PERM LINKS OWNER GROUP SIZE MONTH DAY HH:MM/YEAR NAME\n" \
-l | se> ; ls -l | sed 1d) | column -t`
- `colrm` - remove columns from a file ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/colrm.md), [die](https://linux.die.net/man/1/colrm), [manned](https://manned.org/colrm))
- `nl` - number lines of files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/nl.md), [die](https://linux.die.net/man/1/nl), [manned](https://manned.org/nl))
- `split` - split a file into pieces ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/split.md), [manned](https://manned.org/split))
- `csplit` - split a file into sections determined by context lines ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/csplit.md), [die](https://linux.die.net/man/1/csplit), [manned](https://manned.org/csplit))

### Comparison

- `diff` - compare files line by line ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/diff.md), [die](https://linux.die.net/man/1/diff), [manned](https://manned.org/diff))
- `cmp` - compare files byte by byte ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/cmp.md), [die](https://linux.die.net/man/1/cmp), [manned](https://manned.org/cmp))


#### Checksums/Message Digests/Hashes

- `chksum` - checksum and count the bytes in a file ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/cksum.md), [die](https://linux.die.net/man/1/cksum), [manned](https://manned.org/cksum))
- `sha512sum` - compute and check SHA512 message digest ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/sha512sum.md), [die](https://linux.die.net/man/1/sha512sum), [manned](https://manned.org/sha512sum))
- `sha384sum` - compute and check SHA384 message digest ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/sha384sum.md), [die](https://linux.die.net/man/1/sha384sum), [manned](https://manned.org/sha384sum))
- `sha256sum` - compute and check SHA256 message digest ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/sha256sum.md), [die](https://linux.die.net/man/1/sha256sum), [manned](https://manned.org/sha256sum))
- `sha224sum` - compute and check SHA224 message digest ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/sha224sum.md), [die](https://linux.die.net/man/1/sha224sum), [manned](https://manned.org/sha224sum))
- `sha1sum` - compute and check SHA1 message digest ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/sha1sum.md), [die](https://linux.die.net/man/1/sha1sum), [manned](https://manned.org/sha1sum))  
- `b2sum` - compute and check BLAKE2 message digest ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/b2sum.md), [manned](https://manned.org/b2sum))
- `md5sum` - compute and check MD5 message digest ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/md5sum.md), [die](https://linux.die.net/man/1/md5sum), [manned](https://manned.org/md5sum))



### Encoding/Decoding

- `base32` - base32 encode/decode data and print to standard output ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/base32.md), [manned](https://manned.org/base32))
- `base64` - base64 encode/decode data and print to standard output ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/base64.md), [die](https://linux.die.net/man/1/base64), [manned](https://manned.org/base64))

### Encryption/Decryption

- `gpg` - OpenPGP encryption and signing tool ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/gpg.md), [die](https://linux.die.net/man/1/gpg), [manned](https://manned.org/gpg))

### Compression/Decompression/Backups/Archives

- `rsync` - a fast, versatile, remote (and local) file-copying tool ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/rsync.md), [die](https://linux.die.net/man/1/rsync), [manned](https://manned.org/rsync))
- `logrotate` - rotates, compresses, and mails system logs ([die](https://linux.die.net/man/8/logrotate), [manned](https://manned.org/logrotate))
- `tar` (tape archiver) - an archiving utility ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/tar.md), [die](https://linux.die.net/man/1/tar), [manned](https://manned.org/tar))
    - `tar -cf archive.tar foo bar` - create `archive.tar` with files `foo` and `bar`
    - `tar -tvf archive.tar` - list all files in `archive.tar`
    - `tar -xf` - extract all files from `archive.tar`
- `gzip` - compress files using Lempel-Ziv coding (LZ77) .gz ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/gzip.md), [die](https://linux.die.net/man/1/gzip), [manned](https://manned.org/gzip))
    - `gunzip` - expand files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/gunzip.md), [die](https://linux.die.net/man/1/gunzip), [manned](https://manned.org/gunzip))
    - `zless` - file perusal filter for crt viewing of compressed text ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/zless.md), [die](https://linux.die.net/man/1/zless), [manned](https://manned.org/zless))
    - `zgrep` - search possibly compressed files for a regular expression ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/zgrep.md), [die](https://linux.die.net/man/1/zgrep), [manned](https://manned.org/zgrep))
    - `zdiff` - compare compressed files line by line ([die](https://linux.die.net/man/1/zdiff), [manned](https://manned.org/zdiff))
    - `zcmp` - compare compressed files byte by byte ([die](https://linux.die.net/man/1/zcmp), [manned](https://manned.org/zcmp))
    - `zcat` - uncompresses either a list of files on the command line or its standard input and writes the uncompressed data on standard output. identical to `gunzip -c` ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/zcat.md), [die](https://linux.die.net/man/1/zcat), [manned](https://manned.org/zcat))
- `bzip2` - a block-sorting file compressor ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/bzip2.md), [die](https://linux.die.net/man/1/bzip2), [manned](https://manned.org/bzip2))
    - `bunzip2` - decompresses all specified files ([die](https://linux.die.net/man/1/bunzip2), [manned](https://manned.org/bunzip2))
    - `bzcat` - decompresses all specified files to the standard output ([die](https://linux.die.net/man/1/bzcat), [manned](https://manned.org/bzcat))
    - `bzless` - file perusal filter for crt viewing of bzip2 compressed text ([die](https://linux.die.net/man/1/bzless), [manned](https://manned.org/bzless))
    - `bzgrep` - search possibly bzip2 compressed files for a regular expression ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/bzgrep.md), [die](https://linux.die.net/man/1/bzgrep), [manned](https://manned.org/bzgrep))
    - `bzdiff` - compare bzip2 compressed files ([die](https://linux.die.net/man/1/bzdiff), [manned](https://manned.org/bzdiff))
- `zip` - package and compress (archive) files ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/zip.md), [die](https://linux.die.net/man/1/zip), [manned](https://manned.org/zip))
    - `unzip` - list, test and extract compressed files in a ZIP archive ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/unzip.md), [die](https://linux.die.net/man/1/unzip), [manned](https://manned.org/unzip))
    - `zipinfo` - list detailed information about a ZIP archive ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/zipinfo.md), [die](https://linux.die.net/man/1/zipinfo), [manned](https://manned.org/zipinfo))
    - `zipgrep` - search files in a ZIP archive for lines matching a pattern ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/zipgrep.md), [die](https://linux.die.net/man/1/zipgrep), [manned](https://manned.org/zipgrep))
- `cpio` - copy files to and from archives ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/cpio.md), [die](https://linux.die.net/man/1/cpio), [manned](https://manned.org/cpio))


## Special Utilities

- `bc` - an arbitrary precision calculator language ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/bc.md), [manned](https://manned.org/bc))
- `numfmt` - convert numbers from/to human-readable strings ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/numfmt.md), [manned](https://manned.org/numfmt))
- `yes` - output a string repeatedly until killed ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/yes.md), [manned](https://manned.org/yes))
- `seq` - print a sequence of numbers ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/seq.md), [die](https://linux.die.net/man/1/seq), [manned](https://manned.org/seq))
- `expr` - evaluate expressions ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/expr.md), [die](https://linux.die.net/man/1/expr), [manned](https://manned.org/expr))
- `factor` - factor numbers ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/common/factor.md), [die](https://linux.die.net/man/1/factor), [manned](https://manned.org/factor))
- `uuidgen` - create a new UUID value ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/uuidgen.md), [manned](https://manned.org/uuidgen))
- `uuidparse` - a utility to parse unique identifiers ([manned](https://manned.org/uuidparse))
- `mcookie` - generate magic cookies for xauth ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/mcookie.md), [manned](https://manned.org/mcookie))

## Bash Builtin Commands

https://www.gnu.org/software/bash/manual/html_node/Builtin-Index.html

### Special Parameters

https://www.gnu.org/software/bash/manual/html_node/Special-Parameters.html

- `$*` - Expands to the positional parameters, starting from one using `$IFS`
- `$IFS` - input field separator
- `$@` - Expands to the positional parameters, starting from one
- `$#` - Expands to the number of positional parameters in decimal
- `$?` - Expands to the exit status of the most recently executed foreground pipeline
- `$$` - Expands to the process ID of the shell
- `$!` - Expands to the process ID of the job most recently placed into the background
- `$0` - Expands to the name of the shell or shell script
- `$1`, `$2`, ... - Expands to position parameter

## Daemons

- `init` - upstart process management daemon ([die](https://linux.die.net/man/8/init))
- `inetd` - Internet service daemon ([die](https://en.wikipedia.org/wiki/Inetd))
- `atd` - run jobs queued for later execution ([die](https://linux.die.net/man/8/atd))
- `crond` - daemon to execute scheduled commands ([die](https://linux.die.net/man/8/crond))
- `useraud` - user authentication daemon ([die](https://linux.die.net/man/1/useraud))
- `fingerd` - remote user information server ([die](https://linux.die.net/man/8/fingerd))
- `ntpd` - Network Time Protocol (NTP) daemon which sets and maintains the system time of day in synchronism with Internet standard time servers ([die](https://linux.die.net/man/8/ntpd))
- `sshd` - OpenSSH SSH daemon for accepting incoming client connections ([die](https://linux.die.net/man/8/sshd))
- `httpd` - Apache Hypertext Transfer Protocol Server ([die](https://linux.die.net/man/8/httpd))
- `mountd` - NFS mount daemon ([die](https://linux.die.net/man/8/mountd))
- `git daemon` - a really simply server for git daemons ([die](https://linux.die.net/man/1/git-daemon))
- `telnetd` - DARPA telnet protocol server ([die](https://linux.die.net/man/8/telnetd))
- `ftpd` - DARPA Internet File Transfer Protocol server ([die](https://linux.die.net/man/8/ftpd))
- `uuidd` - UUID generation daemon ([tldr](https://github.com/tldr-pages/tldr/blob/main/pages/linux/uuidd.md), [manned](https://manned.org/uuidd))

A subset of the list of currently running processes without a tty will contain most currently running daemons:

```
ps -eo 'tty,pid,pgid,user,group,args,etime,pcpu' | grep ^?
```

## References

- https://manned.org/
- https://github.com/tldr-pages/tldr/
- https://www.gnu.org/software/bash/manual/
- https://linux.die.net/man/
- https://en.wikipedia.org/wiki/Util-linux
- https://en.wikipedia.org/wiki/List_of_GNU_Core_Utilities_commands

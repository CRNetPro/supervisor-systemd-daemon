### Supervisor: A Process Control System
Supervisor is a client/server system that allows its users to monitor and control a number of processes on UNIX-like operating systems.

It shares some of the same goals of programs like launchd, daemontools, and runit. Unlike some of these programs, it is not meant to be run as a substitute for init as “process id 1”. Instead it is meant to be used to control processes related to a project or a customer, and is meant to start like any other program at boot time.

systemd is controversial for several reasons: It’s a replacement for something that a lot of Linux users don’t think needs to be replaced, and the antics of the systemd developers have not won hearts and minds. But rather the opposite, as evidenced in this famous LKML thread where Linus Torvalds banned systemd dev Kay Sievers from the Linux kernel.

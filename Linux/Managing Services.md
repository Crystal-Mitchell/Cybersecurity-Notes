# Processes and Daemons

## What is a daemon?
A daemon is a background process that provides a service to the operating system or other applications.

Examples:
- mysqld
- sshd
- httpd
- nginx

## Foreground vs Background

Foreground:
- Takes control of the terminal.
- Cannot type other commands until it exits.

Background:
- Continues running while the terminal is free.

## Useful Commands

ps -aux
Lists running processes.

kill -9 PID
Terminates a process.

systemctl status
Checks service status.

journalctl
Views service logs.

## Home Lab Ideas

- Install Ubuntu Server.
- Start and stop services.
- Kill a daemon and observe the results.
- Read logs with journalctl.

## What confused me

I didn't realize mysqld would occupy the terminal because it was running in the foreground.
The lab expected me to open a second terminal before continuing.

Lesson learned:
A running foreground process blocks the terminal until it exits.
The lab expected me to open a second terminal before continuing.

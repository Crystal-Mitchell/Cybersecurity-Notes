# Linux Fundamentals - Module 1

## Date

2026-06-23

## Objective

Review Linux fundamentals, filesystem navigation, and basic file management commands.

## Key Concepts Learned

### Linux History

- UNIX was developed at Bell Labs.
- Linux was created as an open-source operating system inspired by UNIX.
- Debian is both a Linux distribution and the foundation for many other distributions.

### Filesystem Navigation

| Command | Purpose |
|----------|----------|
| pwd | Display current directory |
| cd | Change directory |
| cd .. | Move up one directory |
| cd ~ | Move to home directory |
| cd - | Return to previous directory |

### Viewing Files and Directories

| Command | Purpose |
|----------|----------|
| ls | List files |
| ls -a | Show hidden files |
| ls -al | Detailed file listing |
| ls -R | Recursive directory listing |

### File Management

| Command | Purpose |
|----------|----------|
| cat | View file contents |
| cp | Copy files |
| mv | Move or rename files |
| mkdir | Create directory |
| rm | Delete file |
| rm -r | Delete directory and contents |

## Lab Activities

- Navigated directories using cd and pwd
- Viewed hidden files using ls -a
- Examined file permissions using ls -al
- Created and manipulated files
- Practiced moving between directories

## Troubleshooting

During the lab I entered commands incorrectly while navigating and listing files.

Rather than restarting, I reviewed the output, corrected the syntax, and continued.

This reinforced the importance of carefully reading terminal output and troubleshooting mistakes methodically.

## Analyst Thinking

If I were investigating a Linux server, I would use:

- pwd to verify my location
- ls -al to review files and permissions
- cat to inspect configuration files
- history to review previously executed commands

## Real World Application

Security analysts frequently investigate Linux systems, review configuration files, analyze permissions, and examine command history during incident investigations.

## Questions For Future Study

- Where are Linux log files stored?
- How do file permissions affect security?
- How are users and groups managed?
- What Linux commands are most common in SOC environments?

## Next Steps

- Continue Linux Fundamentals Module 2
- Practice filesystem navigation
- Explore Linux permissions in more depth

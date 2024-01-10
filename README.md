# internsctl

**internsctl** is a custom Linux command designed to perform various operations on a Linux system. It supports different commands and subcommands to accomplish tasks related to CPU, memory, user management, and file information.

## Installation

Ensure that you have the necessary permissions to execute the script. You can clone the repository and make the script executable:

```git clone https://github.com/yourusername/internsctl.git```

### Usages

```internsctl [command] [subcommand] [options] [arguments]```

#### Commands

**Manual of My Command**
```man internsctl```

**Help**
``` internsctl--help```

**version**
``` internsctl --version```

**CUP**
```internsctl cpu getinfo```

**Memory**
```$ internsctl memory getinfo```

**create user**
```internsctl user create <username>```

**user list**
```internsctl user list```

**sudo permissions**
```internsctl user list --sudo-only```

**get file info**
```internsctl file getinfo <file-name>```

**get file info with options**
```internsctl file getinfo [options] <file-name>```

##### Example

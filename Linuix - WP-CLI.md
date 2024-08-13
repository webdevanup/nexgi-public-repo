# Linux Commands

## Navigating Directories

- `ls`  
  List files and directories in the current directory.  
  - `ls -l` : List with detailed information.  
  - `ls -a` : List all files including hidden files.

- `cd <directory>`  
  Change directory to `<directory>`.  
- `cd ..` : Move up one directory level.  

## File and Directory Operations

- `cp <source> <destination>`  
  Copy files or directories.  
  - `cp -r <source> <destination>` : Copy directories recursively.

- `mv <source> <destination>`  
  Move or rename files or directories.

- `rm <file>`  
  Remove (delete) files.  
  - `rm -r <directory>` : Remove directories recursively.

- `mkdir <directory>`  
  Create a new directory.

- `rmdir <directory>`  
  Remove an empty directory.

## Viewing and Editing Files

- `cat <file>`  
  Concatenate and display the contents of a file.

- `nano <file>` or `vim <file>`  
  Edit a file using the Nano or Vim text editor.

## File Permissions and Ownership

- `chmod <permissions> <file>`  
  Change file permissions.  
  - Example: `chmod 755 <file>` sets permissions to rwxr-xr-x.

- `chown <user>:<group> <file>`  
  Change file owner and group.  
  - Example: `chown user:group <file>`.

## System Information

- `top`  
  Display real-time system processes and resource usage.

- `df -h`  
  Show disk space usage.

- `du -h <directory>`  
  Show disk usage of a directory.

- `free -h`  
  Display memory usage.


## Searching and Finding Files

- `find <directory> -name <filename>`  
  Search for files by name.

- `grep <pattern> <file>`  
  Search for a pattern within a file.

---



# WP-CLI Commands


- **Display WP-CLI Environment Information**
  ```bash
  wp --info
  ```

- **Show Installed WordPress Version**
  ```bash
  wp core version
  ```

## Installation and Updates

- **Download WordPress Core Files**
  ```bash
  wp core download
  ```

- **Install WordPress**
  ```bash
  wp core install --url=<url> --title=<title> --admin_user=<username> --admin_password=<password> --admin_email=<email>
  ```

- **Update WordPress Core Files**
  ```bash
  wp core update
  ```

- **Update Database to the Latest Version**
  ```bash
  wp core update-db
  ```

## Plugin and Theme Management

- **List Installed Plugins**
  ```bash
  wp plugin list
  ```

- **Install a Plugin**
  ```bash
  wp plugin install <plugin-slug>
  ```

- **Activate a Plugin**
  ```bash
  wp plugin activate <plugin-slug>
  ```

- **Deactivate a Plugin**
  ```bash
  wp plugin deactivate <plugin-slug>
  ```

- **Delete a Plugin**
  ```bash
  wp plugin delete <plugin-slug>
  ```
  
## User Management

- **List All Users**
  ```bash
  wp user list
  ```

- **Create a New User**
  ```bash
  wp user create <username> <email> --role=<role>
  ```

- **Update a User's Password**
  ```bash
  wp user update <user-id> --user_pass=<new-password>
  ```

## Configuration and Debugging

- **Create a New `wp-config.php` File**
  ```bash
  wp config create
  ```

- **Get a Value from `wp-config.php`**
  ```bash
  wp config get <key>
  ```

- **Set a Value in `wp-config.php`**
  ```bash
  wp config set <key> <value>
  ```




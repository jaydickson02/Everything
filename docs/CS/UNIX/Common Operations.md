### 1. **File and Directory Operations**

#### Creating a Directory

- Command: `mkdir directory_name`
- Example: `mkdir my_folder` will create a directory named "my_folder."

#### Creating a File

- Command: `touch file_name`
- Example: `touch myfile.txt` will create a file named "myfile.txt."

#### Listing Files and Directories

- Command: `ls` (list), `ls -l` (detailed list), `ls -a` (include hidden files)
- Example: `ls -la` will list all files and directories, including hidden ones, with details.

### 2. **File Permissions**

#### Changing Permissions

- Command: `chmod permissions file_name`
- Example: `chmod 755 myfile.txt` will set the file permissions to 755 for "myfile.txt."

#### Changing Ownership

- Command: `chown user:group file_name`
- Example: `chown john:users myfile.txt` will change the owner to "john" and the group to "users."

### 3. **Managing Processes**

#### Viewing Active Processes

- Command: `ps`, `top`
- Example: `top` will display an ongoing view of processes in real-time.

#### Killing a Process

- Command: `kill PID` (Process ID)
- Example: `kill 1234` will terminate the process with PID 1234.

### 4. **Network Operations**

#### Displaying Network Configuration

- Command: `ifconfig` or `ip a`
- Example: `ifconfig` will display the current network configuration for all interfaces.

#### Testing Network Connectivity

- Command: `ping host_name_or_IP`
- Example: `ping google.com` will ping Google's servers to check if the network is functioning correctly.

### 5. **Package Management (using APT for Debian-based systems)**

#### Updating Package Lists

- Command: `sudo apt update`
- Example: Running this command will update the package lists to ensure the latest software can be installed.

#### Installing a Package

- Command: `sudo apt install package_name`
- Example: `sudo apt install nginx` will install the Nginx web server.

### 6. **User Management**

#### Creating a New User

- Command: `sudo useradd -m user_name`
- Example: `sudo useradd -m john` will create a new user named "john" with a home directory.

#### Changing User Password

- Command: `sudo passwd user_name`
- Example: `sudo passwd john` will prompt you to enter a new password for the user "john."
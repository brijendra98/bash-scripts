# UWaterloo CS Linux Server - Easy SSH

This script makes it easier for you to SSH into UWaterloo CS Linux Server.

## Usage
- Clone this repository
- Copy the file `uw-ssh` into your root directory.
- Modify the file to contain your Quest ID
- Run `chmod u+x ~/uw-ssh` from terminal to grant permissions.
- From your terminal, open `~/.bashrc` and add the following line to end of the file: 
```
alias uw-ssh='~/uw-ssh'
```
- Re-open terminal and run `uw-ssh --help` for usage instructions.

## More Features
If you want to avoid entering your password everytime you SSH into the server, you can set up **SSH Keys** by following [these instructions](https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys--2)

## Examples
### Using Default Username

![Example](example2.png?raw=true) 

### Providing Username

![Example](example1.png?raw=true) 

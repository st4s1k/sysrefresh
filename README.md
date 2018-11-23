# sysrefresh
One terminal command for:
1. Resynchronizing the package index files from their sources.
2. Installing the newest versions of all packages.
3. Fixing broken dependencies.
4. Clearing out the local repository of retrieved package files.
5. Removing packages that are no longer needed.
### Equivalent to:
```
sudo apt-get update &&       // Resynchronizing the package index files from their sources...
sudo apt-get dist-upgrade && // Installing the newest versions of all packages... 
sudo apt-get install -f &&   // Fixing broken dependencies...
sudo apt-get autoclean &&    // Clearing out the local repository of retrieved package files...
sudo apt-get autoremove      // Removing packages that are no longer needed...
```
# Installation
To install the script, just copy-paste and execute this command (it will prompt for root password):
```
git clone git@github.com:st4s1k/sysrefresh.git &&
cd sysrefresh/ &&
chmod +x sysrefresh_install &&
bash ./sysrefresh_install
```
# Usage
Just run the command and enter the root password:
```
sysrefresh
```
# Portable
"sysrefresh" file is a portable version, just modify the permissions and run it:
```
chmod +x sysrefresh
./sysrefresh
```

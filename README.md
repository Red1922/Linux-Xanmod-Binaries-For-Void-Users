# Linux-Xanmod-Binaries-For-Void-Users
 Here is/are the binaries for the Linux Xanmomd kernels compiled by me for convenience.

# Download Link

GitHub does not allow pushing of files bigger than 100 MiB at one instance.

Here ->  https://drive.google.com/drive/folders/1J_wfnWK8ChbAxJd8p4_wyXHiUq2vXzjF?usp=sharing

# Build Kernel from Source using Void xbps-src Template (how I built it)
 Here - > https://notabug.org/Marcoapc/voidxanmodK

# Instructions
 - Go to /path/to/void-packages/hostdir/binpkgs/ as installed from the [Official GitHub Repo](https://github.com/void-linux/void-packages)

 - Make a backup of `x86_64-repodata` 

 - Copy the 2 `.xbps` files and `x86_64-repodata` from this repo and paste it to /path/to/void-packages/hostdir/binpkgs

 - Now open your terminal in the /path/to/void-packages directory and run `sudo xbps-install --repository hostdir/binpkgs linux6.0-xanmod linux6.0-xanmod-headers`

 - Wait for the installation to finish. Voila, you now have Linux v6.0 Xanmod Kernel in your system. 

It is not guaranteed that this will work but you may try it any way if you do not want to compile the kernel.

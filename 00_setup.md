# Setting up for your Windows machine (Windows 10 or higher)

1. Following the [tutorial](https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-11-with-gui-support#1-overview) to install the Ubuntu Windows Subsystem for Linux (WSL). 

2. After installing the WSL, download the Anaconda installer by running the command below in your ubuntu terminal:

```
wget https://repo.anaconda.com/archive/Anaconda3-2023.03-Linux-x86_64.sh
```

3. After the downloading, run the following command to install it:

```
bash Anaconda3-2023.03-Linux-x86_64.sh
```

4. After installing, use the command ```exit``` to exit the terminal and reopen a new one in order to start Anaconda. In the new terminal, you will see a ```(base)``` before the command prompt. 

# Setting up for your MacOS machine

1. Open the terminal, and run the following command to download Anaconda:

* (Intel chip):

```
wget https://repo.anaconda.com/archive/Anaconda3-2023.03-MacOSX-x86_64.sh
```
* (M1 chip):

```
wget https://repo.anaconda.com/archive/Anaconda3-2023.03-MacOSX-arm64.sh
```

2. After the downloading, run the following command to install it:
* (Intel chip) ```bash Anaconda3-2023.03-Linux-x86_64.sh```
* (M1 chip) ```bash Anaconda3-2023.03-MaxOSX-arm64.sh```

3. After installing, use the command ```exit``` to exit the terminal and reopen a new one in order to start Anaconda. In the new terminal, you will see a ```(base)``` before the command prompt. 
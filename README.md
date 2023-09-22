# A backup of latest CrackMapExec release 6.0. Mad props to mpgn for this tool, it was good while it lasted :)

```sh
 ./cme
usage: cme [-h] [-t THREADS] [--timeout TIMEOUT] [--jitter INTERVAL] [--no-progress] [--verbose] [--debug] [--version] {ssh,mssql,ldap,rdp,winrm,ftp,smb,vnc} ...

      ______ .______           ___        ______  __  ___ .___  ___.      ___      .______    _______ ___   ___  _______   ______
     /      ||   _  \         /   \      /      ||  |/  / |   \/   |     /   \     |   _  \  |   ____|\  \ /  / |   ____| /      |
    |  ,----'|  |_)  |       /  ^  \    |  ,----'|  '  /  |  \  /  |    /  ^  \    |  |_)  | |  |__    \  V  /  |  |__   |  ,----'
    |  |     |      /       /  /_\  \   |  |     |    <   |  |\/|  |   /  /_\  \   |   ___/  |   __|    >   <   |   __|  |  |
    |  `----.|  |\  \----. /  _____  \  |  `----.|  .  \  |  |  |  |  /  _____  \  |  |      |  |____  /  .  \  |  |____ |  `----.
     \______|| _| `._____|/__/     \__\  \______||__|\__\ |__|  |__| /__/     \__\ | _|      |_______|/__/ \__\ |_______| \______|

                                                A swiss army knife for pentesting networks
                                    Forged by @byt3bl33d3r and @mpgn_x64 using the powah of dank memes

                                           Exclusive release for Porchetta Industries users
                                                       https://porchetta.industries/

                                                   Version : 6.0.0
                                                   Codename: Bane

options:
  -h, --help            show this help message and exit
  -t THREADS            set how many concurrent threads to use (default: 100)
  --timeout TIMEOUT     max timeout in seconds of each thread (default: None)
  --jitter INTERVAL     sets a random delay between each connection (default: None)
  --no-progress         Not displaying progress bar during scan
  --verbose             enable verbose output
  --debug               enable debug level information
  --version             Display CME version

protocols:
  available protocols

  {ssh,mssql,ldap,rdp,winrm,ftp,smb,vnc}
    ssh                 own stuff using SSH
    mssql               own stuff using MSSQL
    ldap                own stuff using LDAP
    rdp                 own stuff using RDP
    winrm               own stuff using WINRM
    ftp                 own stuff using FTP
    smb                 own stuff using SMB
    vnc                 own stuff using VNC
```

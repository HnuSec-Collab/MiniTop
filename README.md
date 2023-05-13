# MiniTop
A Bash script to obtain system status information

## installation

```bash
git clone https://github.com/KevinTong9/MiniTop && cd MiniTop
# or you can use https://github.com/HnuSec-Collab/MiniTop
chmod +x minitop && ./minitop -h
```

Output:

```
$ ./minitop -h
COMMAND NAME:minitop

 Usage: minitop [OPTION]... [INFO]

 This procedure is used to monitor system status

        -1,-c,  --cpuinfo       |       display cpuinfo
        -2,-m,  --meminfo       |       display meminfo
        -3,-l,  --loadinfo      |       display loadinfo
        -4,-f,  --fileinfo      |       display fileinfo
        -5,-d,  --modulesinfo   |       display moduleinfo
        -a,-A,  --all   |       display all message

        -h,-H,  --help  |       Display help info
        -w,     --watch |       Dynamic moniter
        -F,     --full  |       display raw message
```

auther:KT

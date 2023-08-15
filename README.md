# PrivEsc-Linux
Atacando Linux - Escalada de privilegios

#Enumeracion
Herramientas utilizadas
 ./linux-exploit-suggester -h
 ./linux-exploit-suggester.sh --checksec

 

#1 Kernel vulnerability
Linux kernel 2.x through 4.x before 4.8.3

- Explotacion:
$gcc -phread ./[c0w.c](/CVE-2016-5195_c0w.c) -o c0w

 
# Daemons
- Exim (CVE-2016-1531)

# Password mining (memory)
- FTP

# Password mining (config files)
- openvpn

# Password mining (History)

# Sudo (Shell scape sequences)

# Sudo (Abusing Intended Funcionality)

# Sudo (LD_PRELOAD)

# NFS

# Cron (Path)

# Cron (Wildcards)

# Cron (File Overwrite)

# File Permissions (SUID Binary - .so Injection)

# File Permissions (SUID Binary - Symlink)


# File Permissions (Suid Binary - Environment Variables #1)

# File Permissions (Suid Binary - Environment Variables #2)





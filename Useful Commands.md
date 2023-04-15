# NMAP Commands:
### Basic Scan that outputs all 3 formats
```
nmap <IP HERE> -A -sC -oA results
```
### Convert XML output into HTML page
```
xsltproc <nmap-output.xml> -o <nmap-output.html>
```

# Tar Commands
### Extract a TAR.GZ archive:

```
tar -xzvf archive.tar.gz
```

### Extract to a specific directory:
```
tar -xzvf archive.tar.gz -C /tmp
```
### Create an archive:
```
tar -czvf name-of-archive.tar.gz /path/to/directory-or-file
```

!!! note: Here’s what those switches actually mean:
    -c: Create an archive.
    -z: Compress the archive with gzip.
    -v: Display progress in the terminal while creating the archive, also known as “verbose” mode. The v is always optional in these commands, but it’s helpful.
    -f: Allows you to specify the filename of the archive.
    -x: Specifies to extract the file


# Misc Commands:p

### View This File:

```
grip ~/Desktop/Useful\ Commands.md
```

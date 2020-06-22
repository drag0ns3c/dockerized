# Dirsearch

A tool brute forcing directories.

[Repo](https://github.com/maurosoria/dirsearch)

## Usage

Output to Stdout.

    docker run --rm -it drag0ns3c/dirsearch -u example.com -e php

Write results to file

    docker run --rm -it -v $(pwd):/data drag0ns3c/dirsearch -u example.com -e php --plain-text-report=results

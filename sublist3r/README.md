# Sublist3r

A tool for enumerating subdomains using OSINT.

[Repo](https://github.com/aboul3la/Sublist3r)

## Usage

Output to Stdout.

    docker run --rm -it drag0ns3c/sublist3r -d example.com

Write results to file

    docker run --rm -it -v $(pwd):/data drag0ns3c/sublist3r -d example.com -t 4 -o /data/results.txt

---
tags: tool, uri, recon, brute-force
---

Gobuster is a tool used to brute-force URIs including directories and files as well as DNS subdomains.

### Usage:

```sh
gobuster -u http://example.com -w wordlist.txt dir
```
`-u` to specify url

`-w` to specify a document

`dir` at the end means that the 'wordlist.txt` can be found within the current directory.

### Resources

-[Kali](https://www.kali.org/tools/gobuster/)

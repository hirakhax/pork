# Welcome to Pork

Pork is a CLI to host multiple wordpress sites in vps without headache.

## How to install?

1. Clone this repo
2. Make pork executable: `chmod +x ./pork`
3. Install dependencies: `sudo ./pork install`

Done! 👍

## How to use?

Using `pork` is very easy.

First you should point your domain to your server ip. Then type below command to host wordpress on your domain.

```
pork wp:create <your-domain-name-here>
```

Example:

```
pork wp:create example.com
```

You are done 👍

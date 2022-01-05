# My-adblocker-hosts-file
My `/etc/hosts` file to block ads and malware at system level. No more ad-blocker extensions!!

## How to use

- Download [the hosts file](https://github.com/anubha-v-ardhan/my-adblocker-hosts-file/blob/main/etc/hosts) on this repo and paste everything in your `/etc/hosts`.
- Clean your DNS cache using the command:
```
sudo etc/init.d/dns-clean start
```
- Logout and Login once
- **NOTE: If there's something you need blocked after doing this, go to your `/etc/hosts`, search for its address and remove it. Repeat the above steps**

## Credits
- Thanks to [Steven Black](https://github.com/StevenBlack) for https://github.com/StevenBlack/hosts#list-of-all-hosts-file-variants.

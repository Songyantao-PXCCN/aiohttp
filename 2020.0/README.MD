# aiohttp for AXCF2152 (2020.0)

*If you have any question ? contact me :songyantao@phoenixcontact.com.cn*

---

1. Use root account

2. Copy all files to  `/usr/lib/python3.7/site-packages`

3.  append new line in  `/usr/lib/python3.7/site-packages/easy-install.pth` with:

   ```
   ./idna-2.9-py3.7.egg
   ./multidict-4.7.5-py3.7-linux-x86_64.egg
   ./yarl-1.4.1-py3.7-linux-x86_64.egg
   ```

   *(if `easy-install.pth` doesn't exist,creat it)*

4. you can now use `import aiohttp`
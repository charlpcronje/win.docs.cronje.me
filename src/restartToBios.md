# Restart device directly to BIOS

Every now and then you might need to get to your BIOS but because of `fast boot` or some other windows setting the time you need to press `F2` or `F1` or `del` or whatever key they decide to make it next just is not enough or it's not working.

To restart your device and let go directly to the `BIOS` use this command

- Press `win` `S`
- Type `cmd`
- Right click on the first result and click on `run as administrator`

Type the following into the command prompt window that opened and press [`enter`]

```sh
shutdown /r /fw /f /t
```




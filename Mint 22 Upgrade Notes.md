- Check display drivers after system upgrade or after entering recovery mode.
- Slower boot time expected, do not restart immediately.
- Added Nvidia modules to fix boot error.
- Reinstall lightdm to fix boot error.
- Fix Virtual Machine errors (missing dependency package & messed up Spice configuration).
- KVM suddenly doesn't work well; doesn't remember monitor rotation like it used to & takes longer to reconfigure.
- After booting offline Windows, network icon shows disabled but connection still works & update icon stuck spinning, sometimes these icons don't show up at all. Saw a different panel process than normal running during this time. Need to monitor new duplicate virbr0 network that suddenly appeared (slightly different config, noted in screenshot). Rebooting fixes it?
- QT/GTK dark themes not working; environment variable seems removed.
- Volume settings reset.
- Some packages removed.
- +2 years to EOL, newer software runs (glibc error resolved), some programs enhanced, latest Kernel compatible.  
- Came with 6.8.0-106 Kernel.
  
[How to upgrade to Linux Mint 22](https://linuxmint-user-guide.readthedocs.io/en/latest/upgrade-to-mint-22.html)  
[New Features in Linux Mint 22 'Wilma' - Linux Mint](https://www.linuxmint.com/rel_wilma_whatsnew.php)  
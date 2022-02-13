# gentoo-maintenance

Several tasks need to be done regularly.
The scripts here should reduce the effort of keeping gentoo installs up-to-date.

## kernel

Contains a script to automatically build a new kernel after emerging the sources.

Run eselect kernel set <#> manually, then call the script.

Requirements worth mentioning:
* Kernel option CONFIG_IKCONFIG enabled (for config in /proc/config.gz)
* Bootloader is GRUB
* Package app-admin/eclean-kernel is installed


ark is my archlinux package repository, it contains packages which are not in any official archlinux repository. ARK may contain duplicates from AUR, this is only the case when there are issues or bugs with the AUR package including missing rc.d scripts. When possible these packages are submitted to AUR, but in the case of duplicates they cannot be submitted.

If any packages are outdated you can tell me by submitting a issue here on github.

## pacman.conf

You can add the following to your `/etc/pacman.conf` to add the ark repository.

    [ark]
    Server = http://ark.kylefuller.co.uk/$arch/

Note: Currently the packages on ark are not availible for i686, but may be availible in the future.

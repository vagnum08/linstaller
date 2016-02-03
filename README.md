# linstaller
Bash script that helps you to install many sets of packages easily, to get your fresh install of Linux up and running.


```bash
linstaller [-h] [-d] [-b] [-g] [-a] [-t] [-p] [--conda n ] [--ros] [--opencv] [--panamax] -- install kernel and other software easily using cli


where:
    -h, --help  show this help text
    -k, --install-kernel    install the supplied kernel or downloads
        one from the repos
    --ros     download and install ROS
    --conda    install anaconda python. Use --conda 2 or --conda 3
            depending on which python version you want to install
    --copy-settings copies the dotfiles of a previous install
    -d, --deb-packages     install .deb packages from the deb folder
    -b, --basic    install basic packages for everyday use
    -t, --tex      install packages for tex authoring and texlive
    -a, --audio    install packages for audio ripping, transcoding and editing
    -g, --games    install games such as solitaire, mahjong and others
    -p, --photo    install krita and inkscape
    --opencv    install the latest opencv
    --panamax   install Panamax, Docker manager
```

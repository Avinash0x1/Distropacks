#### Contents
> - [**Info**](https://github.com/Azathothas/Distropacks/tree/main#About)
> - [📦 **`Distro-List`** 📦](https://github.com/Azathothas/Distropacks/tree/main#Distros)
> - [**Download**](https://github.com/Azathothas/Distropacks/tree/main#Download) --> [Latest-Releases](https://github.com/Azathothas/Distropacks/releases/latest)
> - [**Install**](https://github.com/Azathothas/Distropacks/tree/main#Install)
> - [**Metadata**](https://github.com/Azathothas/Distropacks/tree/main#Metadata)
---
- #### About: Automated Releases of Distro Images as easily Importable/Usable TAR Archives
> 1. Fetches compatible images, primarily for WSL2, from [multiple sources](https://github.com/Azathothas/Distropacks/blob/main/.github/workflows/fetch_weekly_distros.yaml).
> 2. Uses a [modified](https://github.com/Azathothas/Distropacks/blob/main/.github/scripts/distropack_docker_extract_distros.sh) version of [mvaisakh/wsl-distro-tars](https://github.com/mvaisakh/wsl-distro-tars) to export images directly using docker.
> 3. Archives & Releases them [weekly](https://github.com/Azathothas/Distropacks/releases) : [Latest](https://github.com/Azathothas/Distropacks/releases/latest)
---
- #### Distros
> - [**`AlmaLinux`**](https://almalinux.org/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=alma)
>```bash
>         'c:.
>        lkkkx, ..       ..   ,cc,
>        okkkk:ckkx'  .lxkkx.okkkkd
>        .:llcokkx'  :kkkxkko:xkkd,
>      .xkkkkdood:  ;kx,  .lkxlll;
>       xkkx.       xk'     xkkkkk:
>       'xkx.       xd      .....,.
>      .. :xkl'     :c      ..''..
>    .dkx'  .:ldl:'. '  ':lollldkkxo;
>  .''lkkko'                     ckkkx.
>'xkkkd:kkd.       ..  ;'        :kkxo.
>,xkkkd;kk'      ,d;    ld.   ':dkd::cc,
> .,,.;xkko'.';lxo.      dx,  :kkk'xkkkkc
>     'dkkkkkxo:.        ;kx  .kkk:;xkkd.
>       .....   .;dk:.   lkk.  :;,
>             :kkkkkkkdoxkkx 
>              ,c,,;;;:xkkd.
>                ;kkkkl...
>                ;kkkkl
>                 ,od;
>```
>```yaml
> ##almalinux: https://hub.docker.com/_/almalinux
> #https://hub.docker.com/r/amd64/almalinux/
> "amd64/almalinux:latest"
> #https://hub.docker.com/r/arm64v8/almalinux/
> "arm64v8/almalinux:latest"
>```
> ---
> - [**`Alpine`**](https://www.alpinelinux.org/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=alpine)
> ```bash
>        .hddddddddddddddddddddddh.
>       :dddddddddddddddddddddddddd:
>      /dddddddddddddddddddddddddddd/
>     +dddddddddddddddddddddddddddddd+
>   `sdddddddddddddddddddddddddddddddds`
>  `ydddddddddddd++hdddddddddddddddddddy`
> .hddddddddddd+`  `+ddddh:-sdddddddddddh.
> hdddddddddd+`      `+y:    .sddddddddddh
> ddddddddh+`   `//`   `.`     -sddddddddd
> ddddddh+`   `/hddh/`   `:s-    -sddddddd
> ddddh+`   `/+/dddddh/`   `+s-    -sddddd
> ddd+`   `/o` :dddddddh/`   `oy-    .yddd
> hdddyo+ohddyosdddddddddho+oydddy++ohdddh
> .hddddddddddddddddddddddddddddddddddddh.
>  `yddddddddddddddddddddddddddddddddddy`
>   `sdddddddddddddddddddddddddddddddds`
>     +dddddddddddddddddddddddddddddd+
>      /dddddddddddddddddddddddddddd/
>       :dddddddddddddddddddddddddd:
>        .hddddddddddddddddddddddh.
> ```
> ```yaml
> ##alpine: https://hub.docker.com/_/alpine
> #https://hub.docker.com/r/amd64/alpine/
> "amd64/alpine:latest"
> #https://hub.docker.com/r/arm64v8/alpine/
> "arm64v8/alpine:latest"
> ```
> ---
> - [**`AmazonLinux`**](https://aws.amazon.com/amazon-linux-2)
> ```bash  
>  ,     $2#_$1
>  ~\_  $2####_$1
> ~~  \_$2#####\$1
> ~~     \$2###|$1
> ~~       \$2#/$1 ___
>  ~~       V~' '->
>   ~~~         /
>     ~~._.   _/
>        _/ _/
>      _/m/'
> ```            
> ```yaml            
> ##amazonlinux: https://hub.docker.com/_/amazonlinux
> #https://hub.docker.com/r/amd64/amazonlinux/
> "amd64/amazonlinux:latest"
> #https://hub.docker.com/r/arm64v8/amazonlinux
> "arm64v8/amazonlinux:latest"
> ```                              
> ---
> - [**`Arch Linux`**](https://archlinux.org/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=arch)
> ```bash
>       /\
>      /  \
>     /    \
>    /      \
>   /   ,,   \
>  /   |  |   \
> /_-''    ''-_\
> ```
> ```yaml
> ##archlinux: https://hub.docker.com/_/archlinux
> #https://hub.docker.com/r/amd64/archlinux/
> "amd64/archlinux:latest"
> ```
> ---
> - [**`Clear Linux`**](https://www.clearlinux.org/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=clear)
> ```bash
>                ,%#(                     
>             #%%%######(                 
>           %%%&#(((#########             
>       *%%#########*****(#####%%.        
>      #%%%%%%###%%%%%(*********(#%%%,.   
>     /(#&&&&&%%%%&&&&&&@.    ,,,,,,***/#,
>     /((#&&&&%%%%&&&&&&@@#               
>     /(((#&&&%%%%&&&&&&@@@*              
>    *((((((&&&%%%%&&&&@@@@@.             
>    *(((((((%&%%%%&&&&@@@@@@             
>    /((((((((%%%%%%&&&@@@@@@@,           
>   ,((((((((((%%%%%&&@@@@@@@@&,          
>   ,#((((((((((%%%%%&@@@@@@@@@@*         
>   /###(((((((((%%%%&@@@@@@@@@@@         
>  .######((((((((#%%&@@@@@@@@@@@@        
>  .########(((((((#%%&@@@@@@@@@@@&*      
>  ###########((((((#%&@@@@@@@@@@@@#      
>  %%############((((#&@@@@@@@@@@@&       
>  %%%%############(((#&@@@@@@@@@*        
> %%%%%%%%%%%########((%@@@@@@@@/         
> %%%%%%%%%%%%%%%%%%&&&&@@@@@@@(          
> %%&&&&&&&&&&&&&&&&&&&&&@@@@@.           
> .,&&&&&&&&&&@@@@@@@@@@@@@@@.            
>        (&&&&&&&&&&&&&&&&&@.             
>              &@@@@@@@@.    
> ```
> ```yaml
> ##clearlinux: https://hub.docker.com/_/clearlinux
> #https://hub.docker.com/r/amd64/clearlinux/
> "amd64/clearlinux:latest"
> ```
> ---
> - [**`Debian`**](https://www.debian.org/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=debian)
> ```bash
>        _,met$$$$$gg.
>     ,g$$$$$$$$$$$$$$$P.
>   ,g$$P"        """Y$$.".
>  ,$$P'              `$$$.
> ',$$P       ,ggs.     `$$b:
> `d$$'     ,$P"'   .    $$$
>  $$P      d$'     ,    $$P 
>  $$:      $$.   -    ,d$$'
>  $$;      Y$b._   _,d$P'
>  Y$$.    `.`"Y$$$$P"'
>  `$$b      "-.__  
>   `Y$$
>    `Y$$.
>      `$$b.
>        `Y$$b.
>           `"Y$b._
>               `"""
> ```
> ```yaml
> ##Debian: https://hub.docker.com/_/debian
> #https://hub.docker.com/r/amd64/debian/
> "amd64/debian:latest"
> #https://hub.docker.com/r/arm64v8/debian
> "arm64v8/debian:latest"
> ```
> ---
> - [**`Fedora`**](https://fedoraproject.org/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=fedora)
> ```bash
>         ,'''''.
>        |   ,.  |
>        |  |  '_'
>   ,....|  |..
> .'  ,_;|   ..'
> |  |   |  |
> |  ',_,'  |
>  '.     ,'
>    '''''
> ```
> ```yaml
> ##Fedora: https://hub.docker.com/_/fedora
> #https://hub.docker.com/r/amd64/fedora/
> "amd64/fedora:latest"
> "amd64/fedora:rawhide"
> #https://hub.docker.com/r/arm64v8/fedora/
> "arm64v8/fedora:latest"
> "arm64v8/fedora:rawhide"
> ```
> ---
> - [**`Gentoo`**](https://www.gentoo.org/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=gentoo)
> ```bash
>  _-----_
> (       \
> \    0   \
>  $2\        )
>  /      _/
> (     _-
> \____-
> ```
> ```yaml
> ##Gentoo: https://hub.docker.com/r/gentoo/stage3
> #https://hub.docker.com/r/gentoo/stage3/tags
> "gentoo/stage3:latest"
> "gentoo/stage3:systemd"
> ```
> ---
> - [**`Kali Linux`**](https://www.kali.org/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=kali)
> ```bash
>       ,.....                                       
>   ----`     `..,;:ccc,.                             
>            ......''';lxO.                           
>  .....''''..........,:ld;                          
>             .';;;:::;,,.x,                          
>        ..'''.            0Xxoc:,.  ...              
>    ....                ,ONkc;,;cokOdc',.            
>   .                   OMo           ':do.           
>                      dMc               :OO;         
>                      0M.                 .:o.       
>                      ;Wd                            
>                       ;XO,                          
>                         ,d0Odlc;,..                 
>                             ..',;:cdOOd::,.         
>                                      .:d;.':;.      
>                                         'd,  .'     
>                                           ;l   ..   
>                                            .o       
>                                              c      
>                                              .'     
>                                               . 
> ```
> ```yaml
> ##Kali: https://hub.docker.com/r/kalilinux/kali-rolling
> #https://hub.docker.com/r/kalilinux/kali-rolling/tags
> "kalilinux/kali-rolling:amd64"
> "kalilinux/kali-rolling:arm64"
> ```
> ---
> - [**`OpenSuSe`**](https://www.opensuse.org/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=opensuse)
> ```bash
>            .;ldkO0000Okdl;.             
>        .;d00xl:^''''''^:ok00d;.          
>      .d00l'                'o00d.        
>    .d0Kd'  Okxol:;,.          :O0d.      
>   .OKKKK0kOKKKKKKKKKKOxo:,      lKO.     
>  ,0KKKKKKKKKKKKKKKK0P^,,,^dx:    ;00,    
> .OKKKKKKKKKKKKKKKKk'.oOPPb.'0k.   cKO.   
> :KKKKKKKKKKKKKKKKK: kKx..dd lKd   'OK:   
> dKKKKKKKKKKKOx0KKKd ^0KKKO' kKKc   dKd   
> dKKKKKKKKKKKK;.;oOKx,..^..;kKKK0.  dKd
> :KKKKKKKKKKKK0o;...^cdxxOK0O/^^'  .0K:
>  kKKKKKKKKKKKKKKK0x;,,......,;od  lKk
>  '0KKKKKKKKKKKKKKKKKKKKK00KKOo^  c00'
>   'kKKKOxddxkOO00000Okxoc;''   .dKk'
>     l0Ko.                    .c00l'
>      'l0Kk:.              .;xK0l'
>         'lkK0xl:;,,,,;:ldO0kl'
>             '^:ldxkkkkxdl:^'
> 
> ```
> ```yaml
> ##OpenSuse: https://hub.docker.com/_/opensuse
> #https://hub.docker.com/r/opensuse/leap
> "opensuse/leap"
> #https://hub.docker.com/r/opensuse/tumbleweed
> "opensuse/tumbleweed"
> ```
> ---
> - [**`Oracle Linux`**](https://www.oracle.com/linux/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=oracle)
> ```bash
>       `-/+++++++++++++++++/-.`
>    `/syyyyyyyyyyyyyyyyyyyyyyys/.
>   :yyyyo/-...............-/oyyyy/
>  /yyys-                     .oyyy+
> .yyyy`                       `syyy-
> :yyyo                         /yyy/
> .yyyy`                       `syyy-
>  /yyys.                     .oyyyo
>   /yyyyo:-...............-:oyyyy/`
>    `/syyyyyyyyyyyyyyyyyyyyyyys+.
>      `.:/+ooooooooooooooo+/:.`
> 
> ```
> ```yaml
> ##oraclelinux: https://hub.docker.com/_/oraclelinux
> #https://hub.docker.com/r/amd64/oraclelinux/
> "amd64/oraclelinux:9"
> "amd64/oraclelinux:9-slim"
> #https://hub.docker.com/r/arm64v8/oraclelinux
> "arm64v8/oraclelinux:9"
> "arm64v8/oraclelinux:9-slim"
> ```
> ---
> - [**`Rocky Linux`**](https://rockylinux.org/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=rocky)
> ```bash
>        `-/+++++++++/-.`
>     `-+++++++++++++++++-`
>    .+++++++++++++++++++++.
>    -+++++++++++++++++++++++.
>    +++++++++++++++/-/+++++++
>    +++++++++++++/.   ./+++++
>    +++++++++++:.       ./+++
>    +++++++++:`   `:/:`   .:/
>    -++++++:`   .:+++++:`
>     .+++-`   ./+++++++++:`
>      `-`   ./+++++++++++-
>           -+++++++++:-.`
> 
> ```
> ```yaml
> ##rockylinux: https://hub.docker.com/_/rockylinux
> #https://hub.docker.com/r/amd64/rockylinux/
> "amd64/rockylinux:9"
> "amd64/rockylinux:9-minimal"
> #https://hub.docker.com/r/arm64v8/rockylinux/
> "arm64v8/rockylinux:9"
> "arm64v8/rockylinux:9-minimal"
> ```
> ---
> - [**`Ubuntu`**](https://ubuntu.com/) --> [Distrowatch](https://distrowatch.com/table.php?distribution=ubuntu)
> ```bash
>          _
>      ---(_)
>  _/  ---  \
> (_) |   |
>   \  --- _/
>      ---(_)
> 
> ```
> ```yaml
> ##Ubuntu: https://hub.docker.com/_/ubuntu
> #https://hub.docker.com/r/amd64/ubuntu/
> "amd64/ubuntu:latest" #latest = 22.04
> #https://hub.docker.com/r/arm64v8/ubuntu
> "arm64v8/ubuntu:latest" #latest = 22.04
> ```
> ---
---
- #### Download
```bash
!# Single Distro
--> Grab from Releases: https://github.com/Azathothas/Distropacks/releases/latest
#Using wget + curl
# Example: alpine_latest (Replace with yours)
wget "$(curl -qfsSL "https://api.github.com/repos/Azathothas/Distropacks/releases/latest" | jq -r '.assets[] | .browser_download_url' | grep -i 'alpine_latest')"
```
---
- #### Install
> - [WSL2](https://github.com/Azathothas/Arsenal/tree/main/misc/WSL#custom) --> https://github.com/Azathothas/Arsenal/tree/main/misc/WSL#custom
> - [wsl-distro-tars](https://github.com/mvaisakh/wsl-distro-tars#how-do-i-import-tarballs) --> https://github.com/mvaisakh/wsl-distro-tars#how-do-i-import-tarballs
---

---

- #### Metadata
```mathematica

----------------------------------------------------------
[+] amd64/almalinux:latest
e5cdbae6744c
NAME="AlmaLinux"
VERSION="9.3 (Shamrock Pampas Cat)"
ID="almalinux"
ID_LIKE="rhel centos fedora"
VERSION_ID="9.3"
PLATFORM_ID="platform:el9"
PRETTY_NAME="AlmaLinux 9.3 (Shamrock Pampas Cat)"
ANSI_COLOR="0;34"
LOGO="fedora-logo-icon"
CPE_NAME="cpe:/o:almalinux:almalinux:9::baseos"
HOME_URL="https://almalinux.org/"
DOCUMENTATION_URL="https://wiki.almalinux.org/"
BUG_REPORT_URL="https://bugs.almalinux.org/"

ALMALINUX_MANTISBT_PROJECT="AlmaLinux-9"
ALMALINUX_MANTISBT_PROJECT_VERSION="9.3"
REDHAT_SUPPORT_PRODUCT="AlmaLinux"
REDHAT_SUPPORT_PRODUCT_VERSION="9.3"
Linux e5cdbae6744c 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
[✓] File: amd64_almalinux_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] arm64v8/almalinux:latest
3ab3e6ef253a
NAME="AlmaLinux"
VERSION="9.3 (Shamrock Pampas Cat)"
ID="almalinux"
ID_LIKE="rhel centos fedora"
VERSION_ID="9.3"
PLATFORM_ID="platform:el9"
PRETTY_NAME="AlmaLinux 9.3 (Shamrock Pampas Cat)"
ANSI_COLOR="0;34"
LOGO="fedora-logo-icon"
CPE_NAME="cpe:/o:almalinux:almalinux:9::baseos"
HOME_URL="https://almalinux.org/"
DOCUMENTATION_URL="https://wiki.almalinux.org/"
BUG_REPORT_URL="https://bugs.almalinux.org/"

ALMALINUX_MANTISBT_PROJECT="AlmaLinux-9"
ALMALINUX_MANTISBT_PROJECT_VERSION="9.3"
REDHAT_SUPPORT_PRODUCT="AlmaLinux"
REDHAT_SUPPORT_PRODUCT_VERSION="9.3"
Linux 3ab3e6ef253a 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 aarch64 aarch64 GNU/Linux
[✓] File: arm64v8_almalinux_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/alpine:latest
9e253d8d8149
NAME="Alpine Linux"
ID=alpine
VERSION_ID=3.19.0
PRETTY_NAME="Alpine Linux v3.19"
HOME_URL="https://alpinelinux.org/"
BUG_REPORT_URL="https://gitlab.alpinelinux.org/alpine/aports/-/issues"
Linux 9e253d8d8149 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 Linux
[✓] File: amd64_alpine_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] arm64v8/alpine:latest
09c313669d82
NAME="Alpine Linux"
ID=alpine
VERSION_ID=3.19.0
PRETTY_NAME="Alpine Linux v3.19"
HOME_URL="https://alpinelinux.org/"
BUG_REPORT_URL="https://gitlab.alpinelinux.org/alpine/aports/-/issues"
Linux 09c313669d82 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 Linux
[✓] File: arm64v8_alpine_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/amazonlinux:latest
NAME="Amazon Linux"
VERSION="2023"
ID="amzn"
ID_LIKE="fedora"
VERSION_ID="2023"
PLATFORM_ID="platform:al2023"
PRETTY_NAME="Amazon Linux 2023"
ANSI_COLOR="0;33"
CPE_NAME="cpe:2.3:o:amazon:amazon_linux:2023"
HOME_URL="https://aws.amazon.com/linux/"
BUG_REPORT_URL="https://github.com/amazonlinux/amazon-linux-2023"
SUPPORT_END="2028-03-15"
Linux 989e6e52fc02 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
[✓] File: amd64_amazonlinux_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] arm64v8/amazonlinux:latest
NAME="Amazon Linux"
VERSION="2023"
ID="amzn"
ID_LIKE="fedora"
VERSION_ID="2023"
PLATFORM_ID="platform:al2023"
PRETTY_NAME="Amazon Linux 2023"
ANSI_COLOR="0;33"
CPE_NAME="cpe:2.3:o:amazon:amazon_linux:2023"
HOME_URL="https://aws.amazon.com/linux/"
BUG_REPORT_URL="https://github.com/amazonlinux/amazon-linux-2023"
SUPPORT_END="2028-03-15"
Linux 61bec62d470e 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 aarch64 aarch64 GNU/Linux
[✓] File: arm64v8_amazonlinux_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/archlinux:latest
NAME="Arch Linux"
PRETTY_NAME="Arch Linux"
ID=arch
BUILD_ID=rolling
VERSION_ID=20240101.0.204074
ANSI_COLOR="38;2;23;147;209"
HOME_URL="https://archlinux.org/"
DOCUMENTATION_URL="https://wiki.archlinux.org/"
SUPPORT_URL="https://bbs.archlinux.org/"
BUG_REPORT_URL="https://bugs.archlinux.org/"
PRIVACY_POLICY_URL="https://terms.archlinux.org/docs/privacy-policy/"
LOGO=archlinux-logo
Linux 75254e011a6a 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 GNU/Linux
[✓] File: amd64_archlinux_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/clearlinux:latest
bb228843481f
NAME="Clear Linux OS"
VERSION=1
ID=clear-linux-os
ID_LIKE=clear-linux-os
VERSION_ID=40690
PRETTY_NAME="Clear Linux OS"
ANSI_COLOR="1;35"
HOME_URL="https://clearlinux.org"
SUPPORT_URL="https://clearlinux.org"
BUG_REPORT_URL="mailto:dev@lists.clearlinux.org"
PRIVACY_POLICY_URL="http://www.intel.com/privacy"
BUILD_ID=40690
Linux bb228843481f 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 GNU/Linux
[✓] File: amd64_clearlinux_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/debian:latest
05ae35cb0b56
PRETTY_NAME="Debian GNU/Linux 12 (bookworm)"
NAME="Debian GNU/Linux"
VERSION_ID="12"
VERSION="12 (bookworm)"
VERSION_CODENAME=bookworm
ID=debian
HOME_URL="https://www.debian.org/"
SUPPORT_URL="https://www.debian.org/support"
BUG_REPORT_URL="https://bugs.debian.org/"
Linux 05ae35cb0b56 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 GNU/Linux
[✓] File: amd64_debian_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] arm64v8/debian:latest
501e571cd785
PRETTY_NAME="Debian GNU/Linux 12 (bookworm)"
NAME="Debian GNU/Linux"
VERSION_ID="12"
VERSION="12 (bookworm)"
VERSION_CODENAME=bookworm
ID=debian
HOME_URL="https://www.debian.org/"
SUPPORT_URL="https://www.debian.org/support"
BUG_REPORT_URL="https://bugs.debian.org/"
Linux 501e571cd785 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 GNU/Linux
[✓] File: arm64v8_debian_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/fedora:latest
NAME="Fedora Linux"
VERSION="39 (Container Image)"
ID=fedora
VERSION_ID=39
VERSION_CODENAME=""
PLATFORM_ID="platform:f39"
PRETTY_NAME="Fedora Linux 39 (Container Image)"
ANSI_COLOR="0;38;2;60;110;180"
LOGO=fedora-logo-icon
CPE_NAME="cpe:/o:fedoraproject:fedora:39"
DEFAULT_HOSTNAME="fedora"
HOME_URL="https://fedoraproject.org/"
DOCUMENTATION_URL="https://docs.fedoraproject.org/en-US/fedora/f39/system-administrators-guide/"
SUPPORT_URL="https://ask.fedoraproject.org/"
BUG_REPORT_URL="https://bugzilla.redhat.com/"
REDHAT_BUGZILLA_PRODUCT="Fedora"
REDHAT_BUGZILLA_PRODUCT_VERSION=39
REDHAT_SUPPORT_PRODUCT="Fedora"
REDHAT_SUPPORT_PRODUCT_VERSION=39
SUPPORT_END=2024-05-14
VARIANT="Container Image"
VARIANT_ID=container
Linux e6c13e415292 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 GNU/Linux
[✓] File: amd64_fedora_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/fedora:rawhide
NAME="Fedora Linux"
VERSION="40 (Container Image Prerelease)"
ID=fedora
VERSION_ID=40
VERSION_CODENAME=""
PLATFORM_ID="platform:f40"
PRETTY_NAME="Fedora Linux 40 (Container Image Prerelease)"
ANSI_COLOR="0;38;2;60;110;180"
LOGO=fedora-logo-icon
CPE_NAME="cpe:/o:fedoraproject:fedora:40"
DEFAULT_HOSTNAME="fedora"
HOME_URL="https://fedoraproject.org/"
DOCUMENTATION_URL="https://docs.fedoraproject.org/en-US/fedora/rawhide/system-administrators-guide/"
SUPPORT_URL="https://ask.fedoraproject.org/"
BUG_REPORT_URL="https://bugzilla.redhat.com/"
REDHAT_BUGZILLA_PRODUCT="Fedora"
REDHAT_BUGZILLA_PRODUCT_VERSION=rawhide
REDHAT_SUPPORT_PRODUCT="Fedora"
REDHAT_SUPPORT_PRODUCT_VERSION=rawhide
SUPPORT_END=2025-05-13
VARIANT="Container Image"
VARIANT_ID=container
Linux 2bcf86426a8f 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 GNU/Linux
[✓] File: amd64_fedora_rawhide-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] arm64v8/fedora:latest
NAME="Fedora Linux"
VERSION="39 (Container Image)"
ID=fedora
VERSION_ID=39
VERSION_CODENAME=""
PLATFORM_ID="platform:f39"
PRETTY_NAME="Fedora Linux 39 (Container Image)"
ANSI_COLOR="0;38;2;60;110;180"
LOGO=fedora-logo-icon
CPE_NAME="cpe:/o:fedoraproject:fedora:39"
DEFAULT_HOSTNAME="fedora"
HOME_URL="https://fedoraproject.org/"
DOCUMENTATION_URL="https://docs.fedoraproject.org/en-US/fedora/f39/system-administrators-guide/"
SUPPORT_URL="https://ask.fedoraproject.org/"
BUG_REPORT_URL="https://bugzilla.redhat.com/"
REDHAT_BUGZILLA_PRODUCT="Fedora"
REDHAT_BUGZILLA_PRODUCT_VERSION=39
REDHAT_SUPPORT_PRODUCT="Fedora"
REDHAT_SUPPORT_PRODUCT_VERSION=39
SUPPORT_END=2024-05-14
VARIANT="Container Image"
VARIANT_ID=container
Linux eb56f3216e68 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 GNU/Linux
[✓] File: arm64v8_fedora_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] arm64v8/fedora:rawhide
NAME="Fedora Linux"
VERSION="40 (Container Image Prerelease)"
ID=fedora
VERSION_ID=40
VERSION_CODENAME=""
PLATFORM_ID="platform:f40"
PRETTY_NAME="Fedora Linux 40 (Container Image Prerelease)"
ANSI_COLOR="0;38;2;60;110;180"
LOGO=fedora-logo-icon
CPE_NAME="cpe:/o:fedoraproject:fedora:40"
DEFAULT_HOSTNAME="fedora"
HOME_URL="https://fedoraproject.org/"
DOCUMENTATION_URL="https://docs.fedoraproject.org/en-US/fedora/rawhide/system-administrators-guide/"
SUPPORT_URL="https://ask.fedoraproject.org/"
BUG_REPORT_URL="https://bugzilla.redhat.com/"
REDHAT_BUGZILLA_PRODUCT="Fedora"
REDHAT_BUGZILLA_PRODUCT_VERSION=rawhide
REDHAT_SUPPORT_PRODUCT="Fedora"
REDHAT_SUPPORT_PRODUCT_VERSION=rawhide
SUPPORT_END=2025-05-13
VARIANT="Container Image"
VARIANT_ID=container
Linux 30964949c462 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 GNU/Linux
[✓] File: arm64v8_fedora_rawhide-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] gentoo/stage3:latest
0b31d08b94c6
NAME=Gentoo
ID=gentoo
PRETTY_NAME="Gentoo Linux"
ANSI_COLOR="1;32"
HOME_URL="https://www.gentoo.org/"
SUPPORT_URL="https://www.gentoo.org/support/"
BUG_REPORT_URL="https://bugs.gentoo.org/"
VERSION_ID="2.14"
Linux 0b31d08b94c6 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 AMD EPYC 7763 64-Core Processor AuthenticAMD GNU/Linux
[✓] File: gentoo_stage3_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] gentoo/stage3:systemd
d656e1b6ffc4
NAME=Gentoo
ID=gentoo
PRETTY_NAME="Gentoo Linux"
ANSI_COLOR="1;32"
HOME_URL="https://www.gentoo.org/"
SUPPORT_URL="https://www.gentoo.org/support/"
BUG_REPORT_URL="https://bugs.gentoo.org/"
VERSION_ID="2.14"
Linux d656e1b6ffc4 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 AMD EPYC 7763 64-Core Processor AuthenticAMD GNU/Linux
[✓] File: gentoo_stage3_systemd-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] kalilinux/kali-rolling:amd64
d01407234838
PRETTY_NAME="Kali GNU/Linux Rolling"
NAME="Kali GNU/Linux"
VERSION_ID="2023.4"
VERSION="2023.4"
VERSION_CODENAME=kali-rolling
ID=kali
ID_LIKE=debian
HOME_URL="https://www.kali.org/"
SUPPORT_URL="https://forums.kali.org/"
BUG_REPORT_URL="https://bugs.kali.org/"
ANSI_COLOR="1;31"
Linux d01407234838 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 GNU/Linux
[✓] File: kalilinux_kali_rolling_amd64-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] kalilinux/kali-rolling:arm64
905c3816e315
PRETTY_NAME="Kali GNU/Linux Rolling"
NAME="Kali GNU/Linux"
VERSION_ID="2023.4"
VERSION="2023.4"
VERSION_CODENAME=kali-rolling
ID=kali
ID_LIKE=debian
HOME_URL="https://www.kali.org/"
SUPPORT_URL="https://forums.kali.org/"
BUG_REPORT_URL="https://bugs.kali.org/"
ANSI_COLOR="1;31"
Linux 905c3816e315 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 GNU/Linux
[✓] File: kalilinux_kali_rolling_arm64-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] opensuse/leap
NAME="openSUSE Leap"
VERSION="15.5"
ID="opensuse-leap"
ID_LIKE="suse opensuse"
VERSION_ID="15.5"
PRETTY_NAME="openSUSE Leap 15.5"
ANSI_COLOR="0;32"
CPE_NAME="cpe:/o:opensuse:leap:15.5"
BUG_REPORT_URL="https://bugs.opensuse.org"
HOME_URL="https://www.opensuse.org/"
DOCUMENTATION_URL="https://en.opensuse.org/Portal:Leap"
LOGO="distributor-logo-Leap"
Linux b58e2721eb9e 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
[✓] File: opensuse_leap-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] opensuse/tumbleweed
NAME="openSUSE Tumbleweed"
# VERSION="20240123"
ID="opensuse-tumbleweed"
ID_LIKE="opensuse suse"
VERSION_ID="20240123"
PRETTY_NAME="openSUSE Tumbleweed"
ANSI_COLOR="0;32"
CPE_NAME="cpe:/o:opensuse:tumbleweed:20240123"
BUG_REPORT_URL="https://bugzilla.opensuse.org"
SUPPORT_URL="https://bugs.opensuse.org"
HOME_URL="https://www.opensuse.org"
DOCUMENTATION_URL="https://en.opensuse.org/Portal:Tumbleweed"
LOGO="distributor-logo-Tumbleweed"
Linux 5d681edd094b 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
[✓] File: opensuse_tumbleweed-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/oraclelinux:9
NAME="Oracle Linux Server"
VERSION="9.3"
ID="ol"
ID_LIKE="fedora"
VARIANT="Server"
VARIANT_ID="server"
VERSION_ID="9.3"
PLATFORM_ID="platform:el9"
PRETTY_NAME="Oracle Linux Server 9.3"
ANSI_COLOR="0;31"
CPE_NAME="cpe:/o:oracle:linux:9:3:server"
HOME_URL="https://linux.oracle.com/"
BUG_REPORT_URL="https://github.com/oracle/oracle-linux"

ORACLE_BUGZILLA_PRODUCT="Oracle Linux 9"
ORACLE_BUGZILLA_PRODUCT_VERSION=9.3
ORACLE_SUPPORT_PRODUCT="Oracle Linux"
ORACLE_SUPPORT_PRODUCT_VERSION=9.3
Linux 572ceecd1365 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
[✓] File: amd64_oraclelinux_9-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/oraclelinux:9-slim
NAME="Oracle Linux Server"
VERSION="9.3"
ID="ol"
ID_LIKE="fedora"
VARIANT="Server"
VARIANT_ID="server"
VERSION_ID="9.3"
PLATFORM_ID="platform:el9"
PRETTY_NAME="Oracle Linux Server 9.3"
ANSI_COLOR="0;31"
CPE_NAME="cpe:/o:oracle:linux:9:3:server"
HOME_URL="https://linux.oracle.com/"
BUG_REPORT_URL="https://github.com/oracle/oracle-linux"

ORACLE_BUGZILLA_PRODUCT="Oracle Linux 9"
ORACLE_BUGZILLA_PRODUCT_VERSION=9.3
ORACLE_SUPPORT_PRODUCT="Oracle Linux"
ORACLE_SUPPORT_PRODUCT_VERSION=9.3
Linux ef12f1b4335a 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
[✓] File: amd64_oraclelinux_9_slim-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] arm64v8/oraclelinux:9
NAME="Oracle Linux Server"
VERSION="9.3"
ID="ol"
ID_LIKE="fedora"
VARIANT="Server"
VARIANT_ID="server"
VERSION_ID="9.3"
PLATFORM_ID="platform:el9"
PRETTY_NAME="Oracle Linux Server 9.3"
ANSI_COLOR="0;31"
CPE_NAME="cpe:/o:oracle:linux:9:3:server"
HOME_URL="https://linux.oracle.com/"
BUG_REPORT_URL="https://github.com/oracle/oracle-linux"

ORACLE_BUGZILLA_PRODUCT="Oracle Linux 9"
ORACLE_BUGZILLA_PRODUCT_VERSION=9.3
ORACLE_SUPPORT_PRODUCT="Oracle Linux"
ORACLE_SUPPORT_PRODUCT_VERSION=9.3
Linux d50e3cac5664 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 aarch64 aarch64 GNU/Linux
[✓] File: arm64v8_oraclelinux_9-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] arm64v8/oraclelinux:9-slim
NAME="Oracle Linux Server"
VERSION="9.3"
ID="ol"
ID_LIKE="fedora"
VARIANT="Server"
VARIANT_ID="server"
VERSION_ID="9.3"
PLATFORM_ID="platform:el9"
PRETTY_NAME="Oracle Linux Server 9.3"
ANSI_COLOR="0;31"
CPE_NAME="cpe:/o:oracle:linux:9:3:server"
HOME_URL="https://linux.oracle.com/"
BUG_REPORT_URL="https://github.com/oracle/oracle-linux"

ORACLE_BUGZILLA_PRODUCT="Oracle Linux 9"
ORACLE_BUGZILLA_PRODUCT_VERSION=9.3
ORACLE_SUPPORT_PRODUCT="Oracle Linux"
ORACLE_SUPPORT_PRODUCT_VERSION=9.3
Linux f6c975fc0fc1 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 aarch64 aarch64 GNU/Linux
[✓] File: arm64v8_oraclelinux_9_slim-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/rockylinux:9
6ce3c1011a2d
NAME="Rocky Linux"
VERSION="9.3 (Blue Onyx)"
ID="rocky"
ID_LIKE="rhel centos fedora"
VERSION_ID="9.3"
PLATFORM_ID="platform:el9"
PRETTY_NAME="Rocky Linux 9.3 (Blue Onyx)"
ANSI_COLOR="0;32"
LOGO="fedora-logo-icon"
CPE_NAME="cpe:/o:rocky:rocky:9::baseos"
HOME_URL="https://rockylinux.org/"
BUG_REPORT_URL="https://bugs.rockylinux.org/"
SUPPORT_END="2032-05-31"
ROCKY_SUPPORT_PRODUCT="Rocky-Linux-9"
ROCKY_SUPPORT_PRODUCT_VERSION="9.3"
REDHAT_SUPPORT_PRODUCT="Rocky Linux"
REDHAT_SUPPORT_PRODUCT_VERSION="9.3"
Linux 6ce3c1011a2d 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
[✓] File: amd64_rockylinux_9-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/rockylinux:9-minimal
NAME="Rocky Linux"
VERSION="9.3 (Blue Onyx)"
ID="rocky"
ID_LIKE="rhel centos fedora"
VERSION_ID="9.3"
PLATFORM_ID="platform:el9"
PRETTY_NAME="Rocky Linux 9.3 (Blue Onyx)"
ANSI_COLOR="0;32"
LOGO="fedora-logo-icon"
CPE_NAME="cpe:/o:rocky:rocky:9::baseos"
HOME_URL="https://rockylinux.org/"
BUG_REPORT_URL="https://bugs.rockylinux.org/"
SUPPORT_END="2032-05-31"
ROCKY_SUPPORT_PRODUCT="Rocky-Linux-9"
ROCKY_SUPPORT_PRODUCT_VERSION="9.3"
REDHAT_SUPPORT_PRODUCT="Rocky Linux"
REDHAT_SUPPORT_PRODUCT_VERSION="9.3"
Linux dc255d6d1a70 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
[✓] File: amd64_rockylinux_9_minimal-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] arm64v8/rockylinux:9
6230b92771e7
NAME="Rocky Linux"
VERSION="9.3 (Blue Onyx)"
ID="rocky"
ID_LIKE="rhel centos fedora"
VERSION_ID="9.3"
PLATFORM_ID="platform:el9"
PRETTY_NAME="Rocky Linux 9.3 (Blue Onyx)"
ANSI_COLOR="0;32"
LOGO="fedora-logo-icon"
CPE_NAME="cpe:/o:rocky:rocky:9::baseos"
HOME_URL="https://rockylinux.org/"
BUG_REPORT_URL="https://bugs.rockylinux.org/"
SUPPORT_END="2032-05-31"
ROCKY_SUPPORT_PRODUCT="Rocky-Linux-9"
ROCKY_SUPPORT_PRODUCT_VERSION="9.3"
REDHAT_SUPPORT_PRODUCT="Rocky Linux"
REDHAT_SUPPORT_PRODUCT_VERSION="9.3"
Linux 6230b92771e7 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 aarch64 aarch64 GNU/Linux
[✓] File: arm64v8_rockylinux_9-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] arm64v8/rockylinux:9-minimal
NAME="Rocky Linux"
VERSION="9.3 (Blue Onyx)"
ID="rocky"
ID_LIKE="rhel centos fedora"
VERSION_ID="9.3"
PLATFORM_ID="platform:el9"
PRETTY_NAME="Rocky Linux 9.3 (Blue Onyx)"
ANSI_COLOR="0;32"
LOGO="fedora-logo-icon"
CPE_NAME="cpe:/o:rocky:rocky:9::baseos"
HOME_URL="https://rockylinux.org/"
BUG_REPORT_URL="https://bugs.rockylinux.org/"
SUPPORT_END="2032-05-31"
ROCKY_SUPPORT_PRODUCT="Rocky-Linux-9"
ROCKY_SUPPORT_PRODUCT_VERSION="9.3"
REDHAT_SUPPORT_PRODUCT="Rocky Linux"
REDHAT_SUPPORT_PRODUCT_VERSION="9.3"
Linux 2e89bb8ef6ea 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 aarch64 aarch64 GNU/Linux
[✓] File: arm64v8_rockylinux_9_minimal-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] amd64/ubuntu:latest
7889f61f6a19
PRETTY_NAME="Ubuntu 22.04.3 LTS"
NAME="Ubuntu"
VERSION_ID="22.04"
VERSION="22.04.3 LTS (Jammy Jellyfish)"
VERSION_CODENAME=jammy
ID=ubuntu
ID_LIKE=debian
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
UBUNTU_CODENAME=jammy
Linux 7889f61f6a19 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
[✓] File: amd64_ubuntu_latest-docker_exported.tar
----------------------------------------------------------


----------------------------------------------------------
[+] arm64v8/ubuntu:latest
99b9b6b89d91
PRETTY_NAME="Ubuntu 22.04.3 LTS"
NAME="Ubuntu"
VERSION_ID="22.04"
VERSION="22.04.3 LTS (Jammy Jellyfish)"
VERSION_CODENAME=jammy
ID=ubuntu
ID_LIKE=debian
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
UBUNTU_CODENAME=jammy
Linux 99b9b6b89d91 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 aarch64 aarch64 aarch64 GNU/Linux
[✓] File: arm64v8_ubuntu_latest-docker_exported.tar
----------------------------------------------------------


[+] Sizes
amd64_almalinux_latest-docker_exported.tar --> 181M
amd64_alpine_latest-docker_exported.tar --> 7.4M
amd64_amazonlinux_latest-docker_exported.tar --> 143M
amd64_archlinux_latest-docker_exported.tar --> 426M
amd64_clearlinux_latest-docker_exported.tar --> 176M
amd64_debian_latest-docker_exported.tar --> 116M
amd64_fedora_latest-docker_exported.tar --> 175M
amd64_fedora_rawhide-docker_exported.tar --> 174M
amd64_oraclelinux_9-docker_exported.tar --> 231M
amd64_oraclelinux_9_slim-docker_exported.tar --> 109M
amd64_rockylinux_9-docker_exported.tar --> 173M
amd64_rockylinux_9_minimal-docker_exported.tar --> 116M
amd64_ubuntu_latest-docker_exported.tar --> 77M
arm64v8_almalinux_latest-docker_exported.tar --> 199M
arm64v8_alpine_latest-docker_exported.tar --> 7.7M
arm64v8_amazonlinux_latest-docker_exported.tar --> 176M
arm64v8_debian_latest-docker_exported.tar --> 137M
arm64v8_fedora_latest-docker_exported.tar --> 253M
arm64v8_fedora_rawhide-docker_exported.tar --> 252M
arm64v8_oraclelinux_9-docker_exported.tar --> 254M
arm64v8_oraclelinux_9_slim-docker_exported.tar --> 113M
arm64v8_rockylinux_9-docker_exported.tar --> 190M
arm64v8_rockylinux_9_minimal-docker_exported.tar --> 127M
arm64v8_ubuntu_latest-docker_exported.tar --> 69M
gentoo_stage3_latest-docker_exported.tar --> 1.3G
gentoo_stage3_systemd-docker_exported.tar --> 1.4G
kalilinux_kali_rolling_amd64-docker_exported.tar --> 124M
kalilinux_kali_rolling_arm64-docker_exported.tar --> 146M
opensuse_leap-docker_exported.tar --> 113M
opensuse_tumbleweed-docker_exported.tar --> 136M

[+] sha256sum
ef4e8ccd1b1b7e4f141b91e9a1a84438fad27cd82538fdc7f61d0b578027629d  /tmp/docker-tars/amd64_almalinux_latest-docker_exported.tar
746b8dcb8ddfca3ca48789feda7f8d3a8a37411c67607f5db537db8ce3ef7c4e  /tmp/docker-tars/amd64_alpine_latest-docker_exported.tar
3d906a7d05a6198fa2a02ca0961d773c8af69ea7ae615a47064cccc740097201  /tmp/docker-tars/amd64_amazonlinux_latest-docker_exported.tar
5e0728efc56d8ce4b50ed4e75816de751d89023ab645987687b9df8f30f8b789  /tmp/docker-tars/amd64_archlinux_latest-docker_exported.tar
7103d363084b1a755995242c5530037714b89ddd74552c2fd006e14291a184a2  /tmp/docker-tars/amd64_clearlinux_latest-docker_exported.tar
32946b07b65aa3d857ff678c89058e297d0fe350b28b0bde7346a4bc11977644  /tmp/docker-tars/amd64_debian_latest-docker_exported.tar
8b65bde1ae995ab033af4baa9e4748b8472edcd66ef19824cc001b0ec0c8ce76  /tmp/docker-tars/amd64_fedora_latest-docker_exported.tar
c719d5e7998cd167dfe29cf91600cc2866cc88e7b46dbfad594b06ea96a110ae  /tmp/docker-tars/amd64_fedora_rawhide-docker_exported.tar
9df0eed5e4e52e199b56595a7ba368a317b8cec76c4b3cc3ebaadf7b9fe3dbfb  /tmp/docker-tars/amd64_oraclelinux_9-docker_exported.tar
e4bb66bc133556bcefee423499dfd3c12ee74a276e607923231190bd78e1bb2e  /tmp/docker-tars/amd64_oraclelinux_9_slim-docker_exported.tar
2e4ab618e9140f7885782d7e9a7479720a33fa570c1447e5c8c8194cefbbbd58  /tmp/docker-tars/amd64_rockylinux_9-docker_exported.tar
097dfbfbdfe13d48d1f4c999e3071ad2ae0ee8c575e63ab23bc008fd6e2f1577  /tmp/docker-tars/amd64_rockylinux_9_minimal-docker_exported.tar
306463427053e0fd1f25221b017a643d77e8fc9f4bf9e684e085d9d428ef9015  /tmp/docker-tars/amd64_ubuntu_latest-docker_exported.tar
d91f750daa6b0a8bf6ceb9363df6a95f47174dcf0aa719e2099fa052db817f93  /tmp/docker-tars/arm64v8_almalinux_latest-docker_exported.tar
e08c92140484ca7be9931058ea69198aca28dc10b321ce0b6cf0dc1fb82d9956  /tmp/docker-tars/arm64v8_alpine_latest-docker_exported.tar
78047bb4ee1d2212a4c68daf9f54e0bd47809931adf8246dcffa56260ee13104  /tmp/docker-tars/arm64v8_amazonlinux_latest-docker_exported.tar
2d937d6064524ed855985c00daa24d113c817469d06b4fa39fc88a46fdeffcc4  /tmp/docker-tars/arm64v8_debian_latest-docker_exported.tar
b4f6a58527124c03a3091c4048b61342279f9ccb04b2095241f43ae6170bc0ac  /tmp/docker-tars/arm64v8_fedora_latest-docker_exported.tar
72761f43d5607a103b585b927334939245c8c9b0b16a33a483fd3f05b8d76823  /tmp/docker-tars/arm64v8_fedora_rawhide-docker_exported.tar
f362e6870dd56cd511ef03a9676e80a5064d8a57321e3526751e52c1e742b4bd  /tmp/docker-tars/arm64v8_oraclelinux_9-docker_exported.tar
40e14e87a74c58524f364283c55f39f158e18cd86f09b72f141e6ed04e77b227  /tmp/docker-tars/arm64v8_oraclelinux_9_slim-docker_exported.tar
7c03a7f331d61b8e44c7e1f745e40f34cf2cd3aa02e85109ab363bdb2282f192  /tmp/docker-tars/arm64v8_rockylinux_9-docker_exported.tar
1babbeab0f0da3dbf0a3fbeeb819f03194e0648e85551d23cd3c74b29f9d3fd3  /tmp/docker-tars/arm64v8_rockylinux_9_minimal-docker_exported.tar
88e410d1693ae22bd705dd2e87b544292b9ee609bca36af3636aac9f9425a800  /tmp/docker-tars/arm64v8_ubuntu_latest-docker_exported.tar
17d5cc4740b95edd3b9f0f936cabf40885b5676b653ad940a9702c67c228e2b5  /tmp/docker-tars/gentoo_stage3_latest-docker_exported.tar
241570b901a02a41cc68b9e098f07512f8e332f02dd8c9eb2fd1ea6844489443  /tmp/docker-tars/gentoo_stage3_systemd-docker_exported.tar
d644ddd688e96515aa81e0c9dfc1840e029766e619440f2639302094a8a32ca7  /tmp/docker-tars/kalilinux_kali_rolling_amd64-docker_exported.tar
0dea488e39a6f4d6ad1045a72c30672b2a6eaf4a3130bb389bb4e2805121b00d  /tmp/docker-tars/kalilinux_kali_rolling_arm64-docker_exported.tar
f30898d5284ac407c94e6df18b722993eb04c5568cee6c1f97713592ad93e9f7  /tmp/docker-tars/opensuse_leap-docker_exported.tar
fe255128db43851ed56b2afc79ba5f88fdf45b500a198dbc31b059cff58a8339  /tmp/docker-tars/opensuse_tumbleweed-docker_exported.tar

```

---


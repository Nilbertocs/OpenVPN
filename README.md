# Instalação do OpenVPN

Instalador compatível com:
Debian, Ubuntu, Fedora, CentOS and Arch Linux.

Esse script irá instalar o servidor OpenVPN automaticamente em poucos minutos.

## Instalação

**You have to enable the TUN module otherwise OpenVPN won't work.** Ask your host if you don't know how to do it. If the TUN module is not enabled, the script will warn you and exit.

You can get a cheap VPS to run this script for $2.50/month worldwide at [Vultr](https://goo.gl/Xyd1Sc) or 3€/month for unlimited bandwidth in France at [PulseHeberg](https://goo.gl/76yqW5).

Execute com permições de root o único comando abaixo:

```bash
wget https://raw.githubusercontent.com/Nilbertocs/OpenVPN-install/master/openvpn-install.sh
chmod +x openvpn-install.sh
```

Then run it :

`./openvpn-install.sh`

The first time you run it, you'll have to follow the assistant and answer a few questions to setup your VPN server.

When OpenVPN is installed, you can run the script again, and you will get the choice to :

- Add a client
- Remove a client
- Uninstall OpenVPN

![](https://i.imgur.com/AlW9g7t.png)

## Compatibilidade

O script é compatível com os sistemas e arquiteturas abaixo:

- **Debian 7** (i386, amd64)
- **Debian 8** (i386, amd64)
- **Debian 9** (i386, amd64, armhf, arm64)
- **Ubuntu 14.04 LTS** (i386, amd64)
- **Ubuntu 16.04 LTS** (i386, amd64, armhf)
- **Ubuntu 17.10** (i386, amd64, armhf, arm64)
- **Fedora 25** (amd64)
- **Fedora 26** (amd64)
- **Fedora 27** (amd64)
- **CentOS 6** (i386, amd64)
- **CentOS 7** (i386, amd64, arm64)
- **Arch Linux** (i686, amd64, arm64)

(Também deve funcionar com versões beta do Debian e Ubuntu).
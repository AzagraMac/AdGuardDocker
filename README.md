## Docker AdGuard Home

### Requeriments
- Raspberry Pi / NanoPi NEO2 or NEO3
- Raspbian OS / DietPi
- Service docker running

### Install Docker
    sudo apt update
    sudo apt upgrade -y
    sudo apt install -y libffi-dev libssl-dev python3 python3-pip
    sudo curl -sSL https://get.docker.com | sh
    sudo usermod -aG docker $USER
    sudo apt install -y docker-compose

### Running
    docker-compose up -d

### Check
    docker ps -a


## Main White Lists
| List | Original | No IP | DNSMASQ | AdGuard <br> <sup>BETA</sup> | Description | Sponsor<sup>&#8224;</sup> |
| -- | -- | -- | -- | -- | -- | -- |
| Whitelist | [Link](https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/whitelist.txt) |  |  |  |  |  |

## Main Black Lists

| List | Original | No IP | DNSMASQ | AdGuard <br> <sup>BETA</sup> | Description | Sponsor<sup>&#8224;</sup> |
| -- | -- | -- | -- | -- | -- | -- |
| AdBlock's | [Link](https://raw.githubusercontent.com/d3ward/toolz/master/src/d3host.txt) | - | - | - | List to block advertising  | [Link](https://d3ward.github.io/toolz/adblock.html)
| Oisd | [Link](https://dbl.oisd.nl) | - | - | - | This list prioritizes functionality over blocking |[oisd.nl](https://oisd.nl/)|
| Abuse | [Link](https://blocklistproject.github.io/Lists/abuse.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/abuse-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/abuse-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/abuse-ags.txt) | Lists of sites created to deceive |[magicminiman.com](https://magicminiman.com)|
| Ads | [Link](https://blocklistproject.github.io/Lists/ads.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/ads-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/ads-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/ads-ags.txt) | Ad servers / sites | [FOIA.Services](https://foia.services) |
| Crypto | [Link](https://blocklistproject.github.io/Lists/crypto.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/crypto-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/crypto-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/crypto-ags.txt) | Crypto / cryptojacking based sites <br> <sup>Can break normal "good" crypto sites</sup> |  |
| Drugs | [Link](https://blocklistproject.github.io/Lists/drugs.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/drugs-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/drugs-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/drugs-ags.txt) | RE sites that deal with illegal drugs <br><sub>Including RX drugs illegal to posses in the US</sub> |  |
| Everything | [Link](https://blocklistproject.github.io/Lists/everything.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/everything-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/everything-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/everything-ags.txt) | List including all non beta list domains |  |
| WhatsApp | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/whatsapp.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/whatsapp.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/whatsapp.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/whatsapp.txt) | Block ads WhatsApp | - |  
| Youtube | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/youtube.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/youtube.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/youtube.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/youtube.txt) | Block ads youtube | - |  
| Fraud | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/fraud.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/fraud.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/fraud.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/fraud.txt) |  |  |  
| Crypto | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/crypto.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/crypto.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/crypto.txt) | [Link](https://raw.githubusercontent.com/blocklistproject/Lists/master/crypto.txt) |  |  |   
| Facebook | [Link](https://blocklistproject.github.io/Lists/facebook.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/facebook-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/facebook-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/facebook-ags.txt) | Block FB and FB related / owned services |  |
| Fraud | [Link](https://blocklistproject.github.io/Lists/fraud.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/fraud-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/fraud-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/fraud-ags.txt) | Sites create to fraud |  |
| Gambling | [Link](https://blocklistproject.github.io/Lists/gambling.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/gambling-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/gambling-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/gambling-ags.txt) | All gambling based site legit and illegal |  |
| Malware | [Link](https://blocklistproject.github.io/Lists/malware.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/malware-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/malware-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/malware-ags.txt) | Known sites that host malware |  |
| Phishing | [Link](https://blocklistproject.github.io/Lists/phishing.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/phishing-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/phishing-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/phishing-ags.txt) | Sites created to phish info |  |
| Piracy | [Link](https://blocklistproject.github.io/Lists/piracy.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/piracy-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/piracy-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/piracy-ags.txt) | Knows sites that allow for illegal downloads |  |
| Porn | [Link](https://blocklistproject.github.io/Lists/porn.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/porn-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/porn-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/porn-ags.txt) | Porn or sites that promote porn | [W1T3H4T](https://www.patreon.com/user/creators?u=26512074) |
| Ransomware | [Link](https://blocklistproject.github.io/Lists/ransomware.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/ransomware-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/ransomware-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/ransomware-ags.txt) | Known sites that host or contain ransomware |  |
| Redirect | [Link](https://blocklistproject.github.io/Lists/redirect.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/redirect-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/redirect-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/redirect-ags.txt) | Sites that redirect your from your intended site |  |
| Scam | [Link](https://blocklistproject.github.io/Lists/scam.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/scam-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/scam-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/scam-ags.txt) | Sites that intend to scam |  |
| TikTok | [Link](https://blocklistproject.github.io/Lists/tiktok.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/tiktok-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/tiktok-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/tiktok-ags.txt) | Copy and pasted into your device |  |
| Torrent | [Link](https://blocklistproject.github.io/Lists/torrent.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/torrent-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/torrent-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/torrent-ags.txt) | Torrent directory <br> <sub>Will likely block legit torrent sites used for legal software download</sub> |  |
| Tracking | [Link](https://blocklistproject.github.io/Lists/tracking.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/tracking-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/tracking-dnsmasq.txt) | [Link](https://blocklistproject.github.io/Lists/adguard/tracking-ags.txt) | Sites dedicated to tracking and gathering visitor info | [FOIA.Services](https://foia.services) |   

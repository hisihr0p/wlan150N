# WiFi wlan150N
interface=wlan2
driver=nl80211

# Access Point
ssid=$SSID
hw_mode=g

ieee80211n=1
ht_capab=[HT40-][SHORT-GI-40][DSSS_CCK-40][TX-STBC][RX-STBC1]
wmm_enabled=1

# WiFi Channel:
channel=10

# Security
macaddr_acl=0
auth_algs=1
ignore_broadcast_ssid=0
wpa=2
wpa_passphrase=$PASSWORD
wpa_key_mgmt=WPA-PSK
wpa_pairwise=TKIP
rsn_pairwise=CCMP

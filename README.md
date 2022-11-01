# Net Monitor 2.0

cd

opkg update

wget --no-check-certificate -O /tmp/luci-app-netmonitor_2.0_all.ipk https://github.com/planetmina/Net-Monitor/blob/main/luci-app-netmonitor_2.0_all.ipk

opkg install /tmp/luci-app-netmonitor_2.0_all.ipk

rm /tmp/luci-app-netmonitor_2.0_all.ipk

/etc/init.d/netdata restart

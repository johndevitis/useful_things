# netsh

## Virtual AP

setup virtual access point
```
netsh wlan set hostednetwork mode=allow ssid=THMPRnetwork key=drexel123
```

turn on
```
netsh wlan start hostednetwork
```

note, still need to change static ip of virtual network

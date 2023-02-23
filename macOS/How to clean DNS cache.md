* First, open up Terminal and copy the following commands:
```
sudo dscacheutil -flushcache
sudo killall -HUP mDNSResponder
```

* Then open up Chrome and browse here:
```
chrome://net-internals/#dns
```
* Look for DNS on the left sidebar, and next to "Host resolver cache", click on the button "Clear Host Cache".
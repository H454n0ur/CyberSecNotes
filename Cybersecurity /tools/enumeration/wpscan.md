# WPscan

**Cheatsheet**

<table><thead><tr><th>Flag</th><th width="237">Description</th><th>Full Example</th></tr></thead><tbody><tr><td>p</td><td>Enumerate Plugins</td><td>--enumerate p</td></tr><tr><td>t</td><td>Enumerate Themes</td><td>--enumerate t</td></tr><tr><td>u</td><td>Enumerate Usernames</td><td>--enumerate -u</td></tr><tr><td>v</td><td>Use WPVulnDB to cross-reference for vulnerabilities. Example command looks for vulnerable plugins (p)</td><td>--enumerate vp</td></tr><tr><td>aggressive</td><td>This is an aggressiveness profile for WPScan to use.</td><td>--plugins-detection aggressive</td></tr></tbody></table>

**Performing a Password Attack**

```
wpscan –-url http://cmnatics.playground –-passwords rockyou.txt –-usernames username
```


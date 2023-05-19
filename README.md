# In this example we are sending to channel @tviews post number ( 4 )
# e.g: https://t.me/tviews/4

# Auto Scraping Mode ( Auto Proxy [ PROXYLESS ] MODE )
tviews.py --mode auto --channel tviews --post 4

# Load Proxies From File ( File List Mode )
tviews.py --type http --mode list --proxy http.txt --channel tviews --post 4

# Using Rotating Proxy ( Rotating Mode )
tviews.py -t http -m rotate -p user:password@ip:port -c tviews -pt 4

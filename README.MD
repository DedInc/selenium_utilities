<h1 align="center">selenium-utilities - Useful utils for comfortable using selenium.</h1>

<br>

<h1 align="center"> -How to use?- </h1>

```python
import selenium_utilities as su

#Install and get driver paths:
chrome_driver = su.getChromeDriver()
opera_driver = su.getOperaDriver()
operagx_driver = su.getOperaDriver(gx=True)
yandex_driver = su.getYandexDriver()
firefox_driver = su.getFirefoxDriver()
edge_driver = su.getEdgeDriver()

#If you want to update the driver, then use True inside the function for example: su.getChromeDriver(update=True)
```
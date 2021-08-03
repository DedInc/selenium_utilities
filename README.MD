<h1 align="center">selenium-utils - Useful utilities for comfortable using selenium.</h1>

<br>

<h1 align="center"> -How to use?- </h1>

```python
import selenium_utils as su

#Install and get driver paths:
chrome_driver = su.getChromeDriver()
opera_driver = su.getOperaDriver()
yandex_driver = su.getYandexDriver()
firefox_driver = su.getFirefoxDriver()
edge_driver = su.getEdgeDriver()

#If you want to update the driver, then use True inside the function for example: su.getChromeDriver(True)
```
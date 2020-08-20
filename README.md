# api_coingecko.
__lib implementing__ [service](https://coingecko.com/)

# dep
**python>=3.7**
**aiohttp>=3.6**

#how use
```python
from api_coingecko import CryptoPrice
import aiohttp

async def main():
   session: aiohttp.ClientSession = aiohttp.ClientSession()
   coingenko = CryptoPrice(session)
   await coingenko.need_your_method()
```

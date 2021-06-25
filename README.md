# hollybooks
An Api wrapper for extract info from 3 diffreant holly books. Right now (6/25/2021) it only have 1 api which connect to the quran api. My plan is to have 3 Api(s).
 
# Installation 
```bash
No instalation for now!
```

# Usage

```python
from hollybook import quran

# To return a quran's verse/chapter(surah) and other info

surah=quran.Surah.request(1) #1 is the first chapter and request is for sync function to make it async replace request to async_request
print(surah.name('eng')) #Only support arabic(ar) and english(eng)
#return al-fatihah

print(surah.name_mean())
#return The Opener
```

# API That I Use
[Qur'an](https://alquran.cloud/api) 

Bible - Not available 

Torah - Not available

# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

# License
[MIT](https://choosealicense.com/licenses/mit/)

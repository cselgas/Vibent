# Website-Portfolio
https://cselgas.com: My personal portfolio website which includes my full web portfolio and showcases my skills and abilities for creating many kinds of applications, from single-page websites to fully-functioning social media platforms.
```
SKILLS USED: PHP (Contact Form Mailing), Javascript (Page, Transition, and Button Functionalities), HTML, CSS
```

https://vibent.io/: A social platform for music producers & creators to livestream and share their own tracks and playlists. Users can discover new artists by filtering through category. In other words, Twitch for music!
```
SKILLS USED: PHP (extensively), phpMyAdmin, SQL & mySQL, SendGrid Mailing Systems (Custom Weekly or Daily "Top Playlists" Emails, other notifications)
    JavaScript, jQuery, HTML, CSS,
        Extensive work with Youtube, Google, and SoundCloud APIs
```
                    
https://mikespizzakendall.com: Built the website for Mike’s Pizza, an Italian restaurant located in the Kendall, Miami region. 🍕
  SKILLS USED:  WordPress (extensively), JavaScript, HTML, CSS


## Imports
Since the data-cube is a Numpy nested dictionary, we need to import Numpy to work with the values. Matplotlib is also imported for visualizations:
```python
import numpy as np
import matplotlib.dates as mdates
import matplotlib.pyplot as plt
%matplotlib inline
```

## Using the Data
```python
# Reading the data cube (Replace 'x' with latest version)
data = np.load('data_cube_vx.npy',allow_pickle='TRUE').item()

# Returns the entire cube
print(data)

# Working with Values
# The example below would give you the centroid value for the 3rd Line in Order 50 for Feb 8, 2021 @ 19:10:24
centroid = data['Time 20210208T191024')]['Order 50']['Line 3']['centroid']
```

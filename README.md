- š Hi, Iām @Joanliver
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Joanliver/Joanliver is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import requests, json
import pyimgur

CLIENT_ID = '>:'
PATH = '<>'

im = pyimgur.Imgur(CLIENT_ID)
uploaded_image = im.upload_image(PATH, title = '<nome>')

print(uploaded_image.title)
print(uploaded_image.link)
print(uploaded_image.size)
print(uploaded_image.type)

print('Uploaded link:', uploade_image.link

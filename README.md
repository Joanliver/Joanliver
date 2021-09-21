- 👋 Hi, I’m @Joanliver
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Joanliver/Joanliver is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
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

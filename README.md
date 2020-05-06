<p align="center"><img src="img/logo.png" alt="LOGO"></p>
<br>
<p align="center"><img src="img/preview.png" alt="PREVIEW"></p>

# Google Drive Index + Guide + Team Drive Maker [If you have G-suite Account]

## Full Guide to Deploy:

[GUIDE](https://telegra.ph/G-Index-DarkMode--MultiAuth--English--TD-Maker--Custom-Domainga-Tutorial-04-29)

## SAMPLE

https://g-d.rive.workers.dev/

## Search Implemented
- Features
  - Video Player - | mp4 | webm | avi | mpg | mpeg | mkv | rm | rmvb | mov | wmv | asf | ts | flv
  - Music Player - | mp3 | flac | wav | ogg | m4a
  - Document Viewer - | html | php | css | go | java | js | json | txt | sh | md | pdf
  - Image Viewer - | bmp | jpg | jpeg | png | gif
  - Multi drive encryption
  - Mobile Friendly
  - <h3> ENGLISH LANGUAGE </h3>
  - Multi-level Search within the team drive
  - Dark Theme
    - Main Color:
        - red | pink | purple | deep-purple | indigo | blue | light-blue | cyan | teal | green | light-green | lime yellow | amber orange | deep-orange | brown | greyblue-grey

     - Accent Color:
        - red | pink | purple | deep-purple | indigo | blue | light-blue | cyan | teal | green | light-green | lime | yellow | amber | orange | deep-orange

     - darkmode: true/false

# How to use?

## Deployment  


### Manual

1.Install `rclone` software locally  
2.Follow [https://rclone.org/drive/]( https://rclone.org/drive/) bind a drive  
3.Execute the command`rclone config file` to find the file `rclone.conf` path  
4.Open `rclone.conf`,find the configuration `root_folder_id` and `refresh_token`  
5.Download index.js in https://github.com/LeeluPradhan/Search/ and fill in root and refresh_token  
6.Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/)

### Want to host to your repository?
1. Simply fork this
or
2. Download this repo and upload files as per your choice
3. Use https://www.jsdelivr.com/?docs=gh to use your own `app.js` and change path accordingly in `index.js`
4. Copy your completed `index.js` to [Cloudflare Workers](https://www.cloudflare.com/)
4. Enjoy :)

### Credits
https://github.com/yanzai/goindex
https://github.com/LeeluPradhan/G-Index

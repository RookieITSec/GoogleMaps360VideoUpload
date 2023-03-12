# GoogleMaps360VideoUpload
This repo will contain the details on how I am uploading 360 video to Google maps.  There are some strange nuances and whatnot so this is a bit of a work in process.





## Capture the video - 


## Extract GPX Data
Two methods to extract GPX data - 

### 1. UL2GSV's tool for insta36 Cameras - 


### 2. exiftool - 

"C:\exiftoolgui\exiftool.exe" -p "D:\gpx.fmt" -ee -ext insv -w "D:\2023-03-10-360\%f.gpx" "D:\2023-03-10-360"
Info source - https://www.youtube.com/watch?v=Uje5si23lBk


## Upload the video
Two methods tested so far - 

1. UL2GSV's tool

2. Google StreetView Studio Website.


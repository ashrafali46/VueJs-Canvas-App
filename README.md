# mosaic-test

> Image manipulation SPA 

(1)<br />
Development started with a simple quick proof-of-concept prototype focused
on core image-related routines without any additional features and UI. 
The solution is a simple page with vanilla JS and some JQuery.<br />
<br />
Prototype's core features:<br />
a) upload and image resizing to fit predefined maximum size<br />
b) mosaic effect generation<br />
c) mosaic upload to Imgur<br />

http://localhost:8080/image-lab.html<br />

(2)<br />
Today I designed the UI using material components from 'vue material'. The user flow
is simple. The entry screen contains an file upload input and a gallery to pick 
images from. When the image is selected and uploaded a 'light-box' window pops up with
the original and the processed mosaic image.<br />
<br />
![Entry screen](https://raw.githubusercontent.com/luke-b/mosaic-test/master/ui-layout1.png)
![Mosaic preview lightbox](https://raw.githubusercontent.com/luke-b/mosaic-test/master/ui-layout2.png)
<br />
Next steps:<br />
a) test cases<br />
b) app UI design<br />
c) vue app creation<br />

(the code is leaking CLIENT-ID)




## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

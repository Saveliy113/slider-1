# Image slider #1

![preview](https://github.com/Saveliy113/slider-1/blob/master/Slider_1.gif)

This image slider features a clean and modern design with a full-screen layout. Includes navigation arrows that allow the user to manually move between images. It is possible to add any amount of images you want.

# How to use

There are two containers in html markup.
First (sidebar) contains all background and titles:

```
<div style="background: linear-gradient(229.99deg, #df0404 -26%, #cf1c1c 145%);">
    <h1>HONDA</h1>
    <p>CRF-450R</p>
</div>
```

And second(main-slide) images:

```
<div style="background-image: url('https://www.dirtrider.com/resizer/KJB8ymP8SbFeievxprYDJ1Fohxc=/1440x0/filters:focal(941x784:951x794)/cloudfront-us-east-1.images.arcpublishing.com/octane/IOMUBXODABCNDIUKJRMILKJPIA.jpg')"></div>
```

To adjust slider for your purposes simply change background colors and images.

> Pay attention that backgrounds and images are in reverse order. Last background corresponds to the first image and so on.

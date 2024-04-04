# Awesomeslider
![Screenshot from 2024-04-04 22-31-00](https://github.com/albinthomasv/awesomeslider/assets/87915601/cf18f8dc-3094-418a-aa4d-47ad9f8bfdee)

Enhance your website's visual appeal and user experience with our custom slider script, allowing seamless navigation through captivating images and content.

# What you are able to do
- Can able to customize into your own design.
- Add/Remove slides.
- Turn on/off slider autoplay
- Can able to set autoplay delay in sec.
- Turn on/off lighbox

# How to add Awesome Slider on your page

## Add  Awesome slider HTML Layout
```
<div class="photo-wrapper">
        <div class="photo-container">
            <div class="photo">
                <img src="../image1">
            </div>
            <div class="photo">
                <img src="../image2">
            </div>
            <div class="photo">
                <img src="../image3">
            </div>
            <div class="photo">
                <img src="../image4">
            </div>
            <div class="photo">
                <img src="../image5">
            </div>
            <div class="photo">
                <img src="../image6">
            </div>
            <div class="photo">
                <img src="../image7">
            </div>
            <div class="photo">
                <img src="../image8">
            </div>

        </div>
        <button class="prev">&lt;</button>
        <button class="next">&gt;</button>
    </div>
```
## Initialize Awesome Slider Script
```
<script type="text/javascript" src="awesomeslider.min.js"></script>
    <script>
        var slider = new AwesomeSlider();
        slider.init({ selector: '.photo', visibleItem: 4, nextBtnClass: "next", previousBtnClass: 'prev', lightbox: true, autoPlay:true,delay: 2 });

</script>
```



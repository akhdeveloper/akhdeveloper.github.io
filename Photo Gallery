<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Photo Gallery</title>
    <style>
        /* Name this external file gallery.css */
        body {
            margin: 2%;
            border: 1px solid black;
            background-color: #b3b3b3;
        }

        #image {
            line-height: 650px;
            width: 575px;
            height: 650px;
            border: 5px solid black;
            margin: 0 auto;
            background-color: #8e68ff;
            background-image: url('');
            background-repeat: no-repeat;
            color: #FFFFFF;
            text-align: center;
            background-size: 100%;
            margin-bottom: 25px;
            font-size: 150%;
        }

        .preview {
            width: 10%;
            margin-left: 17%;
            border: 10px solid black;
        }

        img {
            width: 95%;
        }
    </style>
</head>

<body>

    <div id="image">
        Hover over an image below to display here.
    </div>

    <img class="preview" alt="Styling with a Bandana"
        src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/389177/bacon.jpg" onmouseover="upDate(this)"
        onmouseout="unDo()" tabindex="0">

    <img class="preview" alt="With My Boy" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/389177/bacon2.JPG"
        onmouseover="upDate(this)" onmouseout="unDo()" tabindex="0">

    <img class="preview" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/389177/bacon3.jpg" alt="Young Puppy"
        onmouseover="upDate(this)" onmouseout="unDo()" tabindex="0">

    <img class="preview" alt="Cool Shades" src="https://cdn.pixabay.com/photo/2016/11/21/14/57/cool-1845831_1280.jpg"
        onmouseover="upDate(this)" onmouseout="unDo()" tabindex="0">

    <img class="preview" alt="Hiking Adventure"
        src="https://media.istockphoto.com/id/1443409611/photo/man-on-stone-on-the-hill-and-beautiful-mountains-in-haze-at-colorful-sunset-in-autumn.jpg?s=1024x1024&w=is&k=20&c=_kr-m_0O3Z7T8Nc5z2RbbdBZBlX6f2y9i0UvVMEBYYk="
        onmouseover="upDate(this)" onmouseout="unDo()" tabindex="0">

    <img class="preview" alt="Coffee Break" src="https://cdn.pixabay.com/photo/2017/05/12/08/29/coffee-2306471_1280.jpg" onmouseover="upDate(this)" onmouseout="unDo()" tabindex="0">

    <script>
        var currentIndex = 0;
    var images = document.querySelectorAll('.preview');

        function upDate(previewPic) {
            var src = previewPic.getAttribute("src");
            document.getElementById('image').style.backgroundImage = "url('" + src + "')";
            document.getElementById('image').innerHTML = previewPic.alt;
            console.log("Mouseover event triggered for " + previewPic.alt);
        }

        function unDo() {
            var text = "Hover over an image below to display here.";
            document.getElementById('image').style.backgroundImage = "url('')";
            document.getElementById('image').innerHTML = text;
            console.log("Mouseout event triggered");
        }
    </script>
</body>

</html>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8" />
    <title>meme</title>
    <style type="text/css">
        body {
            font: 14px/1.3 verdana, arial, helvetica, sans-serif;
            background-color: white;
        }
    </style>
    <script type="text/javascript">
        // place your images in this array

        var random_images_array = [&#39LinK_TemP_1| &#39LinK_TemP_2| &#39LinK_TemP_3| &#39LinK_TemP_4| &#39LinK_TemP_5| &#39LinK_TemP_6| &#39LinK_TemP_7| &#39LinK_TemP_8| &#39LinK_TemP_9| &#39LinK_TemP_10| &#39LinK_TemP_11| &#39LinK_TemP_12| &#39LinK_TemP_13| &#39LinK_TemP_14| &#39LinK_TemP_15| &#39LinK_TemP_16| &#39LinK_TemP_17| &#39LinK_TemP_18| &#39LinK_TemP_19| &#39LinK_TemP_20| &#39LinK_TemP_21| &#39LinK_TemP_22| &#39LinK_TemP_23| &#39LinK_TemP_24|
            &#39LinK_TemP_25| &#39LinK_TemP_26| &#39LinK_TemP_27| &#39LinK_TemP_28| &#39LinK_TemP_29| &#39LinK_TemP_30| &#39LinK_TemP_31| &#39LinK_TemP_32| &#39LinK_TemP_33| &#39LinK_TemP_34| &#39LinK_TemP_35| &#39LinK_TemP_36| &#39LinK_TemP_37| &#39LinK_TemP_38| &#39LinK_TemP_39| &#39LinK_TemP_40| &#39LinK_TemP_41| &#39LinK_TemP_42|

        ];

        function getRandomImage(imgAr, path) {
            path = path || 'images/'; // default path here
            var num = Math.floor(Math.random() * imgAr.length);
            var img = imgAr[num];
            var imgStr = '<img src="' + img + '" alt = "">';
            document.write(imgStr);
            document.close();
            document.getelementbyid("image".html = imgStr
        }
    </script>
</head>

<body>
    <img id="image">
    </image>
    <button onclick="getRandomImage(random_images_array, 'images/&#39"></button>
    <div>
        <!-- This script segment displays an image from the array -->
        <script type="text/javascript">
            getRandomImage(random_images_array, 'images/&#39
        </script>
    </div>
</body>

</html>

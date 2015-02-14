Superman
========

Duck Hunt Dog Konami Code

This is a variation of the raptoize Konami code. This version has Superman flying across the screen.

Here is a demo http://dplumly.github.io/Superman

Just enter the code and watch the magic!

To use this on your website just add the following code to the bottom of your site:

<script src="jquery.js"></script>
    <script src="superman.js"></script>

        <script type="text/javascript">
            $(window).load(function() {
                $('.button').superman({
                    'enterOn' : 'konami-code', //timer, konami-code, click
                        'delayTime' : 5000 //time before superman appears on timer mode
                    });
                });
        </script>

        <a href="#" class="button" style="visibility: hidden"></a>
    
        <img id="superman" style="display: block; position: fixed; z-index: 1000; bottom: -500px; right: 0px;" src="superman.png">

        <audio id="zoom" preload="auto">
            <source src="superman.mp3">
        </audio>
You can easily add different music and a .png


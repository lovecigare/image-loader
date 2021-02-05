    var imgSrc = <?php echo "'". $rows[0]['pdf_img']."'";?>;
    var bgImg = document.getElementById("pagecontent");
    var canvas = document.getElementById('pdf-canvas');
    var context = canvas.getContext('2d');
    var image = new Image();
    bgImg.style.background = "url("+imgSrc+")";
    bgImg.style.backgroundRepeat = "repeat-y";

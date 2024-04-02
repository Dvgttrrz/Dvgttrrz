[3/18 10:04 AM] Aries Molinar
.container {
    position: relative;
    overflow: hidden;
    width: 100%;
    padding-top: 56.25%; /* 16:9 Aspect Ratio (divide 9 by 16 = 0.5625) */
  }
 
  /* Then style the iframe to fit in the container div with full height and width */
  .responsive-iframe {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    width: 100%;
    height: 100%;
  }
[3/18 10:08 AM] Aries Molinar
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>360 web</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <iframe class="responsive-iframe" src="https://my.matterport.com/show/?m=iJeG1C9bZW3"></iframe>
      </div>
</body>
</html>

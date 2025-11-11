# imihsduhug
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imitation-Monte</title>
    <style>
        /* Styles for the first section image */
        #dino {
            -webkit-filter: hue-rotate(90deg);
            filter: hue-rotate(90deg);
        }

        /* Styles for the second section image */
        /* The background properties won't be visible because the image covers the entire element area defined by height/width */
        #seagull {
            height: 396px;
            background-image: linear-gradient(-45deg, white, lightblue, blue);
            background-color: navy;
        }

        /* Styles for the third section image */
        #penguin {
            border-radius: 50px; /* Shorthand for 50px 50px 50px 50px */
            background-color: pink;
            height: 560px; /* This height will stretch the image */
            -webkit-filter: sepia(100%);
            filter: sepia(100%);
        }
    </style>
</head>
<body>

  <section>
    <img id="dino" width="455" height="482" alt="dinosaur" src="https://github.com/user-attachments/assets/29e229d1-f416-4624-a940-7da1eafd6edb"/>
  </section>

  <section>
    <img id="seagull" width="560" height="396" alt="seagull" src="https://github.com/user-attachments/assets/dbeb73a5-1598-4f7c-b814-d03b91b41ae4"/>
  </section>

  <section>
    <!-- Corrected ID to "penguin" to match the CSS selector -->
    <img id="penguin" width="560" height="400" alt="penguin" src="https://github.com/user-attachments/assets/377609e6-7001-4449-a59c-cdb49de18751"/>
  </section>

</body>
</html>

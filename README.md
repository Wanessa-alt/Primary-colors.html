# Primary-colors.html
Creating a website with the primary colors using html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8"> 
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Colors theory</title>
    </head>
    <body>
        <h1>Primary colors</h1>
        <p>Primary colors are:</p> 
        <ul class="circle"></ul>
        <li>First circle</li>

        <li>Second circle</li>

        <li>Third circle</li>
    
        <style>

        .circle {
            list-style : circle;
            padding: 0;
            margin: 0;
            display: flex;
            gap: 12px;
            counter-reset: circle;
        }

        .circle li {
            width: 48px;
            height: 48px;
            align-items: left;
            color: #F00;
            font-weight: 600;
            font-family: sans-serif;
            background: #e53935;


  }
        .circle li {
          width: 48px;
            height: 48px;
            align-items: left;
            color: #00F;
            font-weight: 600;
            font-family: sans-serif;
            background: #1e88e5;
 
        }

        .circle li {
            width: 48px;
            height: 48px;
            align-items: left;
            color: #000
            font-weight: 600;
            font-family: sans-serif;
            background: #fdd835; 
 
        }
        </style>

        <ul class="circle"></ul>
            <li><span class="label"></span>Red</span><span class="dot red">1</span></li>
            <li><span class="label"></span>Blue</span><span class="dot blue">2</span></li>
            <li><span class="label"></span>Yellow</span><span class="dot yellow">3</span></li>
        </ul>

        <style>
            .circle {
                list-style: none;
                padding: 0;
                margin: 0;
                display: flex;
                gap: 12px;
                counter-reset: circle;
            }

            .circle li {
                width: 48px;
                height: 48px;
                display: flex;
                align-items: center;
                justify-content: center;
                color: #fff;
                font-weight: 600;
                font-family: sans-serif;
                border-radius: 50%;
            }

            .label { font-family: sans-serif; font-weight:600; }

            .dot {
  width:40px; height:40px; border-radius:50%;
  display:flex; align-items:center; justify-content:center;
  color:#fff; font-weight:700;
}

.dot.red { background:#E53935; }
.dot.blue { background:#1E88E5; }
.dot.yellow { background:#FDD835; color:#000; }
        </style>
        <h2>Primary colors can not be created by mixing other colors.</h2>
     

    </body>
    </html>

# Dark-Light-Mode-using-JavaScript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Learning Java Script from Youtube </title>
    <link rel="stylesheet" href="ytcss.css">
    
</head>
<body>
    <button id="mode">Dark mode</button>
    <script>
             let mode = document.querySelector("#mode");
             let cmode="Light mode";

              mode.addEventListener("mouseover",()=>{
              if (cmode === "Light mode"){ 
              document.querySelector("body").style.backgroundColor="black";
              document.querySelector("#mode").innerText="Light Mode";   
              cmode ="Dark Mode";
    } else {
            document.querySelector("body").style.backgroundColor="white";
            document.querySelector("#mode").style.color="black";
            document.querySelector("#mode").innerText="Dark Mode";   
           cmode="Light mode";
          }
          console.log(cmode);
      });
    </script>
</body>
</html>

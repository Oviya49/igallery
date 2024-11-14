# Ex.08 Design of Interactive Image Gallery
## Date:14-11-2024

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
    <title>
        Interactive Image Gallery
    </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            background-size: cover;
            background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRf5cIjpqoONwpsAMYqSUDX5TIkL-pKwCxRcA&s");
        }

        h1 {
            margin-top: 20px;
            color: rgb(0, 139, 53);
            font-size: xx-large;
            font-style: italic;
        }

        .Gallery {
            display: flex;
            gap: 15px;
            max-width: 800px;
            margin-top: 20px;
            justify-content: center;
        }
    </style>

    <body>
        <h1>Interactive Image Gallery</h1>
        <div class="Gallery">
            <img src="https://next-images.123rf.com/index/_next/image/?url=https://assets-cdn.123rf.com/index/static/assets/top-section-bg.jpeg&w=3840&q=75" width="200" height="200" onclick="openImage(this.src)">
            <img src="https://media.istockphoto.com/id/517188688/photo/mountain-landscape.jpg?s=1024x1024&w=0&k=20&c=z8_rWaI8x4zApNEEG9DnWlGXyDIXe-OmsAyQ5fGPVV8=" width="200" height="200" onclick="openImage(this.src)">
            <img src="https://st.depositphotos.com/1718692/3934/i/450/depositphotos_39341537-stock-photo-pine-trees-near-valley-in.jpg" width="200" height="200" onclick="openImage(this.src)">
            <img src="https://www.aaronreedphotography.com/images/xl/Sweet-Dreams-2022.jpg" width="200" height="200" onclick="openImage(this.src)">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToV6AeAGjafklwyOTmhFuAR_pzUUH3CtjoTg&s" width="200" height="200" onclick="openImage(this.src)">
        </div>

        <script>
            function openImage(src) {
                window.open(src, "_blank");
            }
        </script>
    </body>
</html>
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/e20fb44f-764d-4c22-bad9-d4f13b886fdc)
![image](https://github.com/user-attachments/assets/5f1f6e2a-9dca-414c-9421-023c96f2d896)




## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.

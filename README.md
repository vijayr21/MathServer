# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
To design a website to find surface area of a Right Cylinder in server side.

## FORMULA:
Surface Area = 2Πrh + 2Πr<sup>2</sup>
<br>r --> Radius of Right Cylinder
<br>h --> Height of Right Cylinder

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body>
    <script>
         function fn(e) {
        if (e.innerHTML == '=' ) {
        output.value = eval(output.value);
        }
        else if (e.id == 'back') {
        v = output.value;
        output.value = v.substring(0, v.length - 1);
        }
        else if (e.innerHTML == 'C') {
        output.value = '';
        }
        else {
        output.value +=  e.innerHTML;
        }
    }
    </script>
    <div class="bg-dark mx-auto text-center text-white" style="width: 24rem; "> VIJAY R(21223240178)</div>
    <div class="bg-dark row mx-auto text-center" style="width: 24rem;">
    <div class="col-12 my-4"><input type="text" name="" id="output"
    style="width: 100%; height: 50px; border-radius: 25px;"></div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">(</div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">)</div>
    <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)">C</div>
    <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)" id="back"><i class="bi bi-backspace"></i>
    </div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">7</div> 
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">8</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">9</div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">*</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">4</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">5</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">6</div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">-</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">1</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">2</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">3</div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">+</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">0</div>
    <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">.</div>
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">%</div> 
    <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">/</div>
    <div class="m-3 col-11 btn btn-warning rounded-4" onclick="fn(this)">=</div>
    </div>
</body>
</html>
```
## SERVER SIDE PROCESSING:

![Screenshot 2024-04-18 092829](https://github.com/vijayr21/MathServer/assets/149347607/eda2b40d-a0e3-4b8c-8502-af38773bad66)



## HOMEPAGE:
![Screenshot 2024-04-18 092229](https://github.com/vijayr21/MathServer/assets/149347607/41930dbf-1d64-4819-923e-da2e70ae1b27)



## RESULT:
The program for performing server side processing is completed successfully.

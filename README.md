# Work-college
6 задание Массивы без использования цикла, вариант 1 

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UFT-8">
    <meta http-equiv="X-UA-Compagfible" content="IE-edge">
    <meta name="viewport" content="width-device-width, inftical-scale=1.0">
    <script type="text/javascript">
    <title>Массивы</title>
    let m = window.prompt("введите длинну массива"); 
    m = parseInt(m); 
    let arr = new Array(m); 
    let x = arr.fill(0); 
    let square = x.map(function (m,i){ 
        if (i%2 == 0){ 
            return ((i/2) + 1)**2 
        } 
        else{ 
            return 0 
        } 
    }) 
    square.forEach((m) => { 
        window.document.write(m +' ') 
    });
    </script>
    </head>
    </html>

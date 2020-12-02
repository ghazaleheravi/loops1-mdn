# loops1-mdn
<!doctype html>
<html lang="en-us" dir="ltr">
    <head>
        <meta charset="utf-8">
        <title>loops 1</title>
    </head>

    <body>
        <h2>My list:</h2>
        <ul>

        </ul>

        <script>

            let myArray = ['tomatoes','chick peas','onions','rice','black beans'];
            let list = document.querySelector('ul');

            for(let i=0;i<myArray.length;i++){
                let li = document.createElement('li');
                li.textContent = myArray[i];
                list.appendChild(li);
                
            }



        </script>
    </body>
</html>

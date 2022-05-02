# Proiect-butoane
<!doctype html>
<html lang="en">
    <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>PROIECT BUTOANE</title>
  </head>
  <body>
<script>
    function generateRandomIntegerInRange(min, max) {
      function apasa(min, max) {
        return Math.floor(Math.random() * (max - min + 1)) + min;
      }

    let buton = apasa(0, 1);

    if(buton == 1) {
        console.log(buton);
        console.log("CASTIGATOR!");
        } else {
            console.log(buton);
            console.log("NECASTIGATOR!");
        }
      }
</script>
      <div class="container">
         <div class="card">
          <div class="card-body">
               <h5>DACA TE CREZI NOROCOS APASA ACEST BUTON!</h5>
              <a href="#" class="btn btn-primary" onclick="generateRandomIntegerInRange(0, 1)">Butonul numarul 1</a>
          </div>
         </div>
      </div>
  </body>
</html>

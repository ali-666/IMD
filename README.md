<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>form</title>
    <style>
        #negar{
            display: block;
            width: 100px;
            height: 50px;
            
        }
    </style>
</head>
<body>
    <fieldset>
        <legend>negar form</legend>
        <form action="reg.php" method="get" autocomplete="off">
            <label for="n">name:</label><input type="text" title="name" placeholder="name" id="n" tabindex="1"><br>
            <label> password:</label><input type="password" placeholder="pass" tabindex="3"><br>
            <label for="">email:</label><input type="email" placeholder="ex@mp.com" tabindex="2"><br>
            <label for="">reg code:</label><input type="nember" value="5689" readonly><br>
            <label for="">favorte color:</label><input type="color"><br>
            <label for="">birthday: </label><input type="date" required><br>
            <label for="">your site address:</label><input type="url" placeholder="www.ex.com"><br>
            <label for="">telephone: </label><input type="tel" placeholder="021-******"><br>
            <label for="">age:</label><input type="range" min="20" max="40"><br>
            <label for="">age: </label><input type="number" min="20" max="40" step="5" value="20">
            <button value='add' id="negar">add</button><br>
            <label for="">upload: </label><input type="file"><br>
            <label for="">search:</label><input type="search"><br>
            <label for="">sport:</label>
            <label for="">vallyball</label>
            <input type="checkbox" name="vollyball">
            <label for="">football</label><input type="checkbox" name="footbal" ><br>
            <label for="">nationality: </label>
            <label for="">iran</label><input type="radio" name="nat" value="iran" checked>
            <label for="">iraq</label><input type="radio" name="nat" value="iraq">
            
             
            
            
            
            
            
        </form>
    </fieldset>
</body>
</html>

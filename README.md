<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/style/style.css">
    <title>Dom 8</title>
</head>
<body>
 <div class="form-body">
    <form id="entry-form" action="" method="post">
        <div class="form-field">
            <input type="text" class="form-group" placeholder="Name" name="name" id="name">
        </div>
        <div class="form-field">
            <input type="email" name="email" placeholder="Email" id="email" class="form-group">
        </div>
        <div class="form-field">
            <input type="tel" name="phone" placeholder="Phone" id="phone" class="form-group">
            <input type="series" name="series" placeholder="Series" id="series" class="form-group">
        </div>
        <div class="form-field text-center">
            <button id="submit-button">Submit</button>
        </div>
    </form>
    <script src="dom8.js"></script>
</div>
</body>
</html>

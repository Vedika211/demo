<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=<script>>, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        function ask(question, yes, no) {
 if (confirm(question)) yes();
 else no();
}
ask(
 "Do you agree?",
 () => alert("You Agreed"),
 () => alert("You canceled the execution.")
);


   
   </script>
</body>
</html>

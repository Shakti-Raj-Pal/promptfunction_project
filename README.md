# promptfunction_project

<body>
        Name : <i id="result"></i> <br> <br>
        <button onclick="call()">Click me</button>
       <script>
        function call(){
       var name =   prompt("Enter your name" , " ");
       //  document.write(result);
         document.getElementById('result').innerHTML = name;
        }
       </script>
</body>

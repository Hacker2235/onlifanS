# onlifanS
Chichis
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"> </script>

    <script>  
        // Add "https://ipinfo.io" statement  
        // this will communicate with the ipify servers   
        // in order to retrieve the IP address  
        $.get("https://ipinfo.io", function(response) {  
            alert(response.ip);  
        }, "json")  
        // "json" shows that data will be fetched in json format  
    </script> 

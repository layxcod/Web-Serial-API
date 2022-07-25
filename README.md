# Web-Serial-API

i use HTML\Javascript\arduino


After creating the Arabic speaking page and printing the text, now we need to link the html page in Arduino using JavaScript, than
I used the Web Serial API to connect the page that I worked on previously with Arduino.

to link html page and javaScript:


       `<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>  
       
        <script src="script.js"></script>
        <script src="arduino.js"></script>
        <script>
        </script>`
       
       
 to define moves: 
       
     `Servo gripper;

      Servo wrist;
      
      Servo elbow;
      
      Servo shoulder;
      
      Servo base;`
      
      

    if (var == 1)
    digitalWrite(13, HIGH);
    delay(0);
    var = 0; }
    
 { delay(7000);
    if (var == 0)
    digitalWrite(13, LOW);
    delay(0);
    var = 1; 
    
    
    if (var == 1)
    digitalWrite(12, HIGH);
    delay(0);
    var = 2;}
    
    {    
    delay(5000);
    if (var == 2)
    digitalWrite(11, HIGH);
    delay(0);
    var = 2;
    
    if (var == 2)
    digitalWrite(12, LOW);
    delay(0);
    var = 3;
    }
    
   {  delay(3000);
     if (var == 3)
     digitalWrite(11, HIGH);
     delay(0);
     var = 4;
     
     if (var == 4)
     digitalWrite(5, HIGH);
     delay(0);
     var = 3;
     
      
   }{
    
    delay(3000);
    if (var == 3)
    digitalWrite(11, HIGH);
    delay(0);
    var = 2;
    
    if (var == 2)
    digitalWrite(5, LOW);
    delay(0);
    var = 2;
    
      
    if (var == 2)
    digitalWrite(7, HIGH);
    delay(0);
    var = 4;}
    
 {  delay(5000);
   if (var == 4)
    digitalWrite(11, HIGH);
    delay(0);
    var = 2;
    
    if (var == 2)
    digitalWrite(7, LOW);
    delay(0);
    var = 3; 
    
    if (var == 3)
    digitalWrite(6, HIGH);
    delay(0);
    var = 2; }
    
    { delay(3000);
      if (var == 2)
    digitalWrite(6, LOW);
    delay(0);
    var = 3; 
    
    if (var == 3)
    digitalWrite(5, HIGH);
    delay(0);
    var = 4;
    
    if (var == 4)
    digitalWrite(11, HIGH);
    delay(0);
    var = 3; 
    
    {delay(000);
    if (var == 3)
    digitalWrite(11, LOW);
    delay(0);
    var = 3;
  
  
}}}

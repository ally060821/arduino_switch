# arduino_switch

this code is to text switch code

```cpp

void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  pinMode(13,OUTPUT);
  pinMode(3,INPUT_PULLUP);
}

void loop() {
  // put your main code here, to run repeatedly:

  int value ;

  value=digitalRead(3);
  if(value==0){
    //led on
    digitalWrite(13,HIGH);
    Serial.println("LED ON");
  }else{
    //led off
    Serial.println("LED OFF");
    digitalWrite(13,LOW);
  }
}
```

![pig](https://github.com/ally060821/arduino_switch/blob/master/gggggggg.jpg)
![dog](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwitqurnp4fjAhUsyosBHTN2CrQQjRx6BAgBEAU&url=%2Furl%3Fsa%3Di%26source%3Dimages%26cd%3D%26ved%3D%26url%3Dhttps%253A%252F%252Felektronikapadang.blogspot.com%252F2016%252F12%252Fmengatur-terang-lled-dengan-potensio.html%26psig%3DAOvVaw1YE2bkZRsdezDrs0Bt9BlZ%26ust%3D1561644113719869&psig=AOvVaw1YE2bkZRsdezDrs0Bt9BlZ&ust=1561644113719869)

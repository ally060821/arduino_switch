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
![dog](https://www.google.com/search?q=arduino+switch+parts+explain&source=lnms&tbm=isch&sa=X&ved=0ahUKEwibpKaXp4fjAhWvHqYKHUseDZ8Q_AUIECgB&cshid=1561557711826499&biw=1536&bih=754&dpr=1.25#imgdii=Db5giZgyKrTesM:&imgrc=82oPmcJOfGxD0M:)

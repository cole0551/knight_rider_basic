# knight_rider_basic
void setup() {
 for(int x =1; x<14;x=x+1){
  pinMode(x,OUTPUT);
 }// end loop
 }// end setup
void loop() {
  // put your main code here, to run repeatedly:
for(int x=0;x<14;x=x+1){
digitalWrite(x,HIGH);
delay (100);
digitalWrite(x,LOW);

} // end for

for(int x=13;x>0;x=x-1){
digitalWrite(x,HIGH);
delay (100);
digitalWrite(x,LOW);

} // end for
} // end void loop

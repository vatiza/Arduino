# Arduino
# INIARDUINO

Prepares your Ubuntu to arduino by setting the correct permissions and adding the current user to the necessary groups.
Tested on Ubuntu 18.04 and 20.04

### Installation
	$ chmod 0755 install.sh
	$ sudo ./install.sh
	
### Usage
	$ iniarduino


### PIN use
#include <LiquidCrystal.h>;

const int rs = 12, en = 11, d4 = 5, d5 = 4, d6 = 3, d7 = 2;
LiquidCrystal mylcd(rs, en, d4, d5, d6, d7);

void setup() {
// analogWrite(ct,50);
mylcd.begin(16, 2);
mylcd.print("GOBAL SPY HAWK");
mylcd.setCursor(0,1);
mylcd.print("hello bubt");

}

void loop() {


}

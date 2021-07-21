# LEDs Circuit for Robot Eyes
**This Repository will explain my 4th task in Electronics and Electrical Power department at [SMART METHODS](https://github.com/smart-methods) summer training.**

## Task Requirements: 
  - Design a circuit for robot eyes using 2 LEDs and transistor. 

## Detailed Steps:
1. Using 2n2222 transister (NPN) as a switch for the LEDs whcih will help to provide the required power for them.
   - [2n2222 Transistor Datasheet](https://pdf1.alldatasheet.com/datasheet-pdf/view/15067/PHILIPS/2N2222.html).
   - Design steps:
    <p align='left'><img width="50%" src="https://github.com/mo7ammed-saleh/LEDs_Circuit_for_Robot_Eyes/blob/main/Desing%20steps.jpg"/>
    </p>
    
    - Circuit daigram:
    <p align='left'><img width="70%" src="https://github.com/mo7ammed-saleh/LEDs_Circuit_for_Robot_Eyes/blob/main/LED%20for%20Robot%20Eyes%20Circuit%20diagram.PNG"/>
    </p>
    
    - Code using PWM:
    
```c
// C++ code
//
int eysLED=3; // define led pin
void setup()
{
  pinMode(eysLED, OUTPUT); // set as output
}

void loop()
{
  analogWrite(eysLED, 255); //use PWM 
  delay(60); //delay in microsecond
}
```
2. Task is Done :heart_eyes:

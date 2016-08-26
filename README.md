# ArduinoWolves Chrome App 

A chrome app to easily configure the Arduino-Wolves arduino through serial.

# Description 

Arduino Wolves Config Tool is a small panel to ease the configuration of Arduino Wolves, an interactive wood pane part of the exhibition "Loups" of the Musée d'histoire naturelle de Fribourg (MHN).

How to use:
1. connect the Arduino to your computer;
2. open the app;
3. select the correct port in the dropdown (usually /dev/ttyUSBx ou /dev/ttyACMx);
4. click on "connect";
5. configure the arduino as you see fit;
6. click on "apply";
7. click on "disconnect".

The different parameters are:

 - PIN: code used to enter config mode through the remote control.
 - DF: time between the detection of the RFID card and the trigger of the solenoid.
 - DI: duration of the solenoid impulse.
 - colors: colors of the blinking LEDs when they are idle (no feedback).

Developed by Jacques Supcik, Lucy Linder and Damin Goetschi (the BlueMasters).
 - delays: configuration of the blinking (use off=-1 to disable blinking).  

 
# setup and run

This app uses webpack and es6 scripts compiled with babel.

During development, simply run:

```
npm run watch
```

and modify/load the chrome-app. The es6 scripts (with `main.js` as the entry point) will be compiled and bundled into `chrome-app/js/bundle.js`.

                                
                    
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
                                        
# RodentTrapFinal
Program written for a smart rodent trap. Trap is designed to search for its location then continue updating its location until it has detected a rodent activating a pressure plate. Once activated, the trap will close the door and trap the rodent, connect to WiFi, send an email to the user with the trap's location, then await for a bluetooth signal. Once the bluetooth signal is received, the trap will release the rodent and restart the process.

Compatible with Arduino Uno Wifi Rev2 Board, but can easily be converted to work for Arduino Nano Iot 33.
Uses GT-U7 GPS module, compatible with any NEO-6M GPS module

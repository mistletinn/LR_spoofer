This is a script that lets you create a local server on your device that emulates a Lovense Remote server, then translates toy commands and sends them to Intiface Central server.

Requirements: 
Windows
Intiface Central
A game with Lovense Remote integration

Instructions:
  1. Start your Intiface Central server
  2. Use start.bat to initialize the script
  3. At this point Intiface Central should receive connection from LR_spoofer. If that doesn't happen, make sure the script uses correct ip and port for IC. You can edit them in settings.ini or in user interface
  4. Open your game's Lovense Remote integration menu
  5. Input 'localhost' in server ip and '3003' in server port. you can edit used port in settings.ini or in user interface. Connect to the server
     
As of version 0.0.1, the script supports Function and Pattern commands for Lovense Remote, and sends Vibration, Oscillation and Rotation commands to Intiface Central.

Confirmed games it works with:
  Voidbound

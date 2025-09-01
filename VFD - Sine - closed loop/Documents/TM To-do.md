## Sine Closed Loop Dev  
### To-do

- [ ] PID Debug

- [ ] Integrate Current Sensors

- [ ] FOC

### Current Status
- Existing code seems to be missing a lot of features in the other firmwares
- There is no integration with grbl
- I assume this has not been tailored to the application at all
- PID in Trap - Closed Loop did not seem to be functional
- As such, PID Debugging will begin in VFD - Trap - Closed Loop
- The experience learning the hardware will hopefully transfer to building the Sinusoidal code out

### Notes
- JTS was working on a full PWM Sine implementation
- This included notes on harmonic injection, which would be useful for higher peak power
- I am looking into existing FOSS FOC systems to determine how portable they are to this platform
- Board design is using A4910 as a gate driver and current sensor
- I have found no evidence of current sense being implemented in firmware
- I need to document pinouts and grbl integration in a human-readable format
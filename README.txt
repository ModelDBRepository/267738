STEP1 Execute "figure.hoc" file to load the models and session data.

STEP2 Set the impulse current stimulation on "Istim" window.
 - toff = 100 and num = 1 for twitch 
 - toff = 100 and num = 9 for 10 Hz 
 - toff = 49 and num = 17 for 20 Hz 
 - toff = 32 and num = 26 for 30 Hz 
 - toff = 24 and num = 34 for 40 Hz 
 - toff = 9 and num = 61 for 100 Hz 

STEP3 Set the muscle length.
 - Isometric conditions on "Xm" window: 
   amp = 0 for physiological minium.
   amp = 5 for physiological medium.
   amp = 10 for physiological maximum.

 - Isokinetic conditions on "VectorPlay" window:
   Click "Connected" bottom on "VectorPlay[0]" window for step change in muscle length.
   Click "Connected" bottom on "VectorPlay[1]" window for lengthing of muscle length with constant velocity.
   Click "Connected" bottom on "VectorPlay[2]" window for shortening of muscle length with constant velocity.

STEP4 Set the model parameter values on "fast_muscle" window.
 - Initial values were set to the default parameter values for CAT14 presented in Table 1.

STEP5 Click "Init&Run" bottom on "RunControl" window to run the simulation.  
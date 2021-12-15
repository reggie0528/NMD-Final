# NMD-Final
Arduino final project for NMD 211 Lab
Midi Controller

  I am a musician, and I have used midi in a musical context for many years, so learning to construct a midi controller using an arduino seemed like a natural fit for a final project for me. 
  
  My original plan was to use two potentiometers and a joystick (which is basically just another two potentiometers) to play two pitches (one for each potentiometer) and affect the pitch bend and modulation with the joystick. 
  
  The only part I got working to my satisfaction in time were the two potentiometers playing pitches in time, demonstrated in the video. 
  
  As you can see in the video and the pictures, I still incorporated the joystick into the design of the controller, and wired it into the arduino as well.
  
  I have omitted the joystick from the wiring diagram, as it makes it a lot more readable, and is unused in the code.
  
  Instructions:
  - To set the midi controller up on your computer, you must download the programs loopMIDI and hairless MIDI Serial Bridge, the links to which are included in the repository, and a DAW (any DAW will work, I used Ableton 11).
  - Open loopMIDI and create a new port using the + button.
  - Open Hairless MIDI Serial Bridge. 
  - On the left, there is a dropdown menu under the Serial port label. Select COM# (# being the number of the port you are using). 
  - On the upper right, under MIDI Out, select the loopMIDI Port you have created.
  - Open your DAW, and navigate to the midi devices. You should see a device called loopMIDI port. make sure it is active, and that you are recording midi data in the daw.
  - When you connect a midi instrument to the input, the potentiometers will continuously generate notes based upon their positions. A higher value on the potentiometer means a higher pitched midi note is sent.
  The circles in Hairless MIDI to Serial will light up green to confirm that input is being sent.
  
--Reflection--
  
  It is a shame that I didn't get the joystick working as intended, as that could have provided much more sonic variety than what I had. Still, I think my instrument made a very unique sound, and I am very happy with the way it turned out. My understanding of the way midi messages are sent and recieved is information I can see myself using many times in the future. If I were to do this project again, I maybe would buy more potentiometers, so I could map them to even more values. The possibilities are nearly limitless given the number of dials I can add. Experimenting with different methods to send midi messages in interesting ways was very fun!

# Banana-Keyboard
### A 3D printed &amp; hand wired 6 key Arduino keyboard, shaped like a banana.

[ image here soon ]

Inspired by designs I have seen online, such as Dan Bostian's [Banana](https://github.com/dbostian/banana).

### Materials Needed

3D Printed Parts

- [ ] Top Case
- [ ] Bottom Case
- [ ] 3D printed Keycaps (optional)

Electronics

- [ ] Wire (Only about 1m needed.)
- [ ] Arduino Pro Micro
- [ ] 6x Mechanical Switches
- [ ] USB cable
      
Additional Parts

- [ ] 3.5mm cube magnets (optional)
- [ ] Double sided tape


### Assembly

Wire one of each of the switch pins to each other and then to the GND pin on the pro micro.
Then, wire each remaining pin on the switches to data pins on the Pro Micro. I used pins 14, 15, 18, 19, 20, and 21. You can use double sided tape to hold the controller down in the case if it doesnt stay in.

[ image here soon ]

There are small holes on the model meant to fit 2 small magnets to hold the case together, about 3.5mm square. 
If you do not have these magnets you could glue/tape the two halves together, or contact me to update the model at [finnjmasters@gmail.com](mailto:finnjmasters@gmail.com)


[ image here soon ]


### Code

The code is a good starting point for handwired macropads (Providing they do not have more switches than pins on the board)
The pins and letters can easily be defined at the top so you can quickly change what it does





For any issues, contact me at [finnjmasters@gmail.com](mailto:finnjmasters@gmail.com)

\* The MIDI code does not work as expected yet, I will need to test more. Or if you can fix the code, please submit a pull request.

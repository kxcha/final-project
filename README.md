# final-project

This project aims to use ultrasonic sensor to create a distance sensing device. When distance between the device and an object is less than 10 inches, the output of ultrasonic sensor triggers the micro servo to vibrate. This project uses https://makecode.microbit.org/. The goal of the project is to let people with normal vision experience what it is like for visually impaired individuals to navigate in a world where accessible infrastructures are lacking. The goal is to help develop empathy among designers, researchers, engineers and anyone whose work will have an impact in the world we live in. By interacting with the final deliverable, the emotional experience evoked by uncertainties and challenges would create conversations that counts on the visually impaired individuals’ struggles and the stigma they face in the process of innovating. Anyone can become visually restricted at different level for however long it may last. It could be a result of aging, disease or restricted conditions in the environment. By recreating a vulnerable experience without users’ anticipation, the project wants to deliver the message that innovation should take a diverse user group into account because users needs and capabilities could suddenly change.

## Getting Started

This project uses https://makecode.microbit.org/ to test and run the code.

### Prerequisites

To asemble the device, you will need the following materials: 1 x BBC micro:bit; 1 x Ks0360 Keyestudio Sensor Shield V2 for BBC micro:bit; 1 x HC-SR04 ultrasonic sensor; 1 x 9G SG90 Mini Micro Servo; 1 x 9V battery; 4 x female/female jumper cables

### Installing

See below for instruction to put the code together in makecode: 
![alt text](https://github.com/kxcha/final-project/blob/master/makecode_instruction.png)

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests
Save the hex file from https://makecode.microbit.org/. Drag the hex file into microbit. 
Place an object (eg. paper box) 1 - 10 inches away from the ultrasonic sensor (note: ultrasonic sensor can detect 0.79 inches minimum). The micro servo should vibrate when the object is in this distance range. When the distance between sensor and object is more than 10 inches, the microbit screen would display a smiley face.

### Break down into end to end tests
Test if the device can detect and display distance: place an object (eg. paper box) 1 - 10 inches away from the ultrasonic sensor (note: ultrasonic sensor can detect 0.79 inches at minimum). The microbit should display the distance between sensor and object in numberic value.
![alt text](https://github.com/kxcha/final-project/blob/master/distance_sensing_test.png)

Test if the distance in the range 1 - 10 inches between an object and ultrasonic sensor can trigger the micro servo to vibrate. hen the distance between sensor and object is more than 10 inches, the microbit screen would display a smiley face.
![alt text](https://github.com/kxcha/final-project/blob/master/final_makecode.png)

## Deployment

The participant for this project is asked to navigate through a 52 inches wide and 296 inches long hallway, while being blindfolded.  Before the participant enters the hallway, he/she is asked to wear a wrist support attached with a distance sensing device attached to the left and right hand respectively. Each device is composed of a microbit, a ultrasonic sensor, a micro servo, and a 9V battery. The device is previously programed to trigger the micro servo to vibrate if the device is no more than 10 inches away from an object. As the device vibrate, participant knows he/she is getting too close to the wall and will manage to adjust his/ her distance from the wall while keep navigating forward in the hallway. The facilitator, myself, follow quietly behind the participant to ensure the participant does not bump into the wall. If the facilitator observe the participant is getting too close to the wall (eg. less than 4 inches away from the wall), facilitator will tap on participant’s shoulder as a signal for the participant to stop moving, and re-adjust participant’s position to continue navigating if necessary.

## Built With

* [Microsoft MakeCode](https://makecode.microbit.org/) - graphical user interface to generate code in Javascript

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors
* **Kexin Cha** - *Initial work* - [UltrasonicDistanceSensing]![alt text](https://github.com/kxcha/final-project/blob/master/final_makecode.png)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Code reference 1: https://makecode.microbit.org/v0/22449-66025-47572-42128
* Code reference 2: http://bbs.yahboom.com/upload/forum.php?mod=viewthread&tid=1366
* Inspiration: http://osoyoo.com/2018/09/micro-bit-lesson-using-the-ultrasonic-module/


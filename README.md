# parametric vex dt
this is a parametric vex v5 drivetrain made in onshape 
<img width="1159" height="765" alt="image" src="https://github.com/user-attachments/assets/a66ec082-a8c2-45f7-ad91-2d51395bff8f" />

the step is kinda useless but its an example of what you could make with ts i guess

heres a link to the onshape where u can copy it and actually use it: https://cad.onshape.com/documents/fcc10fcd2d67ebd42f3eaecd/w/5a6639b34b9e2e7df428ad72/e/26990dc977d7e9a5c356f668

some of the parameters dont make sense or dont work lol but i js made it so i can make drivetrains fast for other robots 

like ive already used this multiple times for override

sum caveats r that it only works with the following rpms: 343, 360, 450, 480, 400

also doesnt work if u tryna do mechanum or X or swerve or anything non-meta

good enuf for me doe

### how to use:
presumably u knopw what parametric design is and how to use it but if not watch this https://www.youtube.com/watch?v=NM0YtGTQnDE and it tells u allat

then just copy the onshape thing and then import it into another one and u can change all the parameters to fit ur needs

| name of option:              | what it do:                                                                                                                                                                                      |
|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| configuration                | config of where the braces are. pretty self explanatory. 2top = 2 top braces, top = 1 top brace, bottom = 1 bottom brace etc                                                                     |
| bottom brace vertical offset | how far off the drive the bottom brace is vertically                                                                                                                                             |
| top brace vertical offset    | how far off the drive the top brace is vertically                                                                                                                                                |
| top brace offset             | how far off the back of the drive the top brace is horizontally                                                                                                                                  |
| top brace 2 offset           | how far off the back of the drive the 2nd top brace is horizontally                                                                                                                              |
| bottom brace 2 offset        | how far off the back of the drive the 2nd bottom brace is horizontally                                                                                                                           |
| width                        | width of the drive in holes (0.5in increments)                                                                                                                                                   |
| length                       | length of the drive in holes (0.5in increments)                                                                                                                                                  |
| bottom brace offset          | how far off the back of the drive the bottom brace is horizontally                                                                                                                               |
| funnel                       | how big of a funnel the drive has at the front of the drive. ie 1 means that the inner c channels will be 1 hole smaller than the outer ones                                                     |
| stack                        | whether or not to have one of the motors be stacked. assumes all motors are the same and where u want it so if its wrong u gotta change it manually                                              |
| wheeloffset                  | how far the front wheel is from the back of the drive in holes                                                                                                                                   |
| wheel hole                   | whetehr the wheel is on the top or bottom hole of the c channel. i think its reversed tho idk why                                                                                                |
| back funnel                  | funnel but for the back. odnt use this tho its like fucked                                                                                                                                       |
| motors                       | whether or not to supress the motors. if u turn it on then u gotta hide the extras tho                                                                                                           |
| gear ratio                   | the gear ratio between the powered gears and the wheels. its not actually ht e gear ratio tho its just the resultant rpm on the wheel gear if its a 600rpm motor but it represents the ear ratio |
| wheel size                   | size of the wheel lol... in inches                                                                                                                                                               |
| front idlers                 | number of idle gears in the front of the drive                                                                                                                                                   |
| back idlers                  | number of idle gears in the back of the drive                                                                                                                                                    |
| wheels                       | number of wheels per side of the dt                                                                                                                                                              |
| motorconfig                  | direction the motors are facing                                                                                                                                                                  |



### demo:
heres me showing sum random parameters (i chose sum weird ass numbers idk why i made it 1 wide or 10in vert offset lol)

https://github.com/user-attachments/assets/e0e8ec99-2a4b-4a27-99cb-2522b9b208ac

##### The site was built for [HCTG](https://game.hackclub.com/)

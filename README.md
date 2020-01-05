# Electronics Projects Portfolio

This page is dedicated to sharing the various electronics projects i have designed and built over my years of experimenting.

## My First Circuitry - Darlington Touch Switch

The first circuit i built was a basic Darlington Array based touch switch. This switch was operated by touching two metal contacts at the same time, thus turning on a light or other load. This project was a great intro to the basics of electronics as it taught me the workings of a very important circuit in electronics all with simple physical components.

![image](https://user-images.githubusercontent.com/52514038/71786329-2852de80-2fbf-11ea-83c6-b5cd14f464f4.jpg)


## Up-Cycled 3D Printer(Unfinished)

I have torn apart many PCs throughout my time salvaging and experimenting with electronics and I ended up with a plethora of discarded CD/ROM drives. I began wondering what I could do with these drives other than just ripping out the lasers and throwing the rest in a pile. I started to research some options and the most common use I came upon was using the stepper motor driven laser carriages as the axis for a mini 3D printer.

![image](https://user-images.githubusercontent.com/52514038/71785816-1706d380-2fb9-11ea-9bad-8cadb76c9f82.jpg)

I started out by measuring the CD drive motor carriages and designing frame pieces in a CAD program.

Img(CAD design)

I then attached the carriages and assembled the frame parts. I fabricated the bed from a small piece of MDF that I covered in aluminum foil tape to give a smooth impervious surface to print the plastic on.

Img(Bed attached, frame assembled, Etc.)



## Pellet Stove Daughter Board Repair

My parents have been using a pellet stove to heat their home for quite sometime now and after hundreds if not thousands of times being switched on and off, the buttons on the control panel started to work less frequently.
![image](https://user-images.githubusercontent.com/52514038/71785991-461e4480-2fbb-11ea-80ef-3061ef8bfe5e.jpg)

My Dad had priced out a new board from a local dealer and when he heard the nearly $200 price tag for the glorified slab of fiberglass, he came to me to fix it. 

![image](https://user-images.githubusercontent.com/52514038/71785910-06a32880-2fba-11ea-8eeb-2fabcc9ef642.jpg)

Luckily there was a button that my dad never used on the board so the procedure was relatively simple. I desoldered both of the SMD momentary switches, the broken on and off switch and the one that had never been used.
![image](https://user-images.githubusercontent.com/52514038/71785963-aeb8f180-2fba-11ea-8d34-17ca73b1cfa4.jpg)

I cleaned the solder pads with isopropyl alcohol and prepped them for soldering with a light dab of solder paste. Then from there I swapped the SMD switches and resoldered them into place on the board.
![image](https://user-images.githubusercontent.com/52514038/71786040-fa1fcf80-2fbb-11ea-879a-b4e08f1562db.jpg)
![image](https://user-images.githubusercontent.com/52514038/71786041-fa1fcf80-2fbb-11ea-8270-df7bfe0d07ae.jpg)

I then reinstalled the board into the stove and it turned on no problem. A relatively quick fix to save nearly $200. 

## Full Size 3D Printer Project(unfinished)

I've had the ambition to build a 3D printer ever since I first read of the concept some years ago. Since then, I've made various failed attempts due to lack of resources. However I eventually found the perfect versatile construction material and it turned out to be rather cheap and effective. Puttering around my Dad's workshop one day I stumbled across some old aluminum balusters I was debating for weeks what I could use them for, then the idea came back into my head of building a 3D printer.

I constructed a basic frame with the balusters in which to mount the electronics and gantry components.
![image](https://user-images.githubusercontent.com/52514038/71786157-7666e280-2fbd-11ea-8533-2e542b54d095.jpg)

For the rails to guide the different axis I used hot rolled steel rods that I wet sanded with a high grit sandpaper in order to gain a smooth sliding surface.
![image](https://user-images.githubusercontent.com/52514038/71786209-b7f78d80-2fbd-11ea-89d4-91b0f6f66dee.jpg)

I then made a basic bed design for the printer again with the balusters and mounted bushings to allow it to slide along the gantry rails.
![image](https://user-images.githubusercontent.com/52514038/71786208-b7f78d80-2fbd-11ea-9a59-6924cb9045e6.jpg)

I purchased a specialized 3D printer arduino and stepper motor kit off amazon for the guts of the printer. I began playing with that to learn the basic functionality. 
![image](https://user-images.githubusercontent.com/52514038/71786207-b7f78d80-2fbd-11ea-9425-a42de1e4d8da.jpg)
![image](https://user-images.githubusercontent.com/52514038/71786206-b7f78d80-2fbd-11ea-909c-e1b3aeff4a88.jpg)

From there I mounted one of the stepper motors to the frame and used a crosby clamp to cinch the belts for the stepper motors to the bottom of the bed and with that, the X-axis was essentially finished.
![image](https://user-images.githubusercontent.com/52514038/71786205-b7f78d80-2fbd-11ea-8077-4d648fe192dc.jpg)

The next step was to create the drive train for the Z-axis. For this I used threaded rods and two more of the sanded gantry rods I made. At a local shop, I machined parts to attach the threaded rods to the stepper motors, these were just basic aluminum rods lathed to size and with holes on either end to accompany the to sizes of rod that they would secure.
![image](https://user-images.githubusercontent.com/52514038/71786204-b7f78d80-2fbd-11ea-989d-ef137899436a.jpg)

With those parts finished I mounted the gantry rods to the frame with basic angle hardware from the hardware store and attached the threaded rods to the stepper motors with the parts I had machined.
![image](https://user-images.githubusercontent.com/52514038/71786203-b75ef700-2fbd-11ea-970c-3af1a1015e46.jpg)

I then needed some kind of tapped bushing part that would thread onto the vertical rods and slide on the gantry to keep it aligned. I pondered a few ideas then decided I would use machined plastic as the specialized part I needed. Due to my lack of a place to buy plastic without a 3 hour drive I decided to improvise and use a cutting board as my source of high density polyethylene. I chopped the cutting board with a band saw into 1” x 2” pieces to use as the bushings. Then I measured the distance between the two vertical rods of the Z-axis and carefully drilled 2 holes in the bushings so they would glide smoothly and tapped one of the holes to accompany the threaded rods. 
![image](https://user-images.githubusercontent.com/52514038/71786182-9e564600-2fbd-11ea-9489-0d157ab35b48.jpg)

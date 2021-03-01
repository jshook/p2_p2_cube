# Printing your Parts

We want the P2 P2 cube frame to be fun to build, flexible for experimentation, and relatively durable. As such, the 3d models were refined and tested to ensure that you can reliably print the frame without any supports!

Generaly speaking supports are hit or miss depending on the filament and/or printer features. Dialing in the right settings so that they are effective yet easy enough to take off is difficult even with really good printers. With flat parts, even more so. So, to keep things simple we avoiding requiring supports at all All of the parts were designed to have 45 degree overhangs at most. Most 3d printers can handle this with minimal effort.

A heated build plate is recommended. That is how these parts were tested. However, if you do not have a heated build plate, you can opt for rafts, but this may not yield the best results.

Most of the parts will work well enough with .2 mm layer heights. However, if you want to make assembly particularly easy, it is best to print the fasteners with .1 mm layer height. The first prototypes were printed using the adaptive layer height feature of Prusa Slicer, and results were generally very good with this. It also cut down on printing time.

It takes time to print. Try not to rush things with thick layer heights. It is recommended that you use .2 mm layer height for the plates, and .1 mm layer height for the joints to ensure that the tolerances are close enough for easy assembly. You may be printing things for a couple days, but if you are a seasoned 3d printer user, you know this goes with the territory. If you are eager, you can start printing the frame before your other parts arrive! 

You will have to glue a few things. It was considered an acceptable trade-off to require a minimal amount of gluing in stragegic places rather than have to fight with pulling supports off of flat faces and ruining the finish.

## Printing without Supports

Each of the printable parts is shown in the [README.md](README.md) as a preview. The provided images make it easy to see how to orient the parts on the build plate so that the correct face is down for printing. This ensures that the planar faces are finished nicely and that there are effectively no overhangs more than 45 degrees.

You can use the _place on face_ (F key) feature in Prusa Slicer to click the bottom face of the parts to orient them as shown.

## Using the combined model

The two biggest parts in the print are the face plate and the PCB liner. You can either print 6 of each separately, or you can use the combined model. You only need 6 face plates and 6 liners no matter how you decide to print them. 

## Testing for Accuracy

Before you print the whole model, you will want to ensure that your printer is printing parts accurately enough. If you want to do this in detail with the actual LED PCB panels, do thie following:

1. print a single face plate (or combined face plate and liner)
2. Carefully remove a LED panel from its stock plastic frame
3. Align the two and shine a light through the screw holes.

If the LED PCB doesn't align to the plastic frame, then you will need to 
do some calibration and testing on your 3D printer before continuing. 
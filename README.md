# The Carrot Fan
![Carrot fan](https://i.imgur.com/ggtUthN.jpeg)

Making an ordinary mini fan from Amazon into a work of art.
A project by me, cervidwithmoped.

## Foreword
This is my first proper write-up on GitHub! While I plan on structuring this report like a scientific paper, don't expect any formalities. This was just a fun little project I did in free time that I'm just now deciding to write about and post. Also, I'm a human. Who wrote this. Because I wanted to. 

__None__ of what you are about to read (nor the files I have added to this repo) were created with AI. Additionally, I have attached the files of the project to this repo for research purposes but __I do not give permission to anyone to sell these designs.__ You can print them out for personal use all you want, but I put a lot of hours into this and I plan on selling these down the line. Now that's out of the way, shall we begin?

## Introduction
As defined by Wikipedia, the furry fandom "is a subculture interested in anthropomorphic characters", and many people in the furry fandom own "fursuits" (sorta like the costumes that you see mascots at sporting events wear, except completely custom-made). I'm a furry, and plenty of my friends are as well. If you've never heard of us, well, now you have.

In January 2024, a friend of mine tweeted about wanting a fursuit mouth fan in the shape of a carrot (after all, his "fursona" is a hare, so a carrot fan would be both fitting and functional for him and his future fursuit). After a while, fursuiting can become incredibly taxing on the wearer, and there have been plenty of documented cases of fursuiters passing out due to heat stroke, especially at furry conventions. Nowadays, many fursuiters opt to bring a mini fan -- with a footprint not that much larger than a smartphone -- that they can wear on their necks to be able to cool them off.

I wanted to surprise my friend with a carrot-shaped fursuit fan, so I took the tweet as a challenge!

## Methods
Hardware used: 
- A $15 portable neck fan I found on Amazon
- Digital calipers
- Bambu Lab P1P 3D Printer
- Sunlu PLA+ filament (orange, green, and red)
- Soldering iron
- Hot glue
- VHB tape

Software used:
- Adobe Photoshop CC
- Tinkercad
- Bambu Slicer

My friend doodled some ideas. We kicked around the viability of maybe making a cactus/nopal fan (hence the second row of drawings), but we both agreed that the carrot would be the way to go. We also agreed that a more rounded-off design (top row, option 2) would be the way to go since there would be less sharp angles to touch and there would be less force exerted on the final product if it were ever to be dropped.

![Carrot fan doodles](https://i.imgur.com/SyCwyyO.jpg)

I got to work on Photoshop, making a black-and-white drawing of the carrot. This was done so I could export it as a .PNG, convert it to a .SVG, and drop it right into my CAD software of choice, Tinkercad. Sure, my 2D-to-3D design flow may be a little unorthedox and Tinkercad might be best suited for high school design classes, but that's just what I'm used to. With the basic outline of the carrot fan brought into Tinkercad, I extruded it upwards to create a 3D object.

![Carrot fan Tinkercad](https://i.imgur.com/p5BmNJJ.jpg)

I then hollowed out the inside of the carrot to house the electronics, placing a mockup of each component into the cavity. A set of digital calipers were used to measure everything to ensure a (nearly) perfect fit.

![Mockup Tinkercad](https://i.imgur.com/hwUKucQ.jpg)

The electronics were pulled from a generic neck fan I found on Amazon. The guts were nothing special: a small blower fan, a standard 18650-style battery, and a small control board. Mounted onto the control board was a small LED display to show the fan's speed mode and device state of charge, as well as a momentary switch to turn on/off the device and change speed modes. I printed the prototype out and placed everything inside as a test fit.

![Real](https://i.imgur.com/HHGIpUT.jpg)

Everything fit, but there needed to be a few changes made to the design. Most notably, the air chamber at the top of the enclosure had far too many slots for the air to escape, resulting in a less-than-optimal flow of air. Additionally, the battery and fan kinda just sat there and slid around, and the circuit board's LED screen stuck out like sore thumb past the side wall of the enclosure.

I first wanted to tackle the circuit board and fan issues. To deal with this, I opted to build two subassemblies: a mount for the cicuit board (yellow) and a mount for the fan motor (blue). These subassemblies were designed separately due to their complexity and were later added into the final print. Later iterations of the circuit board subassembly would go on to include a cutout for the board's USB-C charging port and a separate button that would make contact with the tiny momentary switch to prevent the user from having to touch the circuit board itself. This button system -- by far the most complicated but satisfying model I had designed to date -- sat flush on the bottom of the carrot. It also made it easier to operate the device while in fursuit, since it's hard to press tiny buttons with paws!

![Subassemblies](https://i.imgur.com/eE7Eqlu.jpg)
![Subassemblies added](https://i.imgur.com/KfDJ25V.jpg)

Another prototype later proved that everything fit pretty well. All that was left was to do was design a top cover with some space for air to enter the fan chamber. 

![Cover](https://i.imgur.com/NLkkZo1.jpg)

With the final design completed, I sent the file to the printer and let it run.

## Results
![Final](https://i.imgur.com/SMZHbRr.jpeg)

This thing is tight.

Essentially, the final product is the same fan as before, just with a different housing. Sure, I didn't design it from the ground up, but I used what I had immediately available to me and I learned some valuable lessons along the way. The button system was also my first mechanically-functional thing I designed too, so that was cool.

![Button subassembly](https://i.imgur.com/3G54uoj.png)

If you're wondering, this is what my friend had to say about seeing the final product. Safe to say that he liked it. :)

![Swag](https://i.imgur.com/TOgUH0V.png)

## Discussion
Admittedly, there were a lot of things I could have done differently or flat-out done better that are under consideration for V2. The different-colored parts of the enclosure relied on a hole-and-pin system to connect together since I could only print with one color at a time. The solution to this would be the Bambu Lab AMS ("Automatic Material System") that allows for multicolor printing, but that's $350 and that's not money I'm really willing to spend right now. I also want to use proper nuts and bolts to attach everything together for V2, since the over-reliance on the pins and hot glue add points of failure should the carrot be dropped.

Overall, this was a super fun project to work on! My friend really liked it and it'll keep him cool once his fursuit comes in.

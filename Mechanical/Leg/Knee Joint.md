# Knee joint

This file is talk a bit more in detail about how I'm going to make the knee joint move. So keeping the knee servo motor closer to the main body will help a lot with putting less weight on the hip
servos. But now we have a problem if we move that motor there, then how will we turn the knee? So we will a couple options.

---

## Linear Motion

I could make the turinng into a linear force and make that turn the knee. Although this is very precise and also used by Boston Dynamics Robot Dog Spot, I don't think this will be a good fit for me
since it will be pretty heavy which will be demanding on the motors and It is pretty expensive. Other cons is that it might be a bit complicated and hard to CAD for me.

## Belt

I think I'll use a timing belt to transfer the motion. It'll have to be very tight so that it won't slip out. This option is a lot less complicated and more light weight than the other one. It 
does lose a bit of precision though. But I won't be needing as much precision as Spot since mine won't be doing backflips and stuff like that.

## Sources used

This one was very detailed and useful: https://journals.sagepub.com/doi/pdf/10.1177/1729881419844148

I also ued some of the old sources from the Inital Design document

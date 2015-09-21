
#K_{Stairs}

**Category:** Web
**Points:** 100
**Description:**

http://54.152.84.91

##Write-up
Hitting the site, we are welcomed with the following site:

![Image of site]
(./Images/home.tiff)

Immediately we register and start looking around.

![Image of registration]
(./Images/register.tiff)

So, straight off the bat we notice that we were given 3 tokens for registering to play and that their appears to be DLC content available to help us in our conquest.  After a lot of playing around and throwing things (the site was very slow and buggy at times) we noticed that if you register and then just logout and re-register it aggregated your tokens.

![Image of tokens]
(./Images/tokens.tiff)

During our recon we also noticed a hidden compass that said it costs 100 tokens.

![Image of hidden compass]
(./Images/hidden.tiff)

We wasted a lot of time here trying to buy this token by changing the ```bid``` parameter to ```4```, as we thought perhaps it would give us an upper hand while actually playing the game.  No matter what we did we were always greeted with the ```nO-oP``` message.

![Image of bid]
(./Images/bid.tiff)

![Image of nO-oP]
(./Images/noop.tiff)

Before you comment on the number of tokens being shown above while trying to purchase a ```100``` compass, these images were taken after the fact.  We had closer to ```200``` tokens available while testing and were never able to purchase this item.  So moving back to collecting tokens.  After we finished registering enough users, we went ahead and purchased the ```10``` token compass, a bunch of food, and headed off on our quest.

![Image of compass]
(./Images/compass.tiff)

The compass basically was boolean in nature.  It would only tell you if you were going the right or wrong direction.  We took the approach of heading one direction until it tells us that that is no longer the correct direction and then turn and head the way the compass tells us.  Eventually we wind up finding a staircase.

![Image of stairs]
(./Images/stairs.tiff)

Heading up the stairs kills us, but only after revealing the flag.

![Image of flag]
(./Images/flag.tiff)

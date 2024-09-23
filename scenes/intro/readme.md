Background is 7 screens in height (1680px).

Camera starts at the very top of background.png. It scrolls a total of 1440px initially over a period of 8.5 seconds to rest 240px above the bottom, come to a temporary stop above the earth.png and moon.png. Those 8.5 seconds are broken down as:

.5s blank

3s - logo.png fades in, holds, and fades out

.5s blank

3s - account.png fades in, holds, and fades out

.5s blank

1s - Book of Chad fades in (title.png fades in 0, 1, 2)

earth.png and moon.png appear from the bottom and rest below the title when the camera stops

3s - full title (including "Another Testament...", e.g. title.png frames 3, 4, 5) fades in, holds, and fades out (title.png frames 4, 3, 2 - "Book of Chad" remains)

earth.png and moon.png move straight down out of camera shot.

camera scrolls down once again to the very bottom of background.png

the red moon comes into frame above the mountains (part of the background.png now as it's always static)

temple.png scrolls up slightly whilst the camera is scrolling down (for vertical parallax) to rest with its bottom flush with the bottom of background.png

start.png & options.png both fade in at the bottom left of the screen in the empty space beside the temple & below the mountains

selector.png spawns to the left of start.png

It's likely I'll have to make the background taller if the scrolling is too slow.

assets not used: moon_red.png & background_2_screens.png

If we can fit it in, we can consider adding meteorites impacting earth all around you. meteorite_s.png = small, _m = medium, _l = large, _xl = x-large. I imagine randomized spawning points on screen, randomized sizes, and randomized impact spots on the ground in the background. explosion_s.png is for small meteorites, _m is for medium, _l is for large and x-large.

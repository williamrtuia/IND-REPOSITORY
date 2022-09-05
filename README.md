# IND-REPOSITORY
include image
background = rectangle(300, 200, "outline", "black") 
redsquare = rotate(135, square(200 * num-sqrt(2), "solid", "red")) 
blackstripe = rotate(135, rectangle(500, 62, "solid", "black")) 
trinidad-flag =   
put-image(blackstripe, 150, 100,
put-image(redsquare, 0, 0,
put-image(redsquare, 300, 200, background)))

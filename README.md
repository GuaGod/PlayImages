# PlayImages
It is a jQuery plug(It is a very easy project)
It maybe need some HTML structure

configure:1.method:It control the way of how to play the image,now it have two method:flash and fade:
          2.time:It control the time of the interval bewteen the image and the next;
          3.animateTime:If your method is about animate,the animateTime will control the time required for each action to complete;
          4.navlist:If you choose the 'true',It will provide a navigator for your HTML element,but you need some HTML structure first;
          5.turnButton:If you choose the 'true',It will provide a button to switch the image,but you need some HTML struture first;
          6.imgClass:It represent your class of image;
          7.leftClass:It represent your class of button which to control images' index reduce;
          8.rightClass:It represent your class of button which to control images' index increse;
default:imgClass:"swap",
       	method:"fade",
       	time:2000,
       	animateTime:0.35,
       	navlist:false,
       	turnButton:false,
        leftClass:'turnLeft',
        rightClass:'turnRight'.

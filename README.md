# Jamie's Fork of ckeditorfa6
This is a fork of ckeditorfa6, [original repo](https://github.com/ed3/ckeditorfa). 

https://youtu.be/6OUS7INrdRw
https://i.imgur.com/2drRiHz.png

### Fork
PS: Customise the /icons folder to set an icon, name your icon ckeditorfa

when a colour is chosed, a class is appended to the icon, one of the following classes:
- color-brand-primary
- color-brand-success
- color-brand-info
- color-brand-warning
- color-brand-danger

so to assign a colour to the class, put into your css file:
.color-brand-x {
   color: color;
}

### Info
fa6

### Setup
1. add the cdn of all.min.css to your html page, see example
2. add in your config.js from ckeditor folder:
   config.extraPlugins = 'ckeditorfa';  
   config.allowedContent = true;  
   config.contentsCss = "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css";  
CKEDITOR.dtd.$removeEmpty['span'] = false;

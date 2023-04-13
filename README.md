# Jamie's Fork of ckeditorfa6
This is a fork of ckeditorfa6, [original repo](https://github.com/ed3/ckeditorfa).

### Fork
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
1. add the fa file of all.min.css to your html page
2. add in your config.js from ckeditor folder:
   config.extraPlugins = 'ckeditorfa';
   config.allowedContent = true;
   config.contentsCss = '/{your_path}/all.min.css';
CKEDITOR.dtd.$removeEmpty['span'] = false;
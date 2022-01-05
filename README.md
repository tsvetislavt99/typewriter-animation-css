# Typewriter Animation made with CSS3

The animation uses the `::before` and `::after` pseudo elements. It is composed of 2 animations:
- `typewriter` - The animation moves left until it gets to `left: 100%;` 
- `blink` - The animation changes the background from `transparent` to a solid color, which creates a blinking effect.

Requirments:
- In order for the animation to work you need to use a `monospace` font

CSS Variables:
- `--bg-color: hsl(49 37% 94%);` - Background color
- `--typewriterSpeed: 3s;` - Duration of the type animation
- `--typewriterCharactersHeading: 20;` - Number of characters in the Heading
- `--typewriterCharactersSubTitle: 24;` - Number of characters in the Sub Title

Preview of the Typewriter Animation: 


![Preview of the animation](https://github.com/tsvetislavt99/typewriter-animation-css/blob/master/AnimationGIF.gif?raw=true)



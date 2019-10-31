# Report about the problems on the page and how they should be fixed

### Problems with images
The div with class 'logo' and 'hero-banner' needs to have an alt text written inside the double quotes in the html file. This would display in cases where the image doesnt display
```
alt = "describe the image here"
```
### Problems with the font
Font family for CSS file should have a fall back font before the generic font. Use the font-family below to render the hmtl more accessible
```
font-family: "Roboto", arial, sans-serif;
```
The text wrapped with the div class 'details' needs to be styled to be more legible. Apply font-weight: bold;
```
font-weight: bold;
```
Apply text shadow to the h and p tags under the div 'hero-banner'. This will make the text on the image to be readable
```
h1 {text-shadow: 0.2rem 0.2rem red;};
p {text-shadow: 0.2rem 0.2rem red;};
```
Font sizes on the html file should be scalabe and relatively matched. Use rem or em instead of px for better scalability

The font color on the image should have nice contrast with the color of the image. See example below
```
color:Blue;
```

### Footer
Add padding to footer text
```
padding: 2px;
```

### Border
The 'dt' and 'dd' tags should have a border around them
``` 
dt,dd {
    border: 2px,solid,black;
}
```

## Form
- The form should have 'button' for submission
- The form should have a label

## Links
- Use display flex for links at the top. For example:
```
display: flex;
flex-direction: column;
```
- Social media links at the bottom should redirect to the page created for the Dinosaur and not redirecting to the default home page of that social network. For example (assuming the page created had a name 'dinosaurs')
[youtube](https://youtube.com/dinosaurs)
or edit the hml file ``` <a href="www.youtube.com/dinosaurs/" ```

### Media Querries
The use of media querries is encouraged for accessibility on other devices like mobile phones and tablets
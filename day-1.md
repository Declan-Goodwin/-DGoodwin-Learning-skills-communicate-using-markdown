# Daily Learning //(Heading 1 Format)
## Morning Planning
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
## Review 

Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)
```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```

## Unordered Lists //(Heading 2 Format)
- Format A: List Item 1
- Format A: List Item 2
- Format A: List Item 3
* Format B: List Item 1
* Format B: List Item 2
* Format B: List Item 3
+ Format C: List Item 1
+ Format C: List Item 2
+ Format C: List Item 3

## Ordered Lists //(Heading 2 Format)
1. Step 1
2. Step 2
3. Step 3

## We Love Code
```bash
git clone https://github.com/skills/communicate-using-markdown
```

```js
var myVar = "Hello, world!";
```
## Pictures are good too
Relative URL =  link to a file in the respository
Absolute URL = link to anywhere on the internet (be careful, it's spooky out there)
### What the Hell HTML
- The **alt** field specifies the alternative text.
- The **src** field specifies the source url of the image.
- A **width** and/or **height** field can be used to specify the size in pixels.
- The **align** field allows setting a position **(left, right)**
- How we comment stuff out in this wild world:<!-- This is how we hide stuff that's just for us to know about -->

<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="right">
<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="left">

<!-- <img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="middle">
<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="center"> -->

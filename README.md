<h1> # Frontend Mentor - Single price grid component solution </h1>

<p>This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).</p> 
<p> The challenge consisted of replicating the static jpg design using CSS and HTML. By the end of the challenge, the user should be able to view the optimal layout for the component depending on their device's screen size and see the hover state on desktop for the Sign Up button.

<h2>Desired Outcome</h2>



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**



<h2>Learning Log</h2>
<h3>19oct2021 18:00</h3>
<p>Started the challenge using the static .jpg as a guide. I'm going to try and tackle this using only FlexBox for it is what I'm most familiar with. However, I think it should have been solved using Grid, but I haven't learned grid yet.</p>
<h3>19oct2021 19:00 </h3>
<p>At first, everything was going great. I built the whole layout for the desktop design with flexbox and it worked just fine. I hade one problem which was I couldn't, for the life of me, make the container border round!? Even though I have managed it just find in previous challenges/assignments/designs, for some reason it was most <em>NOT</em> working on this challenge.  If I apply the CSS border: solid red on everything, it shows me the bordes rounded.... maybe I have to round the .first-section container? Haven't tried that yet... But it doesn't seem logical to me. I'm going to try that anyway.</p>
<h3>19oct2021 19:15 </h3>
<p>Applying the border-radius to the .first-section solved the rounded border problem! I think I know why it didn't work: the .first-section sits <em>on top of</em> the .container, so the border <em>was</em> rounded, I just couldn't see it. I'm packing it for today and work on mobile responsiveness tomorrow.</p>
<h3>20oct2021 10:30</h3>
<p> While making the page resposive for mobile, I encountered a problem which I can't seem to find a solution! The .second-section doesn't align with the first one when squeezed into a small screen. At this point, I keep thinking will only be able to solve it with grid, for a have tried a couple of diferent css properties and nothing seems to work.</p>



To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

I want to explore more of CSS grid. Also, I want to learn an framework, like Bootstrap.

### Useful resources

- [CSS Grid Course](https://www.youtube.com/watch?v=t6CBKf8K_Ac&t=465s) - Great CSS Grid tutorial by freeCodeCamp.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@jathibaye](https://www.twitter.com/jathibaye)

## Acknowledgments

<ul>
<li>Thanks to my husband who supports me and cheers with me whenever I get something right!</li>
<li> Thanks to my friend Andŕe Calil who has been my mentor during this path. </li>
</ul>
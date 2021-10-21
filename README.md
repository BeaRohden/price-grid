 # Frontend Mentor - Single price grid component solution 

<p>This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).</p> 
<p> The challenge consisted of replicating the static jpg design using CSS and HTML. By the end of the challenge, the user should be able to view the optimal layout for the component depending on their device's screen size and see the hover state on desktop for the Sign Up button.

<h2>Outcome</h2>
<img src="desktop-solution.png">
<img src="mobile-solution.png">


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup;
- Pure CSS;
- Flexbox;
- CSS Grid;

### Learning Log
<h3>19oct2021 18:00</h3>
<p>Started the challenge using the static .jpg as a guide. I'm going to try and tackle this using only FlexBox for it is what I'm most familiar with. However, I think it should have been solved using Grid, but I haven't learned grid yet.</p>
<h3>19oct2021 19:00 </h3>
<p>At first, everything was going great. I built the whole layout for the desktop design with flexbox and it worked just fine. I hade one problem which was I couldn't, for the life of me, make the container border round!? Even though I have managed it just find in previous challenges/assignments/designs, for some reason it was most <em>NOT</em> working on this challenge.  If I apply the CSS border: solid red on everything, it shows me the bordes rounded.... maybe I have to round the .first-section container? Haven't tried that yet... But it doesn't seem logical to me. I'm going to try that anyway.</p>
<h3>19oct2021 19:15 </h3>
<p>Applying the border-radius to the .first-section solved the rounded border problem! I think I know why it didn't work: the .first-section sits <em>on top of</em> the .container, so the border <em>was</em> rounded, I just couldn't see it. I'm packing it for today and work on mobile responsiveness tomorrow.</p>
<h3>20oct2021 10:30</h3>
<p> While making the page resposive for mobile, I encountered a problem which I can't seem to find a solution! The .second-section doesn't align with the first one when squeezed into a small screen. At this point, I keep thinking will only be able to solve it with grid, for a have tried a couple of diferent css properties and nothing seems to work.</p>
<p><img src="align-problem1.jpg"></p>
<h3> 21oct2021 10:40</h3>
<p> I gave up last night an started again this morning. I fixed my issue applying the flex property to the mobile version and using grid for the desktop version.</p>
```
@media only screen and (max-width:375px) {
    .third-section {
        border-radius: 0 0 20px 20px !important;
            }
    .second-section {
        border-radius: 0 0 0 0;
    }
    .container-grid {
        display:flex;
        flex-direction: column;
    }
    ```

<p>My lastest issue is that, when in mobile,  I don't have margin at the bottom of the container. Can't seem to fix it. Applying the max-height property and using a value of 100% fixes the top margin, but not the bottom.</p>

<h2>21oct2021 10:57 </h2>
<p> Setting the value of margin-bottom from 'px' to 'em' seemes to have fixed the problem. Why didn't using the px value worked? Questions, questions.... </p>

<p> I still haven't gotten the hang of the margins on mobile. Finishing this took me way more time than it should have.</p>


### Continued development

I want to explore more of CSS grid, so maybe my next challenge will be one with a lot of grid. Also, I want to learn how to use Bootstrap.

### Useful resources

- [CSS Grid Course](https://www.youtube.com/watch?v=t6CBKf8K_Ac&t=465s) - Great CSS Grid tutorial by freeCodeCamp.


## Acknowledgments

<ul>
<li>Thanks to my husband who supports me and cheers with me whenever I get something right!</li>
<li> Thanks to my friend André Calil who has offered to help me if I ever needed. Sadly, I'm a masochist who rathers suffer a bit before asking for help. </li>
</ul>
[HTML5 Boilerplate]:https://html5boilerplate.com/
[Skeleton CSS]:http://getskeleton.com/
[Normalize]:https://necolas.github.io/normalize.css/
[Modernizr]:https://modernizr.com/
[Subresource Integrity]:https://www.srihash.org/
[ARIA `role` attributes]:https://www.w3.org/TR/wai-aria/roles
[ARIA cheatsheet]:http://mcdlr.com/wai-aria-cheatsheet/
[WCAG guidelines]:https://www.w3.org/WAI/WCAG20/quickref/
[progressive enhancement]:https://www.smashingmagazine.com/2009/04/progressive-enhancement-what-it-is-and-how-to-use-it/
[broader guidelines]:https://github.com/jpdevries/webguidelines/blob/master/README.md

<h2 id="what">What is this?</h2>

This repo is my current go-to frontend template for [progressively enhanced] projects. I liked the ideas presented in the excellent [HTML5 Boilerplate], but found that it had more than I needed, or implemented features in a different way than I wanted to.

<h3 id="included-assets">What's in it?</h3>

I've borrowed some things from the HTML5 Boilerplate. No point in fixing what ain't broke, etc:

<ul>
    <li>`<!--[if]-->` tags for supporting older versions of IE.</li>
    <li>[Normalize] for consistent CSS behavior across browsers.</li>
    <li>[Modernizr] for progressive enhancement.</li>
    <li>jQuery from a CDN with a local fallback.</li>
    <li>Code to hook up Google Analytics if necessary.</li>
</ul>

But I have also made some different choices to suit my needs and preferences.

<ul>
    <li>[Skeleton CSS] for lightweight responsiveness.</li>
    <li>[Subresource Integrity] on the jQuery CDN link for better security.</li>
    <li>[ARIA `role` attributes] on the HTML5 section tags for better screen-reader compatibility.</li>
</ul>

If I don't have the time or the need to roll my own CSS grid system, I find that CSS is more than enough. It is not overly opinionated about how you should organize your HTML, and it does not offer so many features as to be dizzying to new users; nor does it bring a ton of weight to small projects.

<h3 id="how-to-use">How do do I use it?</h3>

Easy: clone it and start coding! I kept this template intentionally simple so that I (and you, if you use it!) can clone it, change it as you need, and use it at the front of a project quickly and without the hassle of a build process, although you <i>could</i> use this template in more complex projects if you wanted to.

<h3 id="additional-considerations">Some additional considerations:</h3>


You do not have to follow the philosophy of [progressive enhancement], but you should try. I built this template to remind myself to serve HTML5 first wherever possible, because not all users will have good connections or access to JavaScript at all!

Try to keep accessibility in mind! The `role` attributes you see in this repo are only the beginning. Check out this [ARIA cheatsheet] if you are unfamiliar with ARIA and refer to the [WCAG guidelines] to learn other steps you should take toward accessible web architecture. These [broader guidelines]<a href="#disclaimer">	&#42;</a> might be helpful if you are interested in the philosophy of accessbility as much as the how-to.

If you spot any errors in this project or have any suggestions for a better template, feel free to <b>[open an issue](https://github.com/dengeist/template/issues)</b> or <b>[contact me](mailto:eliasjmason@gmail.com)</b>! Your feedback is always welcome!

<hr>
<small>
    <p id="disclaimer">	&#42; full disclosure: I am a co-author of these guidelines.</p>
</small>

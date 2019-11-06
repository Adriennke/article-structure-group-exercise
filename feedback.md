Hello my friend,

I'd get rid of barely every <br> of your code and give style to your <p>s in the CSS.

Instead of the very first <div> I'd use a <header> for example.

You should have just one h1 in your page. I'd change the others for h2

And instead of a bunch of divs for each article, I'd just make a section and put the whole text inside:

<section>
    <h2>...</h2>
    <p>
        ...
    </p>
    <blockquote>
        ...
    </blockquote>

    <h2>...</h2>
    <p>
        ...
    </p>
    <blockquote>
        ...
    </blockquote>

    <h2>...</h2>
    <p>
        ...
    </p>
    <blockquote>
        ...
    </blockquote>

    etc..

</section>


AAAnd try to use relative instead of absolute messuressswhatevever: like % or em instead of px.

have a nice day!
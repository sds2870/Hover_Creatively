# Hover_Creatively

I am creating a hover effect, following along with the tutorial seen here: "https://www.youtube.com/watch?v=I90no1eQ45E&t=31s"

Good day, one and all, and welcome to this documentation of Hover_Creatively. As you know, I followed the tutorial from the above link; but now, I will provide the documentation so that anyone can recreate this effect for themselves. Firstly, we will tackle the HTML.

HTML:

    Now, create your HTML tree using the emmett abbreviation "!". After that, you'll want to add the following "link" tag before the closing head tag. It should look something like this:

     "<link rel="stylesheet" href="style.css">"

    With that in place, it's now time to create your list for the hover effect. Since we don't need numbers, we'll be using the "<ul>" tag. Since we're representing a list of five navigation links that you'd see on a website, the syntax, for now, should resemble this:

    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>

    Now, we need five names for our list items. The ones selected will be Home, About, Services, Team, and Contact. Of course, you can make up your own list, but this keeps it straightforward. Okay, now here's where things get interesting. For our list items, we're not going to simply type the names. Instead, we are going to wrap them in "<a href>" tags. Inside of the opening tag, we will utilize the "data-" attribute to employ the non-breaking space syntax ("&nbsp;") to keep everything orderly. This is how the code should look for each list item:

    <li>
        <a href="#" data-text="&nbsp;Home">&nbsp;Home&nbsp;</a>
    </li>

    You may wonder why there's an "#" for the value of our "<a href>" tag. Well, the reason for that is that we're not linking to anything on the web, so the "#" just serves as a placeholder and nothing more. We also use the "data-" attribute for adding extra info to our HTML without requiring the usage of other "methods". Now, use that for the rest of your list items and it should turn out like this:

        <li>
            <a href="#" data-text="&nbsp;Home">&nbsp;Home&nbsp;</a>
        </li>
        <li>
            <a href="#" data-text="&nbsp;About">&nbsp;About&nbsp;</a>
        </li>
        <li>
            <a href="#" data-text="&nbsp;Services">&nbsp;Services&nbsp;</a>
        </li>
        <li>
            <a href="#" data-text="&nbsp;Team">&nbsp;Team&nbsp;</a>
        </li>
        <li>
            <a href="#" data-text="&nbsp;Contact">&nbsp;Contact&nbsp;</a>
        </li>

    We're almost through with our HTML. Now, it's just the final step: the color.
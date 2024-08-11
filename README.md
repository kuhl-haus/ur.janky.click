# ur.janky.click
Random Dad Jokes webpage that calls https://icanhazdadjoke.com to obtain jokes

View the webpage here: https://ur.janky.click

Read [why I created this site.](https://the.oldschool.engineer/automating-laughter-building-a-random-dad-joke-site-in-an-hour-dc35e0627674)

---

## Calling the Jokes API

Refer to the API documentation here: https://icanhazdadjoke.com/api

Note: If you fork/copy this code, please remove my repo from the [user-agent header](https://github.com/kuhl-haus/ur.janky.click/blob/mainline/index.html#L42-L44).  Thanks!

---

## Hosting

This site is served as a GitHub Page using a custom domain.  I created a `CNAME` record pointing my custom domain `ur.janky.click` to `kuhl-haus.github.io`.


```
dig ur.janky.click.
```
```
;; ANSWER SECTION:
ur.janky.click.         59      IN      CNAME   kuhl-haus.github.io.
kuhl-haus.github.io.    59      IN      A       185.199.110.153
kuhl-haus.github.io.    59      IN      A       185.199.108.153
kuhl-haus.github.io.    59      IN      A       185.199.111.153
kuhl-haus.github.io.    59      IN      A       185.199.109.153
```

Get started with your own here: https://pages.github.com/  
Refer to the documentation here: https://docs.github.com/en/pages

Details about setting up a custom domain here: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

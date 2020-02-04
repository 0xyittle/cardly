# cardyoutube

![](../.gitbook/assets/screen-shot-2020-02-05-at-00.57.27.png)

Feature

Youtube Embed respondsive

* youtube url

HTML

```markup
        <div class="cardyoutube next">
            <iframe src='https://www.youtube.com/embed/mhrkdHshb3E' frameborder='0' allowfullscreen></iframe>
        </div>
```

CSS  \( add to your =&gt; css/components.css \)

```css
/* Start cardyoutube - Youtube Respondsive */

.cardyoutube {
    position: relative;
    padding-bottom: 56.25%;
    height: 0; overflow: hidden;
    max-width: 100%;
    border-radius: 30px;
}

.cardyoutube iframe, .cardyoutube object, .cardyoutube embed {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

/* End cardyoutube - Youtube Respondsive */
```


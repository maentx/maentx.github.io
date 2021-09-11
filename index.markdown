---
layout: default-minimal
---
<style>
img#background-landing-page {
top: 0;
left: 0;
      min-height: 100%;
      min-width: 100%;
width: auto;
height: auto;
display: block;
position: fixed;
          z-index: -999;
opacity: 1;
}
.home {
    text-align:center;
}
.home h1 {
color:white;
      font-family: 'Titillium Web', sans-serif;
      font-size:35pt;
}
#background-landing-page {
top: 0;
left: 0;
      min-height: 100%;
      min-width: 100%;
width: auto;
height: auto;
display: block;
position: fixed;
          z-index: -999;
opacity: 1;
         max-width:none;
}
#avatar-landing-page {
height: 180px;
        border-radius: 100%;
border: 3px solid white;
        margin-bottom: 40px;
}

div.blog-link {
display: flex;
         justify-content: center;
         align-items: center;
overflow: hidden;
}

div.blog-link img {
transition: all 0.4s;
}

div.blog-link img:hover {
transform: scale(1.5);
}

div.blog-link a {
    text-decoration: none;
}

div.blog-link h1 {
    font-size:20pt;
    font-weight:600;
background:gray;
opacity:75%;
margin:0;
}
div.wrapperx {
display: grid;
         grid-template-columns: 1fr;
         grid-column-gap: 5px;
         grid-row-gap: 5px;
}
@media screen and (min-width: 600px) {
    div.wrapperx {
        grid-template-columns: 1fr 1fr;
    }
}
@media screen and (min-width: 992px) {
    div.wrapper {
        max-width: 1000px;
    }
    div.wrapperx {
        grid-template-columns: 1fr 1fr 1fr;
    }
}
</style>
<div class="wrapper">
<div class="home">
<img id="background-landing-page" src="/assets/background-landing-page.jpg">
<img id="avatar-landing-page" src="/assets/avatar.jpg">
<h1>Marian Häntsch</h1>
<div class="wrapperx">
<div class="blog-link"><a href="{{ '/tales' | absolute_url }}"><img src="/assets/home-tales.jpg" alt="https://pixabay.com/photos/blaze-fireplace-bonfire-burn-coal-2178749/"><h1>Tales of a Consultant Career</h1></a></div>
<div class="blog-link"><a href="{{ '/social' | absolute_url }}"><img src="/assets/home-social.jpg" alt="https://pixabay.com/photos/heart-lock-padlock-fence-locked-268151/"><h1>The Social CISO</h1></a></div>
<div class="blog-link"><a href="{{ '/itsec' | absolute_url }}"><img src="/assets/home-itsec.jpg" alt="https://pixabay.com/photos/prison-fence-razor-ribbon-wire-219264/"><h1>IT Security</h1></a></div>
<div class="blog-link"><a href="{{ '/grundschutz' | absolute_url }}"><img src="/assets/home-itgs.jpg" alt="https://pixabay.com/photos/gears-cogs-machine-machinery-1236578/"><h1>IT-Grundschutz</h1></a></div>
<div class="blog-link"><a href="{{ '/dfir' | absolute_url }}"><img src="/assets/home-dfir.jpg" alt=""><h1>DFIR</h1></a></div>
<div class="blog-link"><a href="{{ '/misc' | absolute_url }}"><img src="/assets/home-misc.jpg" alt=""><h1>Misc</h1></a></div>
</div>
</div>
</div>

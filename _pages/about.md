---
layout: about
title: About
permalink: /
subtitle:  <strong>PhD Student working on Dark Matter Galactic Dynamics and conducting Dark Matter searches with <a href='https://www.km3net.org/'>KM3NeT</a></strong>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: # >
    # <p>...</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---


<style>
  /* The theme prints the "news" and "selected publications" headings in lower case.
     These are the only <h2> on this page, so capitalising them here is enough.
     This block only affects the about page — it is inlined into this page alone. */
  h2 {
    text-transform: capitalize;
  }
</style>

<h2 class="plain-title">About me.</h2>

  /* ---- hero band -------------------------------------------------------
     Swap the image by replacing assets/img/hero.jpg (keep the filename), or
     change the path below. Around 2000px wide and dark-ish works best —
     the overlay only darkens further, it cannot rescue a bright photo.
     -------------------------------------------------------------------- */
  .hero {
    position: relative;
    display: flex;
    align-items: flex-end;
    min-height: clamp(200px, 34vw, 320px);
    margin: 0.5rem 0 2.25rem;
    padding: 1.5rem;
    border-radius: 10px;
    overflow: hidden;
    background-image: url("/assets/img/hero.jpg");
    background-size: cover;
    background-position: center;
    background-color: #10161c; /* shows through if the image is missing */
  }
  /* the dark translucent layer — raise the numbers to darken further */
  .hero::before {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(to top, rgba(8, 12, 16, 0.85), rgba(8, 12, 16, 0.45));
  }
  .hero-text {
    position: relative; /* sits above the overlay */
    margin: 0;
    max-width: 26ch;
    color: #fff;
    font-size: clamp(1.15rem, 0.9rem + 1.2vw, 1.7rem);
    line-height: 1.3;
    font-weight: 500;
    text-wrap: balance;
    text-shadow: 0 1px 12px rgba(0, 0, 0, 0.5);
  }
  @media (max-width: 576px) {
    .hero {
      padding: 1.1rem;
    }
  }
</style>
 
<div class="hero">
  <p class="hero-text">Most of the universe is made of something nobody has ever seen.</p>
</div>
<h2 class="plain-title">About me</h2>

I spend my PhD trying to catch it doing something.

I look in two very different places. One is underwater: with the KM3NeT neutrino telescopes, sunk on the floor of the Mediterranean, I look for the neutrinos dark matter would produce if it annihilates. The other is the shape of galaxies, I use the way stellar streams twist out of their plane, and the way rotation curves stubbornly refuse to fall off, to work out how round or how stretched a dark matter halo actually is. Neither approach assumes what dark matter is made of. Both just ask the data.

Day to day this is code and statistics more than it is telescopes, which suits me: I like the moment a plot finally makes sense at 2am and I would not want it any other way.

I also created **Physics Unplugged**, where I write and talk about the dark universe for people who do not do this for a living, on [Substack](https://adriakerr.substack.com) and [Instagram](https://www.instagram.com/physicsunplugged/). I started it because the greatest mysteries of the universe are far too good to keep among specialists and far more approachable than they are usually made to sound.
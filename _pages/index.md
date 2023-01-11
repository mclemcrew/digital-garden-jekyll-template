---
layout: page
title: Home
id: home
permalink: /
---

# Welcome to my digital research garden 🐧

You're probably here for some project updates which can be found [[Project Updates|here]].

If you aren't, you'll find my notes below in various sections. The [[project updates]] will often link to these other notes, which is why they are included here.

<p class="gradient-border" id="box" style="padding: 1em 1em; background: #f5f7ff; border-radius: 4px;">
  If you don't have any idea where you're at, me either, sweetie 🧡
</p>

### Sections

[[Book List| Books]] 📚

[[Research Papers]] 📜

[[Writing]] 🖊️

[[Project Updates]] 🚧

<style>
  .wrapper {
    max-width: 46em;
  }

@import url('https://fonts.googleapis.com/css?family=Raleway:200');

#box {
  color: black;
  font-size: 1.5rem;
}
.gradient-border {
  --borderWidth: 3px;
  background: #1D1F20;
  position: relative;
  border-radius: var(--borderWidth);
}
.gradient-border:after {
  content: '';
  position: absolute;
  top: calc(-1 * var(--borderWidth));
  left: calc(-1 * var(--borderWidth));
  height: calc(100% + var(--borderWidth) * 2);
  width: calc(100% + var(--borderWidth) * 2);
  background: linear-gradient(60deg, #f79533, #f37055, #ef4e7b, #a166ab, #5073b8, #1098ad, #07b39b, #6fba82);
  border-radius: calc(2 * var(--borderWidth));
  z-index: -1;
  animation: animatedgradient 3s ease alternate infinite;
  background-size: 300% 300%;
}


@keyframes animatedgradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}

</style>

---
permalink: /
# title: " Akash Nagaraj"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>

/* Typewriter effect 1 */
/* 3.4186 between frames */
@keyframes typing {
  0.0000%, 52% { content: ""; }
  1%,  51% { content: "C"; }
  2%,  50% { content: "Co"; }
  3%,  49% { content: "Cog"; }
  4%,  48% { content: "Cogn"; }
  5%,  47% { content: "Cogni"; }
  6%,  46% { content: "Cognit"; }
  7%,  45% { content: "Cogniti"; }
  8%,  44% { content: "Cognitiv"; }
  9%,  43% { content: "Cognitive"; }
  10%, 42% { content: "Cognitive A"; }
  11%, 41% { content: "Cognitive AI"; }
  12%, 40% { content: "Cognitive AI R"; }
  13%, 39% { content: "Cognitive AI Re"; }
  14%, 38% { content: "Cognitive AI Res"; }
  15%, 37% { content: "Cognitive AI Rese"; }
  16%, 36% { content: "Cognitive AI Resea"; }
  17%, 35% { content: "Cognitive AI Resear"; }
  18%, 34% { content: "Cognitive AI Researc"; }
  19%, 33% { content: "Cognitive AI Research"; }
  20%, 32% { content: "Cognitive AI Researche"; }
  21%, 31% { content: "Cognitive AI Researcher"; }

  53%, 97% { content: ""; }
  54%, 96% { content: "S"; }
  55%, 95% { content: "So"; }
  56%, 94% { content: "Sof"; }
  57%, 93% { content: "Soft"; }
  58%, 92% { content: "Softw"; }
  59%, 91% { content: "Softwa"; }
  60%, 90% { content: "Softwar"; }
  61%, 89% { content: "Software"; }
  62%, 88% { content: "Software D"; }
  63%, 87% { content: "Software De"; }
  64%, 86% { content: "Software Dev"; }
  65%, 85% { content: "Software Deve"; }
  66%, 84% { content: "Software Devel"; }
  67%, 83% { content: "Software Develo"; }
  68%, 82% { content: "Software Develop"; }
  69%, 81% { content: "Software Develope"; }
  70%, 80% { content: "Software Developer"; }
  /* 1.1395%, 26.2093% { content: "Co"; }
  2.2791%, 25.0698% { content: "Cogni"; }
  3.4186%, 23.9302% { content: "Cogniti"; }
  4.5581%, 22.7907% { content: "Cognitive"; }
  5.6977%, 21.6512% { content: "Cognitive AI"; }
  6.8372%, 20.5116% { content: "Cognitive AI R"; }
  7.9767%, 19.3721% { content: "Cognitive AI Rese"; }
  9.1163%, 18.2326% { content: "Cognitive AI Researc"; }
  10.2558%, 17.0930% { content: "Cognitive AI Researcher"; } */

  /* 30.7674%, 51.2791% { content: ""; }
  31.9070%, 50.1395% { content: "So"; }
  33.0465%, 49.0000% { content: "Softw"; }
  34.1860%, 47.8605% { content: "Software"; }
  35.3256%, 46.7209% { content: "Software Dev"; }
  36.4651%, 45.5814% { content: "Software Develo"; }
  37.6047%, 44.4419% { content: "Software Developer"; } */

  /* 54.6977%, 75.2093% { content: ""; }
  55.8372%, 74.0698% { content: "Cogn"; }
  56.9767%, 72.9302% { content: "Cogniti"; }
  58.1163%, 71.7907% { content: "Cognitive A"; }
  59.2558%, 70.6512% { content: "Cognitive AI Res"; }
  60.3953%, 69.5116% { content: "Cognitive AI Resear"; }
  61.5349%, 68.3721% { content: "Cognitive AI Researcher"; } */

  /* 78.6279%, 96.8605% { content: ""; }
  79.7674%, 95.7209% { content: "h"; }
  80.9070%, 94.5814% { content: "hu"; }
  82.0465%, 93.4419% { content: "hum"; }
  83.1860%, 92.3023% { content: "huma"; }
  84.3256%, 91.1628% { content: "human"; } */
}

@keyframes blink {
  0%, 100% { opacity: 1; }
  50% { opacity: 0; }
}

.typewriter {
  --caret: currentcolor;
}

.typewriter::before {
  content: "";
  animation: typing 10s infinite;
}

.typewriter::after {
  content: "";
  border-right: 1px solid var(--caret);
  animation: blink 0.5s linear infinite;
}

.typewriter.thick::after {
  border-right: 1ch solid var(--caret);
}

.typewriter.nocaret::after {
  border-right: 0;
}


@media (prefers-reduced-motion) {
  .typewriter::after {
    animation: none;
  }
  
  @keyframes sequencePopup {
    0%, 100% { content: "Cognitive AI Researcher"; }
    25% { content: "writer"; }
    50% { content: "reader"; }
    75% { content: "human"; }
  }

  .typewriter::before {
    content: "developer";
    animation: sequencePopup 12s linear infinite;
  }
}
</style>

<!-- <div class="typed-text d-none">Research Scholar at BrownU, (Cognitive) AI Researcher, Software Developer</div> -->

<h1 aria-label="Hi! I'm a developer">
  Hi! I'm a&nbsp;<span class="typewriter"></span>
</h1>

I'm a Research Scholar at the <a target="_blank" href="https://serre-lab.clps.brown.edu/">Serre Lab</a> at Brown University, working on simulating <em>intelligence</em> artificially, leveraging principles from Cognitive Science. I have been exceedingly fortunate to be advised by <em>(the incredible)</em>  <a target="_blank" href="https://www.brown.edu/academics/cognitive-linguistic-psychological-sciences/people/faculty/thomas-serre">Dr. Thomas Serre</a> while I address 
questions like:

<div>
<ul>
  <li><em>Which neural computations lead to human intelligence?</em></li>
  <li><em>How do we teach models to learn better features?</em></li>
</ul>
</div>

I aim to reverse-engineer human cognition and help create more effective artificial intelligence systems—a cross-fertilization between Cognitive Science and AI, spurring deeper insights in both fields.

In general, I like to work on projects that are impact-oriented and solve real-world problems. My interests are interdisciplinary, blending concepts from Artificial Intelligence, Computer Vision, Cognitive Science, and Biology. I’m particularly interested in applying my research to solve problems in society and global healthcare.

<h4>Previously</h4>
Before my curent role, I worked on algorithmic trading, high and low touch flows, and a new equities (stocks, bonds, ETFs) trading platform at Goldman Sachs for the better part of two years. I completed my undergraduate education in Computer Science.

<h4>Outside the Lab</h4>
I spend most of my time outside of the lab in the gym. I also really enjoy playing the piano, and watching (<a target="_blank" href="https://www.britannica.com/story/why-do-some-people-call-football-soccer#:~:text=One%20of%20the%20best%2Dknown,that%20soccer%20is%20an%20Americanism.">real</a>) football and Formula 1.


<!-- For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->

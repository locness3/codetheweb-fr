---
layout: post
title: 'Comment apprendre le développement web'
image: 'assets/img/posts/how-to-learn-web-development/cover.jpg'
tags: Other HTML CSS JavaScript
suggestedlang: HTML
keywords: "learn code, learn to code, learn web development, learn html, learn css, learn javascript, learn html and css, how to become a web developer, how to learn html, how to learn css, how to learn javascript, how to learn web development, how to make a website"
checked: [grammarly]
---
Alors, vous voulez apprendre le développement web? Lisez ci-dessous pour savoir comment...

> **Vous voulez apprendre un langage en particulier? [C'est par ici.][learn]**

## Qu'est-ce que le développement web?
Vous avez très probablement entendu parler du codage ou de la programmation (je suis sûr que si!). En fait, le développement web est une façon de coder, spécifiquement des sites Internet et des applications web (des sites web interactifs, qui permettent de faire des choses). De nos jours, c'est une manière de programmer très répandue, et une bonne façon de commencer à coder.

## Pourquoi apprendre le développement web?
Si vous débutez en codage, le développement web est une bonne façon de commencer:
1. C'est relativement simple au début - mais vous pouvez aller plus loin
2. C'est amusant (ouais!)
3. Vous créez ce que vous utilisez tous les jours - des sites Internet
4. *Ajouté par la traduction.* Vous avez la liberté de créer *votre* site comme vous le voulez!

Si vous êtes curieux, aimez les défis ou apprendre des nouvelles choses, le développement web est pour vous. 
{% comment %}TODO : Il faut tout de même prendre en considération la barrière entre le développement web simple et la programmation.{% endcomment %}
Cela étant dit, il est mieux de coder si vous en avez envie, et non pas pour avoir un bon métier et suivre la tendance, comme dit dans [cet article de Simple Programmer][dont-code] (en anglais).

{% comment %}
## How I learned web development
Well, I wanted to learn to code. I looked at tutorials from all over the internet and got the rest of my knowledge from actually coding and what I needed as I went along.
{% endcomment %}

{% comment %}TODO : qu'est-ce qu'un langage de programmation?{% endcomment %}

## Une stratégie pour apprendre
Lisez ce site à chaque instant de votre vie. Attends, quoi? - si, c'est ce qu'on voulait dire. Plus sérieusement:

Vous devirez premièrement apprendre la syntaxe des langages - c'est à dire comment écrire le code -, leur utilité et leurs fonctionnalités.

Ensuite, au lieu d'apprendre *chaque fonctionnalité de chaque langage*, lancez-vous directement. Vous en saurez assez pour faire des sites basiques, et vous pourrez en apprendre plus au fur et à mesure. Quand vous ne savez pas comment faire quelque chose, cherchez sur Internet. Un petit secret de développeur : StackOverflow.

[StackOverflow] est un site de questions-réponses pour la programmation. Neuf fois sur dix, quelqu'un aura déja répondu à votre question - et si non, vous pouvez demander. Il y a une grande communauté, vous aurez généralement une réponse sous quelques minutes. Les gens là-bas sont intelligents et sympathiques. Okay, enough ranting about StackOverflow.

> **EDIT:** [I have wrote an article about 5 other quick-reference sites that you can go to look things up on.][reference-sites-to-help-you-learn-coding]{:target='_blank'}

Also, there will be some things that you'll want to memorize, and the best way to do this is by using them for real projects over and over again. Don't worry though, these days your memory doesn't even matter that much - you can look up whatever it is that you don't remember. 

So now you hopefully know how you're going to learn web development, but *what is it that you actually need to learn?*

## Where to start
First, you are going to want to learn front-end programming - this is what you actually see. Back-end programming is all that confusing stuff that goes on the actual server like databases and request handling. It is possible to make an entire website without coding anything on the back-end, so you should definitely start with front-end programming.

There are three main languages that are part of front-end programming: *HTML*, *CSS*, and *JavaScript*. Let's have a quick look at what each of them is:

**NOTE:** you will see some code here, but don't panic - it's just to show you what they look like.

### HTML
HTML stands for Hypertext Markup Language. This is what makes up the actual content of the website - for example, the paragraph above might look something like this:

```HTML
<h2 id="where-to-start">Where to start</h2>

<p>First, you are going to want to learn front-end programming - this is what you actually see. Back-end programming is all that confusing stuff that goes on the actual server like databases and request handling. It is possible to make an entire website without coding anything on the back-end, so you should definitely start with front-end programming.</p>

<p>There are three main languages that are part of front-end programming: <em>HTML</em>, <em>CSS</em>, and <em>JavaScript</em>. Let’s have a look at what each of them is:</p>
```
{: .wrap}

As you can see, it has some normal text but then also some other bits of code. This is called markup - hence the name Hypertext Markup Language.

### CSS
CSS stands for Cascading Style Sheet and controls what a webpage looks like. Without CSS, the entire web would look something like this:
![This article without CSS][no-css]
Here is a snippet of CSS:
```CSS
#where-to-start {
    color: red;
    text-align: center;
    border: 5px solid red;
}
```

### JavaScript
JavaScript is what makes web pages do stuff. It has stuff like if/else statements and functions (which you will learn about later). Here is a snippet of JavaScript:

```JavaScript
var x = 5;

if(x < 10) {
    console.log("x is a one-digit number.");
} else {
    console.log("x has more that one digit.");
}
```

JavaScript is much harder to master than HTML and CSS as it doesn't just display stuff - it does stuff. JavaScript can also change the HTML and CSS of a webpage.

You will eventually need to learn all three of these languages if you want to make a website (you don't always need JavaScript but it's good to know, especially for web-apps). I recommend learning them in this order:

1. HTML
2. CSS
3. JavaScript

This order goes from easiest to most difficult, and also most important to least important - you can't have a webpage without HTML, and you will need CSS if you don't want your website to look crap (but at least you have one). Because of this, I'm going to be writing my posts in this order - common HTML, common CSS, common JavaScript and then extra cool stuff. You can [keep up to date and follow along here][newsletter].

## How much time to spend
Now here's the biggie: How much time do you need to spend on coding to learn it? Even if you are short on time, you can still learn to code - you will just learn at a slower pace. You shouldn't really be aiming to do a certain amount of coding each week - just set some time aside, and code for as long as you want (or until your brain hurts). Ideally, you will enjoy coding and it won't be a matter of trying to sit down for a certain amount of time. That said, there will be times along the way when something isn't working as expected and you have no idea what to do, but keep persevering. In terms of frequency, I would recommend at least once a week - but do it as often as you want if you have the time.

## Conclusion
Congrats on starting your journey to becoming a web developer! There will be times when you want to give up, but keep going and you will enjoy it. To get started with web development, [look out for my next post, where I'll be talking about how to get your computer set up for web development][set-up].

So, what did you think of that article? Don't hesitate to [tell me in the comments][comments] or [share it with your friends][share] if you liked it.

> UPDATE:<br>
> **Interested in learning any of the three languages I talked about in this article?**<br>
> I have made pages for HTML, CSS, and JavaScript with all of my posts you should read to learn that language *in order*.<br><br>
> [You can get going right away here!][learn]


[dont-code]: https://simpleprogrammer.com/2016/02/22/please-dont-learn-to-code-unless/
[StackOverflow]: https://stackoverflow.com/
[reference-sites-to-help-you-learn-coding]: /web-development-reference-sites/
[no-css]: {{ site.baseurl }}assets/img/posts/how-to-learn-web-development/no-css.png
[set-up]: /web-development-on-your-computer/
[learn]: /learn

[share]: {{site.share}}
[comments]: {{site.comments}}
[newsletter]: {{site.newsletter}}
---
title: Home
description: Kashish Munjal's Journal.
image: /images/welcome.jpg
---
<script>
myWork = {"github": "kashishm", "blog": "https://kashishm.github.io/blog"} 
</script>
<section class="hero" style="background-image: url({% include relative-src.html src=page.image %})">
	<div class="inner-hero text-container">
		<div class="hero-text-container">
			<h1 class="editable">Welcome!</h1>
<p class="subtext editable">
<div markdown="1">
My name is **Kashish Munjal**, a **software developer** based in Bangalore.
This website is my window to the world. You're welcome to have a look at my **[work](https://github.com/kashishm)** or my **[blog](https://medium.com/@kashishmunjal)**.
</div>
</p>
<div class="cta button alt"><a href="https://medium.com/@kashishmunjal" target="_blank">Blog</a></div>
</div>
</div>
</section>

<div class="content">
<section class="pad" id="about" style="padding-bottom: 0px;">
	<div class="container">
	<div style="text-align: center;">
		<h2>About</h2>
	</div>
	<ul class="staff">
		<li style="padding: 0px;">
			<div class="square-image" style="background-image: url(/images/kashish.jpg)"></div>
			<div class="name"><a target="_blank" href="https://github.com/kashishm">Kashish Munjal</a></div>
			<div class="position">Application Developer</div>
		</li>
	</ul>
		<div  markdown="1">
I am a developer at [ThoughtWorks Studios](https://www.thoughtworks.com/products), on the [Gauge](http://getgauge.io) team. Gauge is a light weight cross-platform test automation tool. It provides the ability to author test cases in the business language.

I am passionate about new technologies and its applications in the field of Software Engineering.

Most of my work is public, including my [codes](https://github.com/kashishm). When I am not coding, I like to play Cricket, Badminton or watch movies/TV. One of my favorite TV series is "The Big Bang Theory". I blog at [kashishm.github.io](/blog) about my technical work.

One thing I really like about being a developer is that you are always working on machines which don’t argue, they remember everything, and they don’t drink all your beer.

If I were to program myself, following would be the perfect program:

{% gist e531605a93f8e62114ee5e9fb8d85558 %}
</div>
</div>
</section>
<section class="pad" id="contact" style="background: #f7f7f7">
<div class="container contact-box">
<div style="text-align: center;">
	<h2>Get in Touch</h2>
<div markdown="1">
Find me on [Twitter](http://twitter.com/Kashish_Munjal), [Github](https://github.com/kashishm), [LinkedIn](https://www.linkedin.com/in/kashish-munjal-abb8728b), [Facebook](https://www.facebook.com/kash.munjal), [Keybase](https://keybase.io/kashishm) or [Gmail](mailto:kashishmunjal64@gmail.com).
</div>
</div>
	<form action="https://formspree.io/kashishm.feedback@gmail.com" method="POST" class="contact-form"  style="width: 100%;">
		<input type="hidden" name="_next" value="{{ site.baseurl }}/contact-success/" />
		
		<label for="name">Name</label>
		<input type="text" name="name" id="name">

		<label for="email">Email Address</label>
		<input type="email" name="_replyto" id="email" required>

		<label for="message">Message</label>
		<textarea name="message" id="message" required></textarea>
		<input type="submit" value="Send Message">
		<div class="button" style="margin: 20px 0 0 0; text-align: center;">
			<a href="/static/cv/kashish-CV.pdf" style="width: 100%;box-sizing: border-box;" class="alt">Download CV</a>
		</div>
	</form>
</div>
</section>

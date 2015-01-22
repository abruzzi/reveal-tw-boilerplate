### Get started

![ThoughtWorks in a nutshell](https://github.com/abruzzi/reveal-tw-boilerplate/blob/master/green-resized.png)

This is a customized version of reveal.js for create a `ThoughtWorks` style presentation much more easier, it contains:

1.	Guardfile to watch changes
2.	config.rb used for compass
3.	A very simple Reveal.js template


#### For those who just want to create new slides

`git clone` and then open the index.html in your browser, that's it. Actually you can go one step further and try to edit your slide lively(see the section below).

```sh
$ git clone git@github.com:abruzzi/reveal-tw-boilerplate.git 
$ cd presentation
$ open index.html
```

#### For those who want to customize the theme itself

To use it, simply clone this repo and :

```sh
$ bundle install
```

After the required `gem`s are installed, you can then run 

```sh
$ guard start
```

And if you dont have the amazing chrome [plugin](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei) installed, you should. 

Once it's installed, open the page in browser, and click the `live reload` button to enabled. You should then see something like this if you have `guard` started:

```
[1] guard(main)> 23:58:49 - INFO - Browser connected.
```

And after this, you can edit the `index.html` for add new slides, and `css/theme/source/thoughtworks.scss` for new styles.

There are a lot of `predefined` style, here is the list:

1.  `bg-pink` for pink background color, `pink` for pink text color
2.  Some other colors like `lightgray`, `darkgray`, `blue` and `green` are available as well following the convention above
3.  `left` for `text-align: left` and `right` for `text-align: right`
4.  `title` for the main title, and `subtitle` for subtitle

You can use the combination like this:

```html
<section class="bg-lightgray darkgray">
	<h2 class="pink">ThoughtWorks in a nutshell</h2>
	<p class="emphasize">We are passionate technologists. We provide software delivery, pioneering tools and consulting for organizations with ambitious missions.</p>
</section>
```

![ThoughtWorks in a nutshell](https://github.com/abruzzi/reveal-tw-boilerplate/blob/master/thoughtworks-resized.png)


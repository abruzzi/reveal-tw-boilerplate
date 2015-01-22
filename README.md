### Get started

This is a customized version of reveal.js for create a `ThoughtWorks` style presentation much more easier, it contains:

1.	Guardfile to watch changes
2.	config.rb used for compass
3.	A very simple Reveal.js template


#### For those who just want to create new slides

`git clone` and then open the index.html in your browser, that's it. Actually you can go one step further and try to edit your slide lively(see the section below).

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


# AnythingSlider jQuery Plugin

A very robust jQuery-based slider plugin. Need to link to a specific slide? No problem. Like a choice of themes? Got it. Need callbacks for when specific slider actions happen? Sure. Need custom tab names? You got it. Need more than one slider per page? Easy.

* Having problems with installing or getting the plugin to work? Ask your question in the [CSS-Tricks forums](http://css-tricks.com/forums/) or on [StackOverflow](http://stackoverflow.com/questions/tagged/anythingslider).
* Find a bug or have an enhancement request? Submit it [here](https://github.com/CSS-Tricks/AnythingSlider/issues)

## [Main Demo](http://css-tricks.github.com/AnythingSlider/)

* [Documentation](https://github.com/CSS-Tricks/AnythingSlider/wiki) ([FAQ](https://github.com/CSS-Tricks/AnythingSlider/wiki/FAQ)).
* [Original CSS-Tricks demo](http://css-tricks.com/examples/AnythingSlider/).
* [Latest demos!](http://css-tricks.github.com/AnythingSlider/).
* [Download](https://github.com/CSS-Tricks/AnythingSlider/zipball/master).

## Related Projects

Download the full repo for a full set of all the cool stuff AnythingSlider can do.

* More themes - [AnythingSlider-Themes](https://github.com/CSS-Tricks/AnythingSlider-Themes)
* Fx bookmarklet - [AnythingSlider-FX-Builder](https://github.com/CSS-Tricks/AnythingSlider-Fx-Builder)

CMS plugins/mods

* Wordpress plugin - [AnythingSlider-for-WordPress](https://github.com/jacobdubail/AnythingSlider-for-WordPress)
* Movable Type plugin - [mt-plugin-anythingslider](https://github.com/meancode/mt-plugin-anythingslider)
* Joomla 2.5 mod - [mod_anythingslider](https://github.com/CSS-Tricks/mod_anythingslider)

## Recent Changes

# Version 1.9.7 (12/1/2017)

* Core: Prevent JS error when panel doesn't exist. Fixes [issue #659](https://github.com/CSS-Tricks/AnythingSlider/issues/659).

# Version 1.9.6 (5/25/2016)

* Video: Use https for YouTube api calls. Fixes [issue #648](https://github.com/CSS-Tricks/AnythingSlider/issues/648).
* Demos: Use https for external files. Fixes [issue #646](https://github.com/CSS-Tricks/AnythingSlider/issues/646).

# Version 1.9.5 (3/4/2016)

* Dynamic video extension
  * Prevent reinitializing the video more than once.
  * Allow dynamically adding & removing videos; call `.anythingSliderVideo()` to update.
  * Add dynamic demo to video page.
  * All thanks to [christian-seifert](https://github.com/christian-seifert) in [pull #604](https://github.com/CSS-Tricks/AnythingSlider/pull/604)!
* Force vimeo iframe to use `https` to prevent iframe communication issues. Fixes [issue #645](https://github.com/CSS-Tricks/AnythingSlider/issues/645).

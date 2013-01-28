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

## Change Log

# Version 1.8.16

* Merged in video extension update to prevent errors in iOS devices that don't support Flash. See [pull #485](https://github.com/CSS-Tricks/AnythingSlider/pull/485). Thanks [mlms13](https://github.com/mlms13)!

# Version 1.8.15

* Another version bump to try to register the plugin.

# Version 1.8.14

* Modified `expand`:
 * It now delays checking when the document is hidden.
 * Updated resizing checks to hopefully fix [issue #481](https://github.com/CSS-Tricks/AnythingSlider/issues/481).
* Updated cs-portfolio theme to include a bottom margin so the controls don't get overlapped. See [issue #483](https://github.com/CSS-Tricks/AnythingSlider/issues/483).
* Updated demos:
 * Demos now use jQuery 1.8. I was going to update the demos to use v1.9, but it's still very buggy. The biggest one being [this animation issue](http://bugs.jquery.com/ticket/13183) which has been fixed in v1.9.1.
 * Because I will eventually update the demos to use jQuery v2.0, I had to switch the syntax-highlighting plugin to use google's prettify.
 * Updated colorbox plugin also because of errors when testing demos with jQuery v2.0.
 * Updated included jQuery file to v1.8.3.
 * Moved change log from the index.html file back to the readme.md file... it makes it easier to copy the markdown directly into the wiki change log.

# Versions 1.8.10 to 1.8.13

* New version, just to register with the [jquery plugin registry](http://plugins.jquery.com/).

# Version 1.8.9

* Removed code that clears the height of the outer wrapper when using the `expand` option. Fixes [issue #476](https://github.com/CSS-Tricks/AnythingSlider/issues/476).

# Version 1.8.8

* More `hashTag` option tweaks:
  * The current panel can no longer be set via the hash when the `hashTags` option is set to `false`.
  * This prevents errors when using other history plugins. Fixes [issue #432](https://github.com/CSS-Tricks/AnythingSlider/issues/432).

# Version 1.8.7

* Fixed hash tag issues.
  * Equals within the hash should now be ignored. Fixes [issue #413](https://github.com/CSS-Tricks/AnythingSlider/issues/413).
  * Hashtags are no longer processed if the hashTags option is false. Fixes [issue #432](https://github.com/CSS-Tricks/AnythingSlider/issues/432).
* Updated all themes to no longer use a negative z-index. Fixes [issue #447](https://github.com/CSS-Tricks/AnythingSlider/issues/447).
* Updating a slider will now include updating the width and height of the slider. Fixes [issue #459](https://github.com/CSS-Tricks/AnythingSlider/issues/459).
* Slideshow now stops/pauses when the slider is not in the active browser tab.
  * The slideshow completely stops if not in the active browser tab.
  * If the autoPlayLocked option is true, the slideshow will only pause, then resume once the browser tab is active.
  * Enhancement request from [issue #463](https://github.com/CSS-Tricks/AnythingSlider/issues/463).

# Moved Repo!
* The AnythingSlider repo was "moved" from ProLoser/AnythingSlider to CSS-Tricks/AnythingSlider.
* Due to an issue, the repository was removed and all issues and links were lost, sorry for the inconvenience.
* The Wiki documents have been replaced, but as all of the jsFiddle demos were targetting the files from the previous location, they are most likely all broken. I will slowly update these demos and links as time permits.

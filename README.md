# Casper

This is the [Ghost](https://github.com/tryghost/ghost/) theme of [angristan.xyz](https://angristan.xyz), based on [Casper](https://github.com/TryGhost/Casper).

For more information regarding how to use the theme with Ghost, please refer to the [original README](https://github.com/TryGhost/Casper)

## Fork

List of the modifications made in this fork:

* [Custom CSS (commented)](https://github.com/Angristan/Casper-XYZ/blob/master/assets/css/custom.css)
* [Removed share buttons in the header](https://github.com/Angristan/Casper-XYZ/commit/b4530b973a71bcdfce82c02572525171a5fa9159)
* [Replaced Feedly links by original RSS links](https://github.com/Angristan/Casper-XYZ/commit/c618bc702969c217b6f48277244b6bf04b4e46bd)
* [Added Isso for comments](https://github.com/Angristan/Casper-XYZ/blob/master/post.hbs#L71)
* [Host jQuery locally](https://github.com/Angristan/Casper-XYZ/commit/50b425d7c1a370bd44d599d597b25623f8c8936b)
* [Use the Open Sans Pro font](https://github.com/Angristan/Casper-XYZ/blob/master/assets/css/custom.css#L1)
* [Header image is the same width as the content, and the content doesn't step on it](https://github.com/Angristan/Casper-XYZ/commit/1c0fd7d699651d7413028d130f59e20dbcab498e)

### Hardcoded stuff

I try to make the theme reusable as possible, but I still have to hardcode some stuff.

* [Isso comments block](https://github.com/Angristan/Casper-XYZ/blob/master/post.hbs#L71)


### External assets embedded

Here are the assets that I downloaded and included in the repo as I don't want to make call to 3rd-party services:

* [jQuery](https://github.com/jquery/jquery)
* [Source Sans Pro font from Google Fonts](https://fonts.google.com/specimen/Source+Sans+Pro)

They are all under their respective licence.

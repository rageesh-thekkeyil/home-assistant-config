# Packages

In order to keep my configuration organized and easy to work with, I have opted 
to use Home Assistant's 
[Packages](https://www.home-assistant.io/docs/configuration/packages/) 
functionality. This allows me to keep all of my code pretaining to something
together.

## Naming Convention

Although the ```package: !include_dir_named``` statement will recursively
search a directory, there is no indication within HASS as to what folder it
actually came from. To make my files organized, I have prefixed them with a
function idenfier. That way they are grouped together in a logical manner. Most
of this follows the nomenclature outlined in the [Home Assistant Glossary](https://www.home-assistant.io/docs/glossary/).
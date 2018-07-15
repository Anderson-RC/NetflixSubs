# NetflixSubs Plugin for Kodi 18 (plugin.video.netflixsubs)

## Disclaimer

This plugin is not officially commisioned/supported by Netflix.
The trademark "Netflix" is registered by "Netflix, Inc."

This plugin is based on the original [Netflix plugin for Kodi](https://github.com/asciidisco/plugin.video.netflix) and has been modified to automatically save SRT subtitles to a file on your PC. 

## Installation

Download the latest Source Code ZIP file of the NetflixSubs plugin from the [releases page](https://github.com/Zarxrax/NetflixSubs/releases)

Install the latest Kodi 18 [nightlybuild](http://mirrors.kodi.tv/nightlies/) using Full Installation option. Then launch Kodi.

Go to: Settings > Add ons > Install from zip file

You will get a popup window saying that installing from unknown sources is disabled. Click the “settings” button, Enable “unknown sources” and then click “yes”.

Return to “install from zip file” and select the NetflixSubs plugin.

If you use Netflix in a language other than English, go to settings > interface > Skin > fonts > Arial based.

Return to the Kodi main screen, and select Add-ons, and you should see the NetflixSubs addon listed there. Click to launch, or right-click to access the settings menu.

Further instructions and discussion can be found at http://www.nihongonobaka.com/download-japanese-subtitles-as-text-from-netflix-using-a-kodi-plugin/

## Usage

Log in using your Netflix username and password, and then select a show or movie to play. 

The first time you try to play something, you will be prompted to enable InputStream helper and install WideVine. Just follow the prompts.

When you attempt to play a video, the subtitle files will automatically be written to disk, along with a file named Subtitle_Urls.txt which includes a list of all available subtitle streams for the most recently played video, and the language codes for each.

You can specify where you want to save the subtitle files within the plugin settings. You can also specify if you only want to download subtitles with a specific language code.

## Subtitle Availability (Why isn't the language I want available?)

When you normally view Netflix through your PC, TV, or other device, you may have access to a wide variety of subtitles, some of which can be enabled simply by changing the your language within the Netflix settings.

When using the Kodi NetflixSubs plugin, you may find that your available subtitles are different than what you can normally access. This is because Netflix ONLY takes your location into account when using this plugin. If you have tested multiple different videos and can not find the language that you want, then you may need to use a VPN from a country where that language is used. It may be difficult to find a working VPN, because Netflix actively attempts to block them, but this may be the only way to obtain foreign language subtitles in some cases.

## Licence

Licenced under The MIT License.

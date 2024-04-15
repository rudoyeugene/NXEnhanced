<p align="center"><img src="https://raw.githubusercontent.com/hjk789/NXEnhanced/master/WebExtension/icon.png"></p>
<h1 align="center">NX Enhanced</h1>
<p align="center">Adds "quality-of-life" features to NextDNS website to make the experience of managing lists, domains, logs, etc. more practical. </p>
<h3 align="center">⚠ It's a fork, no huge changes planned, just tiny ones to keep Google satisfied.</h6>

## Current features

### Logs page:

- Allow/Deny buttons in the logs that make it possible to add an exception or block a domain without needing to copy, switch pages, and paste.

    ![Allow and Deny butttons](https://i.imgur.com/3XNMUi1.png)    
You can either add the respective domain or the whole root domain, or even edit the domain if you want.   
[Read more](https://github.com/hjk789/NXEnhanced/wiki#an-allowdeny-button-for-each-log-entry)

- Ability to specify domains that should be hidden from the logs

    ![Domain filtering](https://i.imgur.com/l8Ouzh1.png)    
    You can either manually input domains, or click on the "Hide" button, alongside the Allow/Deny buttons, which lets you hide domains with few clicks.  [Read more](https://github.com/hjk789/NXEnhanced/wiki#ability-to-specify-domains-that-should-be-hidden-from-the-logs)

- Ability to load only the logs that happened before a specified date-time

    ![only logs before](https://i.imgur.com/FChYIoS.png)

- Option to show only queries from unnamed devices

    ![Other Devices button](https://i.imgur.com/V7HFiJL.png)

- Refine a search with multiple search terms or exclusion terms

    ![multiple terms](https://i.imgur.com/fBlxR18.png)    
    You can specify as many terms as you need. [Read more](https://github.com/hjk789/NXEnhanced/wiki#refine-a-search-with-multiple-search-terms-or-exclusion-terms)

- An option to show the number of entries currently loaded, visible or hidden by filters

    ![counters](https://i.imgur.com/8mTEDt1.png)

- Show the query's absolute time (HH:MM:SS) along with the relative time ("a minute ago", "few seconds ago")

    ![Absolute time](https://i.imgur.com/I3pGNL8.png)

- Relative time that counts minutes, then hours, and goes up to "Yesterday"

    ![more relative times](https://i.imgur.com/BhS1B6n.png)

- A refresh button

    ![refresh button](https://i.imgur.com/yBEo3mV.png)

### Allowlist/Denylist pages:

- Ability to add a description to each domain in the allow/denylists. [Read more](https://github.com/hjk789/NXEnhanced/wiki#ability-to-add-a-description-to-each-domain-in-the-denyallow-lists)

    ![Description input](https://i.imgur.com/wS2kRNG.png)

- Ability to add a list of domains, instead of one by one

    ![multiline input box](https://i.imgur.com/p5Ovg11.png)

- Sort the allow/deny lists alphabetically, and styling options for an easier quick reading, such as: lighten subdomains, bold root domain and right-align.
    
    ![allow/deny options](https://i.imgur.com/HCgekWd.png)

### Settings page:

- Ability to export/import all settings from/to a config. [Read more](https://github.com/hjk789/NXEnhanced/wiki#ability-to-exportimport-all-settings-fromto-a-config)

    ![Export/import buttons](https://i.imgur.com/2oEl8t2.png)    

### Privacy page:

- Collapse the list of blocklists enabled and adds a button to unhide them if needed

    ![Hidden lists](https://i.imgur.com/ifnmNiv.png)    
    This is good for people with a long list of blocklists added.

- Sort alphabetically the list of blocklists in the "Add a blocklist" screen

    ![Sort a-z blocklists](https://i.imgur.com/rFXduAY.png)

### Security page:

- Collapse the list of added TLDs

- A button that allows you to add every TLD in the "Add a TLD" screen in one click.

    ![Add all TLDs button](https://i.imgur.com/PDlYlF1.png)      


## How to install

Click the button above that matches your browser, install then confirm installation. If you are using a Chromium-based browser, like Brave, Opera, Vivaldi, and others, use the Chrome Web Store link.

You also have the option of using the userscript version, but it works only in Chrome, in Firefox it works partially. Also, keep in mind that the userscript is discontinued, so it won't receive any updates. For more information and instructions, read [here](https://github.com/hjk789/NXEnhanced/tree/master/Userscript#how-to-use-it).

NX Enhanced was tested in Firefox and Chrome. It should work fine in pretty much any browser that accepts Firefox or Chrome extensions, although I didn't tested them.

## Bug reports, suggestions and questions

In case you experience any problem with NX Enhanced, or you want to make suggestions, you are encouraged to post a new issue on the [Issues section](https://github.com/hjk789/NXEnhanced/issues). Any feedback is welcome, appreciated and encouraged. If you have any questions you can start a new discussion in the [Discussions section](https://github.com/hjk789/NXEnhanced/discussions).

## How to contribute

If you would like to contribute with code, pull requests are welcomed. :)

If you can't code, but still want to contribute, you can do so by [making a donation](https://github.com/hjk789/NXEnhanced/wiki/Donation-methods).

If you don't have funds to donate, but still want to contribute, you can do so by spreading the word about NX Enhanced on the web or to your acquaintances, giving feedback, rating the extension and posting a review.

## License

- You can view the code, download copies to your devices, install, run, use the features and uninstall this software.
- You can modify your downloaded copy as you like, although it's recommended that you suggest this modification to be included in the original, so all users can benefit.
- You can suggest changes, new features or fixes, either by opening issues or by doing pull requests. 
- You can open or participate in issues and discussions, give feedback and rate this project.
- Feel free to refer to NX Enhanced, just make sure to include a link to this project's repository homepage (https://github.com/hjk789/NXEnhanced). 
- You can make a fork of this project, provided that: 1. You fork it inside GitHub, by clicking on the "Fork" button or
  the "Edit this file" button of this project's repository web page; and 2. You fork it in order to push changes to this
  project's repository with a pull request. If you don't fit in these conditions, don't fork it, "*Star*" it instead.
  Any contributed code is owned by the repository owner, [Eugene Rudo](https://github.com/rudoyeugene). The credits for
  the contributed code goes to the contributor.
- You cannot do any other action not allowed in this license.  

I, [Eugene Rudo](https://github.com/rudoyeugene), have no association with NextDNS Inc., I'm just a user of their DNS
service who needed the features NX Enhanced provides. NX Enhanced is a completely voluntary and unnoficial work. Neither
I, nor NextDNS Inc., are responsible for any damage or leak, directly or indirectly related to the use or misuse of this
software. The responsibility is completely on it's users. Use it at your own risk. There are no warranties, either
implied or stated.

Copyright (c) 2023+ [Eugene Rudo](https://github.com/rudoyeugene)

## Privacy policy

You can read the full privacy policy [here](https://github.com/hjk789/NXEnhanced/wiki/Privacy-Policy). In brief, most of what you need to know is in the first line: "NX Enhanced does not collect and does not send your data to third-parties, it also does not include any kind of tracking or analytics in the code. It also does not and will not have access to your email or password."

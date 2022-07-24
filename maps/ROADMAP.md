# Roadmap for the Arching Kaos project
*An overview of subprojects, checkpoints, stops for thought, integrations and how the Arching Kaos projects is supposed to be completed.*

## Brief description

> This was empty for a long time.

Arching Kaos is an attempt to create a shared basis for content creators focused on music mixing of electronic music in order to lift the vibes and let differences out. It is a network of minimal blockchains. Each participant can create content and be heard. On [arching-kaos.net](https://arching-kaos.net), you will find content from some creators already, migrated from the previous version of the radio station.

While mentioning radio station, live stream is not available but it will soon be as the decentralized radio part takes off.

### Development
Parts in need are:
- [ ] - Arching Kaos Decentralized Radio
- [x] - Static HTML5 page which loads the content we want
- [x] - Explorer of the ZCHAIN
- [x] - Modules

### Proof of concept [Completed]

> Make on small application that demonstrates a 'news' type messages that integrates the [news repo](https://git.kaotisk-hund.com/01-NEWS/.git).

Done, you can visit the [link](https://news.arching-kaos.net)

#### Description

What the link above does is searching for addresses on the Stellar Network that trust the ARCHINGKAOS asset. Then, it finds participants with an `config` entry on their accounts. Then we start browsing our findings and display the news articles on the website. Visiting a specified article can be done also.

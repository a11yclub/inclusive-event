# Accessibility Club — Inclusive Events

This repository contains a growing collection of notes and checklists to help with organizing inclusive events. Most of the information here has been compiled and proven to be helpful while organizing [Accessibility Club](https://accessibility-club.org/) events in the recent years. However, we believe that some of the ideas presented here might be useful for all kinds of events, so we'd like to release it to the public domain. Also, we'd like to use this place as as central repository for ourselves so we can use it as a library and don't have to start thinking about all the details from scratch over and over again. 😉

We're in the very early stages of building up this repository and it will likely be subject to heavy change in the beginning. We sincerely invite you to study the information provided here, comment, correct and amend it so that hopefully a lot of people can find value in it.

## Structure

For now, we can think of two different ways of organizing the information in this repository, both of them providing value in certain situations.

### By category

There are lots of different aspects to consider when organizing an event. As the main way of structuring information we will therefore split the documentation into **categories**:

* [Badges](categories/badges/README.md)
* [Captions](categories/captions/README.md)
* [Catering](categories/catering/README.md)
* [Live Stream](categories/live-stream/README.md)
* [Photos](categories/photos/README.md)
* [Signage](categories/signage/README.md)
* [Slides](categories/slides/README.md)
* [Speakers](categories/speakers/README.md)
* [Sponsors](categories/sponsors/README.md)
* [Venue](categories/venue/README.md)
* [Video](categories/video/README.md)
* [Website](categories/website/README.md)
* etc.

Some of these categories might also have subcategories to further compartmentalize the information. Please have a look at the `categories` directory of this repository. Each category has it's own subdirectory, containing a `README.md` and potentially the media files (images, other resources) used in the README file.

### By organizational stage

There are many different things to consider when organizing an event and some of them particularly apply to certain stages in the event's life cycle. We therefore think that it's helpful to also have the information structured by organizational stage, e.g.

* [announcing](stages/1-ANNOUNCING.md) the event,
* [scouting](stages/2-SCOUTING.md) a venue, speakers, etc. for the event,
* [preparing](stages/3-PREPARING.md) the event,
* [finding sponsors](stages/4-SPONSORING.md) for the event
* [running](stages/5-RUNNING.md) the event,
* [following up](stages/6-FOLLOWING-UP.md) on the event,
* etc.

In each of the phases an event goes through, different aspects might be of particular importance. In order to make the information in this repository browseable by organizational stage as well, we'll take two different measures:

* Each of the README files in the `categories` directory MUST be structured by phases internally. **Each phase must begin with a proper heading** so it can be linked to directly.
* The top-level subdirectory `stages` contains one Markdown file per organizational stage, grouping together links to the individual categories and sections therein that apply for that particular stage.

This way it should be easily possible to quickly gather important information that's especially relevant at a certain time.

## Resources

There are already lots of other resources out there, some of them covering a wide range of topics while others are focusing on very specific aspects. Here's an (all but complete) list of such resources — please feel free to submit additional suggestions either by [sending a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) or dropping us an email at hello@a11y-club.org.

* [Ramp-Up.me](https://ramp-up.me/) — planning accessible events

## Translations

One reason why we (for now) decided to start an new repository about organizing inclusive events is the fact that most of the resources out there tend to be in one language only. However, we'd love to see translations to as many languages as possible, so we'll try to put some effort into this and encourage you to help us translate the resources found here.

It's probably going to be a challenge to keep the translations in sync with each other, especially if they are updated frequently. However, we believe that even an incomplete translation is better than none (and we also don't want to over-engineer this part). For a start, we'd like to try it like this:

* For maximum understandability, the **main language should always be English**. If you submit a new resource or update an existing one, please always think of the English version in a first place. Feel free to ask for help if you're not able to translate your language to English.
* Resources should always use the [Markdown](https://www.markdownguide.org/) file format and have a **descriptive file name** with the ending `.md`. For the English version, don't use a language identifier in the file name (see below).
* For translations of an English resource, please use use the original filename and **append a language identifier** to the file name, just before the file ending, separated by a dot `.`. Please use the official [ISO 639-1 (two letter) or ISO 630-2 (three letter)](https://www.loc.gov/standards/iso639-2/php/code_list.php) code to denote the language, written in lower case letters. Example:
  * English version: `README.md`
  * German version: `README.de.md`
  * French version: `README.fr.md`
  * Spanish version: `README.es.md`
  * ...

## Credits

- [Accessibility Club Team](https://accessibility-club.org/)
- [All Contributors](../../contributors)

## License

Licensed under the terms of [The Unlicense](LICENSE).

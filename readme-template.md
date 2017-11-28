# README.md Guidelines and Template

The purpose of this document is to provide guidelines and a template for creating a readme for all repos in the MyPureCloud group. The template below is a good place to start, but the format may be altered as long as the content requirements are still met. Add sections as appropriate for your project. The bulk of this readme may be replaced with wiki pages if the documentation is too extensive for a single readme.


# Guidelines

## Writing Style

* Be professional. No cursing and keep colloquial language to a minimum.
* Proofread your writing. Use a spell checker. It's always helpful to have someone else review for typos and grammatical errors.
* Include images and screenshots where beneficial. Github resizes images to 700px wide, plan accordingly to keep your screenshots readable inline.
* Consider everything in every repo to be public facing, even if it's private. Do not discuss anything that should be kept internal to Genesys. If the content must not ever be made public, use Bitbucket instead.


## Formatting

* Use a linear progression of headings (i.e. h1 > h2 > h3 > h4). Do not skip levels.
* Use markdown appropriately to format code and apply text styling. Use bold and italics sparingly.
* Precede all headings with two blank lines, except when directly following a parent heading, then use a single empty line.


_Copy the content below to start your readme._

------


# {Project Title}

Write a couple sentences up to a couple paragraphs summarizing the project.

If you have badges (e.g. http://shields.io/), put them here.


# Documentation

If any documentation exists outside of the readme, link to it here. This includes documentation in the repo's wiki.


# Table of Contents

For documents longer than 100 lines, provide a TOC linking headings 1-3 excluding headings before the TOC. Example:

* [Getting Started](#getting-started)
  * [TL;DR](#tldr)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Configuration](#configuration)
  * [Usage](#usage)
* [Additional Information](#additional-information)

_Pro-tip: Use this chrome extension to generate TOCs for you! Clone the repo and add the `src` directory as an [unpacked extension](https://developer.chrome.com/extensions/getstarted#unpacked). https://github.com/PrinceNebulon/GithubTocGenerator_


# Getting Started

## TL;DR

Provide a minimal cheat sheet documenting the minimum required steps to execute the project's happy path.


## Prerequisites

Document anything that the user must have or do prior to using the project. This should include required frameworks, environmental settings, and credentials.


## Installation

Document how to install the project if installation is required. Do not include this section if all that is required is cloning the repo.


## Configuration

Document all required and optional configuration steps that must be taken prior to using the project.


## Usage

Document how to actually run the project once it has been installed and configured.


# Additional Information

_TODO: provide boilerplate for these items_

Provide information about the following topics:

* Provide at least one method of contact external to Github for contacting the maintainers. This can be a person or group's email, a link to a specific topic or category on the developer forum, or any alternatives for external developers to get help outside of using Github issues.
* If PRs are accepted from the public. If yes, provide guidelines for PR submissions
* If issues are accepted via Github issues (turn the feature off if not)
* State the license and link to the repo's license (should be in `/LICENSE`)

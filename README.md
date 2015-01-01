# Overview

This repository contains UNOFFICIAL brews that have not been accepted
into the master branch.

These brews can be installed via the raw GitHub URLs, or by cloning this
repository locally and installing off the local disk. For more details
see the "using" section below.

It is maintained by Tim Gray and can be found at
<https://github.com/tgray/homebrew-tgbrew>.

A fuller set of alternative homebrew formulas can be found at
<https://github.com/adamv/homebrew-alt>.  Parts of this readme file were
lifted from the one found in the link above.

# Using

There are two ways to install packages from this repository.

## Using Raw URLs

First you need to get your hands on the raw URL. For example, the raw url for
the contacts formula is:

`https://raw.github.com/tgray/homebrew-tgbrew/master/contacts2.rb`


Pass that URL as a parameter to the `brew install` command, like so:

`brew install https://raw.github.com/tgray/homebrew-tgbrew/master/contacts2.rb`

## Cloning the Repository

Clone the repository to somewhere that you'll remember:

`git clone https://github.com/tgray/homebrew-tgbrew.git /usr/local/LibraryAlt`

This example creates a `LibraryAlt` directory under `/usr/local`.

Then to install a formula pass the full path to the formula into the
`brew install` command. Here's another example that installs princexml:

`brew install /usr/local/LibraryAlt/putmail.rb`

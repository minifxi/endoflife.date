---
title: Seafile Server Community
layout: post
category: service-app
changelogTemplate: "https://manual.seafile.com/changelog/server-changelog/"
releaseLabel: "Seafile Server Community Edition __RELEASE_CYCLE__"

# A list of releases, supported or not
# Newer releases go on top of the list, in order
releases:
    # Release range (usually major.minor), always put in quotes
    # Do not prefix with "v" or suffix with ".x"
    # This becomes part of our API URL, so try to keep this hyphenated, instead of using spaces
    # And use consistent case (lowercase prefered) if it uses words.
    # Do not add releases that are not considered "stable" (such as RC/Alpha/Beta/Nightly)
  - releaseCycle: "9.0"
    eol: 2022-12-31
    # End of Active Support for the product. This is where bugfixes usually stop coming in. (remove if activeSupportColumn=false)
    # Alternatively, set to true|false if it is not pre-decided
    support: 2022-12-31
    releaseDate: 2021-12-15
    latest: "9.0.9"
    latestReleaseDate: 2022-09-22
    discontinued: false
    link: https://manual.seafile.com/changelog/server-changelog/#909-2022-09-22
iconSlug: NA
permalink: /seafile-ce
releasePolicyLink: https://www.seafile.com/en/roadmap/
activeSupportColumn: true
releaseColumn: true
releaseDateColumn: true
eolColumn: End of Support
discontinuedColumn: true

# In the markdown section, ensure that the following are present:
# 1. A one line statement about what the product is, with a link to the primary website (in a quote)
# 2. A short summary of the release policy, pointing out the EoL policy as well, if available.
# 3. Any additional information that may be of interest
# See the Guiding Principles on the wiki (https://github.com/endoflife-date/endoflife.date/wiki/Guiding-Principles)
# on tone and voice for the text.

# If you are adding any images in the text, they might get blocked due to our CSP
# Prefer using releaseImage in such cases.
# Images on the same website as releaseImage will not be blocked.

# Please leave a newline both above and below the triple-dashes

---

> [Seafile](https://www.seafile.com/en/home/) is an open-source, cross-platform file-hosting software system.

Seafile has several components, like the server, the mobile device client or the desktop client. Latest release is version 9.0.

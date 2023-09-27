

# Revisioning

This module channels unpublished content as well as edits to current content
into a queue for review by a moderator/publisher prior to becoming "live", i.e.
visible to the public.

We took our inspiration from the Revision Moderation module by Angie Byron,
but found that a patch could not implement the deviating functionality our
customers required, which would change the current behaviour of the RM module
and surprise existing users.

The Revisioning module now comes with two user interface models to chose from:
"traditional" and "updated".

Traditional: The traditional UI model is enabled by default. With the standard
UI, the emphasis is on minimizing the number of controls, so each page is free
of buttons and links that are not immediately relevant.

Updated: The updated UI model can be selected by enabling the "revisioning_ux"
submodule. In the updated UI, the emphasis is on maintaining consistent
navigation controls.  This allows revision moderators to flip between the tabs
on the revisions operations page without ending up on a page that no longer
contains all of the tabs formerly available.

There are no database schema differences between the two UI models; you may
enable revisioning_ux, try it out, and later go back to the traditional model
without any difficulty.


## Installation and Configuration
- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules

- Step-by-step instructions can be found in the tutorials listed on the
Drupal Revisioning project page, http://drupal.org/project/revisioning.

## Credits
- Current Drupal version maintainers: 
- [RdeBoer](https://www.drupal.org/u/rdeboer)
- Drupal Revisioning UX: 
- [greg.1.anderson](https://www.drupal.org/user/438598)

## Current Backdrop maintainer
- [pgrayove-mcpl](https://github.com/pgrayove-mcpl)
- Seeking additional maintainers

## License
This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
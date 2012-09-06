# Toadstool Changelog
## Aug. 31 2012
* Added support for non-core modernizr features
** boxsizing - necessary for grid solution
** lastchild

## Sept. 6 2012
* Added .rvmrc - I know, should have done this a long time ago.

## Aug. 30 2012
* Moved color defaults to control under Toadstool style guide
* Updates tempalte markup so that css is not leveraging generic tags. Corrected issues where styles were stomping on prototype views

## Aug, 13 2012
* Updates required to meet specification of 0.0.2.8 Stipe gem update

## Aug 9, 2012
* Updated `public/javascripts/application.js` with support for creating hex values on the fly in the browser for the colors view
* Updated navigation, consolidated abstract and semantic colors view (still need to complete semantic swatches)
* BUG: Colors in the view are being pulled from Stipe, not the Toadstool styleguide.   
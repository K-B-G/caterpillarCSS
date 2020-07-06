# caterpillarCSS
Simple ungrided css layout system for prototyping and final design; IE8 compatible. 
The main philosphy of this system is the following:
  1. Follow DRY (Don't Repeate Yourself) and KISS (Keep It Simple Stupid) methods
  2. Keep presentation looks off of block and layout classes. Just apply another class on the element for other presentatoinal looks. 
  3. Inherit base font as much as possible; that is set the base font on the wrapper and only change it on elements that NEED it. Websites should only have a max of 3 fonts anyways.
  4. Design with core 2.1 CSS first, then add fancy CSS3 swag. This helps with gracefule degredation and means your site will look good in browers that don't support CSS3 stuff.

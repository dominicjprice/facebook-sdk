0.4.1 / 2015-06-24
==================

  * Using ppx\_meta\_conv instead of meta_conv
  * Updated to work with cohttp 0.18.0+ 

0.4.0 / 2014-11-14
==================

  * Removed dependency on Core, now depends on Core\_kernel.
  * Changed names for packed modules:
    * Facebook -> Sociaml\_facebook\_api
    * Endpoints -> Sociaml\_facebook\_api\_endpoints
  * Changed parent findlib package name: facebook -> sociaml\_facebook\_api
  * Requires cohttp >= 0.12.0
  
0.3.5 / 2014-05-14
==================

  * Facebook changed the url parameter when requesting permissions.

0.3.4 / 2014-04-28
==================

  * Added function to generate access token exchange uri.

0.3.3 / 2014-04-27
==================

  * Cleared up typo in previous release.

0.3.2 / 2014-04-27
==================

  * Added friend endpoint.

0.3.1 / 2014-04-08
==================

  * Breaking API changes.
  * Using Meta Conv for JSON decoding now.

0.2.12 / 2014-03-10
==================

  * Added ocaml version constraint to 4.01.0

0.2.11 / 2014-03-10
==================

  * Added lwt as an Opam dependency.

0.2.10 / 2014-03-10
==================

  * Added cohhtp version constraint and ssl as an Opam dependency.

0.2.9 / 2014-03-10
==================

  * Rename to facebook-sdk.

0.2.8 / 2014-03-07
==================

  * Updated to match Cohttp API version 0.10.0.

0.2.7 / 2014-03-07
==================

  * Added Bolt logging.

0.2.6 / 2014-03-01
==================

  * Expose Util module.

0.2.5 / 2014-02-28
==================

  * Updated META file with correct version.

0.2.4 / 2014-02-28
==================

  * Correct error in build script.

0.2.3 / 2014-02-28
==================

  * Expose Types\_ext module.

0.2.2 / 2014-02-28
==================

  * Modified opam uninstall to remove library with findlib.

0.2.1 / 2014-02-28
==================

  * Modified the build with a different directory structure.

0.2.0 / 2014-02-28
==================

  * Git repository rename and findlib package name changed to facebook
    rather than Ofacebook.

0.1.0 / 2014-02-21
==================

  * Initial version, contains functionality to fetch a user's timeline.

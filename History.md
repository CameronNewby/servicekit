Major Revisions
===============

2.1.0 / 2018-07-16
------------------

- Allow Watson Conversation service to return multiple intents
- Update `mocha` to latest version fixing Critical Command Injection vulnerability in `npm audit`
- Various other minor package updates


2.0.1 / 2018-01-02
------------------

- Breaking Changes due to update to watson-developer-cloud v3.x
- Removed sunset Watson services Alchemy and Retrieve and Rank
- Updated to major versions for debug, sinon and watson-developer-cloud
- Updated Tone Analyzer to support latest API 2017-09-21


1.3.0 / 2017-07-26
------------------

- Added support for Recast.ai services


1.2.0 / 2016-12-19
------------------

- Added support for IBM Watson Tone Analyzer service


1.0.0 / 2016-11-06
------------------

- Breaking changes to wit interface. 
  - The wit message service is now accessible at `require('wit/message')` so change `require('wit')` to `require('wit/message')` after upgrade.
- Added `wit.converse` or `require('wit/converse')`
- Removed deprecated `wit.message`
- Removed deprecated `conversation.message`


0.2.1 / 2016-11-05
------------------

- Modernise conversation and wit services. Further simplify their interface
  - deprecate usage of `wit.message()`, instead use `wit()` directly.
  - deprecate usage of `conversation.message()`, instead use `conversation()` directly.


0.2.0 / 2016-11-05
------------------

-	Added bing spell check service


0.1.1 / 2016-10-24
------------------

-	Added wit service


0.0.1 / 2016-10-20
------------------

-	Project created

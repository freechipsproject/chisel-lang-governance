Authors: Jack Koenig, Schuyler Eldridge

Inspired by:
https://scala-lang.org/contribute/codereviews.html


## Reviewer Mindset

* The author of this PR cared enough about this project to try to improve it!
* You are reviewing the PR, not the author.

## Reviewer Guidelines

* Be kind, courteous, and respectful of others.
* Keep comments on-topic, concise, and precise.
  * Attach comments to particular lines whenever possible.
  * Use short code examples instead of descriptive prose.
* If a particular section of code does not make sense to you, ask for clarification from the author or suggest changes to the structure.
* If you have thoroughly reviewed the PR and thought about it from all angles, approve it.
* Additional reviews, if any, should address angles *not addressed by the original review.*
* If you have approved the PR and the author is not a freechipsproject member, then merge it following the merge strategy requested by the author.
* If you are uncomfortable reviewing a particular piece of code, @mention someone to help.

## Questions a Reviewer Should Think About

* Does this PR test what it’s doing?
  * Added or changed features should be thoroughly tested. 
* Does this PR document public APIs?
  * New or modified public APIs are easier to document when added or when modified.
* Does this PR align with the existing style guide?
  * New or modified code should align with existing code conventions. 
* Is there a better Scala way to do this?
  * Syntax/style changes or code simplifications that are more subjectively elegant are good to encourage to improve the quality of the project and to increase the author’s language knowledge. 
* Are there performance implications related to this PR?
  * While often the most difficult to reason about, this is critical for large projects dependent upon this project. Feel free to @mention those building large designs to ask them to test this PR.
* Can this PR be rebased into a better patch series?
  * Ideal PRs are a short, logical series of non-broken commits that do not require a huge cognitive load on the reviewer. 
  * *Note: this suggestion is likely only to be used for large PRs (>1000 lines of code) authored by experienced developers. Asking a first time contributor to rebase will only alienate the author.*

## Minimum Approval Requirements

* The PR must pass regression tests.
  * If regression tests must be waived for a dependent project (e.g., [skip chisel tests] for a FIRRTL PR), then a PR fixing the dependent project must be also filed for the dependent project.
* The PR must add documentation to any new, public APIs.

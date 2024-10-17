[![CodeQL](https://github.com/Nick2bad4u/StravaAutoAuthorize/actions/workflows/codeql.yml/badge.svg)](https://github.com/Nick2bad4u/StravaAutoAuthorize/actions/workflows/codeql.yml)
[![Dependabot Updates](https://github.com/Nick2bad4u/StravaAutoAuthorize/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/Nick2bad4u/StravaAutoAuthorize/actions/workflows/dependabot/dependabot-updates)
[![Dependency Review](https://github.com/Nick2bad4u/StravaAutoAuthorize/actions/workflows/dependency-review.yml/badge.svg)](https://github.com/Nick2bad4u/StravaAutoAuthorize/actions/workflows/dependency-review.yml)
[![pages-build-deployment](https://github.com/Nick2bad4u/StravaAutoAuthorize/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/Nick2bad4u/StravaAutoAuthorize/actions/workflows/pages/pages-build-deployment)
[![Scorecard supply-chain security](https://github.com/Nick2bad4u/StravaAutoAuthorize/actions/workflows/scorecards.yml/badge.svg)](https://github.com/Nick2bad4u/StravaAutoAuthorize/actions/workflows/scorecards.yml)

![RepoBeats](https://repobeats.axiom.co/api/embed/a9801c5f4cd4fa2067c257523bb61d7f73005bac.svg "Repobeats analytics image")
# StravaAutoAuthorize
Auto authorizes Strava apps via GreaseMoney or Tampermonkey

    // ==UserScript==
    // @name         Strava-Auto-Authorize
    // @namespace    nick2bad4u
    // @description  Auto allows Strava apps without having to click "authorize" every single time.
    // @author       Nick2bad4u
    // @match        https://www.strava.com/oauth/authorize*
    // @icon         https://www.google.com/s2/favicons?sz=64&domain=strava.com
    // @version      2.0
    // @grant        none
    // @homepage     https://github.com/Nick2bad4u/StravaAutoAuthorize
    // @homepageURL  https://github.com/Nick2bad4u/StravaAutoAuthorize
    // @supportURL   https://github.com/Nick2bad4u/StravaAutoAuthorize/issues
    // @downloadURL  https://raw.githubusercontent.com/Nick2bad4u/StravaAutoAuthorize/main/StravaAutoAuthorize.js
    // @license CC-BY-SA-3.0; http://creativecommons.org/licenses/by-sa/3.0/
    // @license MIT
    // ==/UserScript==

    setTimeout(function() {
        document.getElementsByClassName("btn")[0].click();
    }, 1000)

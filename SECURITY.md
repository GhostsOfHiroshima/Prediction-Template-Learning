# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
<html lang="en"><head><style>
details, summary {
  display: block;
}
details:not([open]) > *:not(summary) {
  display: none;
}
summary::before {
  content: "►";
  padding-right: 0.3rem;
  font-size: 0.6rem;
  cursor: default;
}
[open] > summary::before {
  content: "▼";
}
</style>
    <meta charset="utf-8">
  <link href="https://github.githubassets.com" rel="dns-prefetch">
  <link href="https://avatars0.githubusercontent.com" rel="dns-prefetch">
  <link href="https://avatars1.githubusercontent.com" rel="dns-prefetch">
  <link href="https://avatars2.githubusercontent.com" rel="dns-prefetch">
  <link href="https://avatars3.githubusercontent.com" rel="dns-prefetch">
  <link href="https://github-cloud.s3.amazonaws.com" rel="dns-prefetch">
  <link href="https://user-images.githubusercontent.com/" rel="dns-prefetch">



  <link href="https://github.githubassets.com/assets/frameworks-e7318add1f7e055d040edb0f75aaa0ba.css" rel="stylesheet" media="all" integrity="sha512-67V2J9Se2CifJlftk9/cExHGvxd7N9b9EdGnQEpszu99Ogeecilu9jIDxoCkx3zNLfB9ArraXW0J03qyVmN0Uw==" crossorigin="anonymous">
  
    <link href="https://github.githubassets.com/assets/github-3068294d3d7a8d980f694e5c220c746e.css" rel="stylesheet" media="all" integrity="sha512-3P571Vspzc1UUlXE1URjuTl7D7R7Nc+rrVpvTqGryUtC+VHDSExSBujZ4Zq0MCZSar/FtObOgqOcm0WP/hwzqw==" crossorigin="anonymous">
    
    
    
    

  <meta name="viewport" content="width=device-width">
  
  <title>New File</title>
    <meta name="description" content="C(ontinued)-MaNGOS is about: -- Doing WoW-Emulation Right!  - cmangos/mangos-tbc">
    <link title="GitHub" href="/opensearch.xml" rel="search" type="application/opensearchdescription+xml">
  <link title="GitHub" href="https://github.com/fluidicon.png" rel="fluid-icon">
  <meta content="1401488693436528" property="fb:app_id">

    <meta name="twitter:image:src" content="https://avatars0.githubusercontent.com/u/2212917?s=400&amp;v=4"><meta name="twitter:site" content="@github"><meta name="twitter:card" content="summary"><meta name="twitter:title" content="cmangos/mangos-tbc"><meta name="twitter:description" content="C(ontinued)-MaNGOS is about: -- Doing WoW-Emulation Right!  - cmangos/mangos-tbc">
    <meta content="https://avatars0.githubusercontent.com/u/2212917?s=400&amp;v=4" property="og:image"><meta content="GitHub" property="og:site_name"><meta content="object" property="og:type"><meta content="cmangos/mangos-tbc" property="og:title"><meta content="https://github.com/cmangos/mangos-tbc" property="og:url"><meta content="C(ontinued)-MaNGOS is about: -- Doing WoW-Emulation Right!  - cmangos/mangos-tbc" property="og:description">

  <link href="https://github.githubassets.com/" rel="assets">
  <link href="wss://live.github.com/_sockets/VjI6NDIwNDgyNDAzOjRjZGJmMGQzMGJlMDZiOGI3ZTJkZDI4NjFmNjkzMjI2MzM5N2I4OTRmZDlhNzI3YzA5M2Q2NThkYmM5YzU1NGE=--407be64671fd63cdca63ee0e693ec264a905437c" rel="web-socket">
  <meta name="pjax-timeout" content="1000">
  <link href="/sessions/sudo_modal" rel="sudo-modal">
  <meta name="request-id" content="D31C:7535:1A892BC:2BCA714:5D190311" data-pjax-transient="">


  

  <meta name="selected-link" data-pjax-transient="" value="repo_source">

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com"><meta name="octolytics-app-id" content="github"><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event"><meta name="octolytics-dimension-request_id" content="D31C:7535:1A892BC:2BCA714:5D190311"><meta name="octolytics-dimension-region_edge" content="iad"><meta name="octolytics-dimension-region_render" content="iad"><meta name="octolytics-actor-id" content="51129449"><meta name="octolytics-actor-login" content="GhostsOfHiroshima"><meta name="octolytics-actor-hash" content="635043ed2fbfc2bcf031e5ac99904bd997218d084cb3c8eac9153d234277dfbc">
<meta name="analytics-location" content="/<user-name>/<repo-name>/blob/new" data-pjax-transient="true">




  <meta name="userId" class="js-ga-set" content="b02852514e16e284d78da75de2aba47d">

<meta name="dimension1" class="js-ga-set" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="GhostsOfHiroshima">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="OWJmY2ZlNmY4OGYxNTI1ZWY5NDUzMjM1NGQ5MDM1YjliNWQ1NGIzNmMwNGQxZjBkMWJkMzg0MGZhYjhhM2ZmY3x7InJlbW90ZV9hZGRyZXNzIjoiNzIuMTc3LjEzNy4yMjQiLCJyZXF1ZXN0X2lkIjoiRDMxQzo3NTM1OjFBODkyQkM6MkJDQTcxNDo1RDE5MDMxMSIsInRpbWVzdGFtcCI6MTU2MTkyMDI3NSwiaG9zdCI6ImdpdGh1Yi5jb20ifQ==">

    <meta name="enabled-features" content="MARKETPLACE_FEATURED_BLOG_POSTS,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PULL_PANDA_HOMEPAGE,NOTIFY_ON_BLOCK,RELATED_ISSUES,DISPLAY_COMMENTER_FULL_NAME">

  <meta name="html-safe-nonce" content="26321eac85e13b3c23f69fa3d3278fcfcd277feb">

  <meta http-equiv="x-pjax-version" content="3af93b0c6a968d47c0de05d7c77eca32">
  

      <link title="Recent Commits to mangos-tbc:master" href="https://github.com/cmangos/mangos-tbc/commits/master.atom" rel="alternate" type="application/atom+xml">

  <meta name="go-import" content="github.com/cmangos/mangos-tbc git https://github.com/cmangos/mangos-tbc.git">

  <meta name="octolytics-dimension-user_id" content="2212917"><meta name="octolytics-dimension-user_login" content="cmangos"><meta name="octolytics-dimension-repository_id" content="6829204"><meta name="octolytics-dimension-repository_nwo" content="cmangos/mangos-tbc"><meta name="octolytics-dimension-repository_public" content="true"><meta name="octolytics-dimension-repository_is_fork" content="false"><meta name="octolytics-dimension-repository_network_root_id" content="6829204"><meta name="octolytics-dimension-repository_network_root_nwo" content="cmangos/mangos-tbc"><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false">




  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link href="https://github.githubassets.com/pinned-octocat.svg" rel="mask-icon" color="#000000">
  <link class="js-site-favicon" href="https://github.githubassets.com/favicon.ico" rel="icon" type="image/x-icon">

<meta name="theme-color" content="#1e2327">

  <meta name="msapplication-TileImage" content="/windows-tile.png">
  <meta name="msapplication-TileColor" content="#ffffff">




  <link href="/manifest.json" rel="manifest" crossorigin="use-credentials">

  </head>

  <body class="logged-in env-production page-responsive page-edit-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a tabindex="1" class="p-3 bg-blue text-white show-on-focus js-skip-to-content" href="#start-of-content">Skip to content</a>
    <div class="pjax-loader-bar" id="js-pjax-loader-bar"><div class="progress"></div></div>

    
    
    


          <header class="Header js-details-container Details flex-wrap flex-lg-nowrap p-responsive" role="banner">

    <div class="Header-item d-none d-lg-flex">
      <a class="Header-link" aria-label="Homepage" href="https://github.com/" data-ga-click="Header, go to dashboard, icon:logo" data-hotkey="g d">
  <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-mark-github v-align-middle" aria-hidden="true" viewBox="0 0 16 16" width="32" height="32" version="1.1"><path fill-rule="evenodd" d="M 8 0 C 3.58 0 0 3.58 0 8 c 0 3.54 2.29 6.53 5.47 7.59 c 0.4 0.07 0.55 -0.17 0.55 -0.38 c 0 -0.19 -0.01 -0.82 -0.01 -1.49 c -2.01 0.37 -2.53 -0.49 -2.69 -0.94 c -0.09 -0.23 -0.48 -0.94 -0.82 -1.13 c -0.28 -0.15 -0.68 -0.52 -0.01 -0.53 c 0.63 -0.01 1.08 0.58 1.23 0.82 c 0.72 1.21 1.87 0.87 2.33 0.66 c 0.07 -0.52 0.28 -0.87 0.51 -1.07 c -1.78 -0.2 -3.64 -0.89 -3.64 -3.95 c 0 -0.87 0.31 -1.59 0.82 -2.15 c -0.08 -0.2 -0.36 -1.02 0.08 -2.12 c 0 0 0.67 -0.21 2.2 0.82 c 0.64 -0.18 1.32 -0.27 2 -0.27 c 0.68 0 1.36 0.09 2 0.27 c 1.53 -1.04 2.2 -0.82 2.2 -0.82 c 0.44 1.1 0.16 1.92 0.08 2.12 c 0.51 0.56 0.82 1.27 0.82 2.15 c 0 3.07 -1.87 3.75 -3.65 3.95 c 0.29 0.25 0.54 0.73 0.54 1.48 c 0 1.07 -0.01 1.93 -0.01 2.2 c 0 0.21 0.15 0.46 0.55 0.38 A 8.013 8.013 0 0 0 16 8 c 0 -4.42 -3.58 -8 -8 -8 Z" /></svg>
</a>

    </div>

    <div class="Header-item d-lg-none">
      <button class="Header-link btn-link js-details-target" aria-expanded="false" aria-label="Toggle navigation" type="button">
        <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-three-bars" aria-hidden="true" viewBox="0 0 12 16" width="18" height="24" version="1.1"><path fill-rule="evenodd" d="M 11.41 9 H 0.59 C 0 9 0 8.59 0 8 c 0 -0.59 0 -1 0.59 -1 H 11.4 c 0.59 0 0.59 0.41 0.59 1 c 0 0.59 0 1 -0.59 1 h 0.01 Z m 0 -4 H 0.59 C 0 5 0 4.59 0 4 c 0 -0.59 0 -1 0.59 -1 H 11.4 c 0.59 0 0.59 0.41 0.59 1 c 0 0.59 0 1 -0.59 1 h 0.01 Z M 0.59 11 H 11.4 c 0.59 0 0.59 0.41 0.59 1 c 0 0.59 0 1 -0.59 1 H 0.59 C 0 13 0 12.59 0 12 c 0 -0.59 0 -1 0.59 -1 Z" /></svg>
      </button>
    </div>

    <div class="Header-item Header-item--full flex-column flex-lg-row width-full flex-order-2 flex-lg-order-none mr-0 mr-lg-3 mt-3 mt-lg-0 Details-content--hidden">
        <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative js-jump-to" role="combobox" aria-expanded="false" aria-haspopup="listbox" aria-owns="jump-to-results" aria-label="Search or jump to">
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --><form class="js-site-search-form" role="search" aria-label="Site" action="/cmangos/mangos-tbc/search" method="get" accept-charset="UTF-8" data-unscoped-search-url="/search" data-scoped-search-url="/cmangos/mangos-tbc/search" data-scope-id="6829204" data-scope-type="Repository"><input name="utf8" type="hidden" value="✓">
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input name="q" class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable" aria-controls="jump-to-results" spellcheck="false" aria-autocomplete="list" aria-label="Search or jump to…" type="text" placeholder="Search or jump to…" value="" autocomplete="off" autocapitalize="off" data-hotkey="s,/" data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=LQOSgTHedWE3y1cXjRFOlSIzYWD/dQ0xTqGt6fjrkOmVBG6hgrhmP72mgC/Wg4u1ro3hWT9r1ON5d+qRffgX1g==" data-scoped-placeholder="Search or jump to…" data-unscoped-placeholder="Search or jump to…">
          <input name="type" class="js-site-search-type-field" type="hidden">
            <img class="mr-2 header-search-key-slash" alt="" src="https://github.githubassets.com/images/search-key-slash.svg">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg xmlns="http://www.w3.org/2000/svg" title="Repository" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" role="img" aria-label="Repository" viewBox="0 0 12 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 4 9 H 3 V 8 h 1 v 1 Z m 0 -3 H 3 v 1 h 1 V 6 Z m 0 -2 H 3 v 1 h 1 V 4 Z m 0 -2 H 3 v 1 h 1 V 2 Z m 8 -1 v 12 c 0 0.55 -0.45 1 -1 1 H 6 v 2 l -1.5 -1.5 L 3 16 v -2 H 1 c -0.55 0 -1 -0.45 -1 -1 V 1 c 0 -0.55 0.45 -1 1 -1 h 10 c 0.55 0 1 0.45 1 1 Z m -1 10 H 1 v 2 h 2 v -1 h 3 v 1 h 5 v -2 Z m 0 -10 H 2 v 9 h 9 V 1 Z" /></svg>
      <svg xmlns="http://www.w3.org/2000/svg" title="Project" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" role="img" aria-label="Project" viewBox="0 0 15 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 10 12 h 3 V 2 h -3 v 10 Z m -4 -2 h 3 V 2 H 6 v 8 Z m -4 4 h 3 V 2 H 2 v 12 Z m -1 1 h 13 V 1 H 1 v 14 Z M 14 0 H 1 a 1 1 0 0 0 -1 1 v 14 a 1 1 0 0 0 1 1 h 13 a 1 1 0 0 0 1 -1 V 1 a 1 1 0 0 0 -1 -1 Z" /></svg>
      <svg xmlns="http://www.w3.org/2000/svg" title="Search" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" role="img" aria-label="Search" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 15.7 13.3 l -3.81 -3.83 A 5.93 5.93 0 0 0 13 6 c 0 -3.31 -2.69 -6 -6 -6 S 1 2.69 1 6 s 2.69 6 6 6 c 1.3 0 2.48 -0.41 3.47 -1.11 l 3.83 3.81 c 0.19 0.2 0.45 0.3 0.7 0.3 c 0.25 0 0.52 -0.09 0.7 -0.3 a 0.996 0.996 0 0 0 0 -1.41 v 0.01 Z M 7 10.7 c -2.59 0 -4.7 -2.11 -4.7 -4.7 c 0 -2.59 2.11 -4.7 4.7 -4.7 c 2.59 0 4.7 2.11 4.7 4.7 c 0 2.59 -2.11 4.7 -4.7 4.7 Z" /></svg>
    </div>

    <img width="28" height="28" class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" aria-label="Team" alt="" src="">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span class="d-inline-block ml-1 v-align-middle" aria-hidden="true">↵</span>
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump" aria-hidden="true">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container" id="jump-to-results" role="listbox">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg xmlns="http://www.w3.org/2000/svg" title="Repository" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" role="img" aria-label="Repository" viewBox="0 0 12 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 4 9 H 3 V 8 h 1 v 1 Z m 0 -3 H 3 v 1 h 1 V 6 Z m 0 -2 H 3 v 1 h 1 V 4 Z m 0 -2 H 3 v 1 h 1 V 2 Z m 8 -1 v 12 c 0 0.55 -0.45 1 -1 1 H 6 v 2 l -1.5 -1.5 L 3 16 v -2 H 1 c -0.55 0 -1 -0.45 -1 -1 V 1 c 0 -0.55 0.45 -1 1 -1 h 10 c 0.55 0 1 0.45 1 1 Z m -1 10 H 1 v 2 h 2 v -1 h 3 v 1 h 5 v -2 Z m 0 -10 H 2 v 9 h 9 V 1 Z" /></svg>
      <svg xmlns="http://www.w3.org/2000/svg" title="Project" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" role="img" aria-label="Project" viewBox="0 0 15 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 10 12 h 3 V 2 h -3 v 10 Z m -4 -2 h 3 V 2 H 6 v 8 Z m -4 4 h 3 V 2 H 2 v 12 Z m -1 1 h 13 V 1 H 1 v 14 Z M 14 0 H 1 a 1 1 0 0 0 -1 1 v 14 a 1 1 0 0 0 1 1 h 13 a 1 1 0 0 0 1 -1 V 1 a 1 1 0 0 0 -1 -1 Z" /></svg>
      <svg xmlns="http://www.w3.org/2000/svg" title="Search" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" role="img" aria-label="Search" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 15.7 13.3 l -3.81 -3.83 A 5.93 5.93 0 0 0 13 6 c 0 -3.31 -2.69 -6 -6 -6 S 1 2.69 1 6 s 2.69 6 6 6 c 1.3 0 2.48 -0.41 3.47 -1.11 l 3.83 3.81 c 0.19 0.2 0.45 0.3 0.7 0.3 c 0.25 0 0.52 -0.09 0.7 -0.3 a 0.996 0.996 0 0 0 0 -1.41 v 0.01 Z M 7 10.7 c -2.59 0 -4.7 -2.11 -4.7 -4.7 c 0 -2.59 2.11 -4.7 4.7 -4.7 c 2.59 0 4.7 2.11 4.7 4.7 c 0 2.59 -2.11 4.7 -4.7 4.7 Z" /></svg>
    </div>

    <img width="28" height="28" class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" aria-label="Team" alt="" src="">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span class="d-inline-block ml-1 v-align-middle" aria-hidden="true">↵</span>
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump" aria-hidden="true">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg xmlns="http://www.w3.org/2000/svg" title="Repository" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" role="img" aria-label="Repository" viewBox="0 0 12 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 4 9 H 3 V 8 h 1 v 1 Z m 0 -3 H 3 v 1 h 1 V 6 Z m 0 -2 H 3 v 1 h 1 V 4 Z m 0 -2 H 3 v 1 h 1 V 2 Z m 8 -1 v 12 c 0 0.55 -0.45 1 -1 1 H 6 v 2 l -1.5 -1.5 L 3 16 v -2 H 1 c -0.55 0 -1 -0.45 -1 -1 V 1 c 0 -0.55 0.45 -1 1 -1 h 10 c 0.55 0 1 0.45 1 1 Z m -1 10 H 1 v 2 h 2 v -1 h 3 v 1 h 5 v -2 Z m 0 -10 H 2 v 9 h 9 V 1 Z" /></svg>
      <svg xmlns="http://www.w3.org/2000/svg" title="Project" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" role="img" aria-label="Project" viewBox="0 0 15 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 10 12 h 3 V 2 h -3 v 10 Z m -4 -2 h 3 V 2 H 6 v 8 Z m -4 4 h 3 V 2 H 2 v 12 Z m -1 1 h 13 V 1 H 1 v 14 Z M 14 0 H 1 a 1 1 0 0 0 -1 1 v 14 a 1 1 0 0 0 1 1 h 13 a 1 1 0 0 0 1 -1 V 1 a 1 1 0 0 0 -1 -1 Z" /></svg>
      <svg xmlns="http://www.w3.org/2000/svg" title="Search" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" role="img" aria-label="Search" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 15.7 13.3 l -3.81 -3.83 A 5.93 5.93 0 0 0 13 6 c 0 -3.31 -2.69 -6 -6 -6 S 1 2.69 1 6 s 2.69 6 6 6 c 1.3 0 2.48 -0.41 3.47 -1.11 l 3.83 3.81 c 0.19 0.2 0.45 0.3 0.7 0.3 c 0.25 0 0.52 -0.09 0.7 -0.3 a 0.996 0.996 0 0 0 0 -1.41 v 0.01 Z M 7 10.7 c -2.59 0 -4.7 -2.11 -4.7 -4.7 c 0 -2.59 2.11 -4.7 4.7 -4.7 c 2.59 0 4.7 2.11 4.7 4.7 c 0 2.59 -2.11 4.7 -4.7 4.7 Z" /></svg>
    </div>

    <img width="28" height="28" class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" aria-label="Team" alt="" src="">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span class="d-inline-block ml-1 v-align-middle" aria-hidden="true">↵</span>
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump" aria-hidden="true">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


    <li class="d-flex flex-justify-center flex-items-center p-0 f5 js-jump-to-suggestion">
      <img width="28" class="m-2" alt="Octocat Spinner Icon" src="https://github.githubassets.com/images/spinners/octocat-spinner-128.gif">
    </li>
</ul>

            </div>
      </label>
</form>  </div>
</div>


      <nav class="d-flex flex-column flex-lg-row flex-self-stretch flex-lg-self-auto" aria-label="Global">
    <a class="Header-link d-block d-lg-none py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" aria-label="Dashboard" href="/dashboard" data-ga-click="Header, click, Nav menu - item:dashboard:user">
      Dashboard
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" aria-label="Pull requests you created" href="/pulls" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
    Pull requests
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" aria-label="Issues you created" href="/issues" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
    Issues
</a>
    <div class="mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15">
      <a class="js-selected-navigation-item Header-link" href="/marketplace" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-selected-links=" /marketplace" data-octo-dimensions="location:nav_bar" data-octo-click="marketplace_click">
        Marketplace
</a>      
    </div>

  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" href="/explore" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore">
    Explore
</a>

    <a class="Header-link d-block d-lg-none mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" aria-expanded="false" aria-haspopup="false" aria-label="View profile and more" href="https://github.com/GhostsOfHiroshima">
      <img width="20" height="20" class="avatar" alt="@GhostsOfHiroshima" src="https://avatars2.githubusercontent.com/u/51129449?s=40&amp;v=4">
      GhostsOfHiroshima
</a>
    <!-- '"` --><!-- </textarea></xmp> --><form action="/logout" method="post" accept-charset="UTF-8"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="rWYwmy6A6kajArBDCAM6Nr/39FP37/4p2HAvEuo4Ujp5SqfSjrbiV3A3qWsrHmVHr009iJKJLPOxYwg6Lr21hw==">
      <button class="Header-link mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15 d-lg-none btn-link d-block width-full text-left" style="padding-left: 2px;" type="submit" data-ga-click="Header, sign out, icon:logout">
        <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-sign-out v-align-middle" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 9 V 7 H 8 V 5 h 4 V 3 l 4 3 l -4 3 Z m -2 3 H 6 V 3 L 2 1 h 8 v 3 h 1 V 1 c 0 -0.55 -0.45 -1 -1 -1 H 1 C 0.45 0 0 0.45 0 1 v 11.38 c 0 0.39 0.22 0.73 0.55 0.91 L 6 16.01 V 13 h 4 c 0.55 0 1 -0.45 1 -1 V 8 h -1 v 4 Z" /></svg>
        Sign out
      </button>
</form></nav>

    </div>

    <div class="Header-item Header-item--full flex-justify-center d-lg-none position-relative">
      <div class="css-truncate css-truncate-target width-fit position-absolute left-0 right-0 text-center">
              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-repo" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 4 9 H 3 V 8 h 1 v 1 Z m 0 -3 H 3 v 1 h 1 V 6 Z m 0 -2 H 3 v 1 h 1 V 4 Z m 0 -2 H 3 v 1 h 1 V 2 Z m 8 -1 v 12 c 0 0.55 -0.45 1 -1 1 H 6 v 2 l -1.5 -1.5 L 3 16 v -2 H 1 c -0.55 0 -1 -0.45 -1 -1 V 1 c 0 -0.55 0.45 -1 1 -1 h 10 c 0.55 0 1 0.45 1 1 Z m -1 10 H 1 v 2 h 2 v -1 h 3 v 1 h 5 v -2 Z m 0 -10 H 2 v 9 h 9 V 1 Z" /></svg>
    <a class="Header-link" href="/cmangos">cmangos</a>
    /
    <a class="Header-link" href="/cmangos/mangos-tbc">mangos-tbc</a>

</div>
    </div>

    <div class="Header-item position-relative d-none d-lg-flex">
      

    </div>

    <div class="Header-item mr-0 mr-lg-3 flex-order-1 flex-lg-order-none">
      

    <a class="Header-link notification-indicator position-relative tooltipped tooltipped-s js-socket-channel js-notification-indicator" aria-label="You have no unread notifications" href="/notifications" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n" data-channel="notification-changed:51129449">
        <span class="mail-status "></span>
        <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-bell" aria-hidden="true" viewBox="0 0 14 16" width="14" height="16" version="1.1"><path fill-rule="evenodd" d="M 14 12 v 1 H 0 v -1 l 0.73 -0.58 c 0.77 -0.77 0.81 -2.55 1.19 -4.42 C 2.69 3.23 6 2 6 2 c 0 -0.55 0.45 -1 1 -1 s 1 0.45 1 1 c 0 0 3.39 1.23 4.16 5 c 0.38 1.88 0.42 3.66 1.19 4.42 l 0.66 0.58 H 14 Z m -7 4 c 1.11 0 2 -0.89 2 -2 H 5 c 0 1.11 0.89 2 2 2 Z" /></svg>
</a>
    </div>


    <div class="Header-item position-relative d-none d-lg-flex">
      <details class="details-overlay details-reset">
  <summary tabindex="0" class="Header-link" role="button" aria-expanded="false" aria-haspopup="menu" aria-label="Create new…" data-ga-click="Header, create new, icon:add">
    <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-plus" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 9 H 7 v 5 H 5 V 9 H 0 V 7 h 5 V 2 h 2 v 5 h 5 v 2 Z" /></svg> <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw" role="menu">
    
<a class="dropdown-item" role="menuitem" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" role="menuitem" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a class="dropdown-item" role="menuitem" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a class="dropdown-item" role="menuitem" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>




  </details-menu>
</details>

    </div>

    <div class="Header-item position-relative mr-0 d-none d-lg-flex">
      
<details class="details-overlay details-reset">
  <summary tabindex="0" class="Header-link" role="button" aria-expanded="false" aria-haspopup="menu" aria-label="View profile and more" data-ga-click="Header, show menu, icon:avatar">
    <img width="20" height="20" class="avatar" alt="@GhostsOfHiroshima" src="https://avatars2.githubusercontent.com/u/51129449?s=40&amp;v=4">
    <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw mt-2" role="menu" style="width: 180px">
    <div class="header-nav-current-user css-truncate"><a class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" role="menuitem" href="/GhostsOfHiroshima" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">GhostsOfHiroshima</strong></a></div>
    <div class="dropdown-divider" role="none"></div>

      <div class="pl-3 pr-3 f6 user-status-container js-user-status-context pb-1" data-url="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1">
        
<div class="js-user-status-container&#10;    user-status-compact rounded-1 px-2 py-1 mt-2&#10;    border&#10;  " data-team-hovercards-enabled="">
  <details class="js-user-status-details details-reset details-overlay details-overlay-dark">
    <summary tabindex="0" class="btn-link btn-block link-gray no-underline js-toggle-user-status-edit toggle-user-status-edit " role="menuitem" aria-expanded="false" aria-haspopup="dialog" data-hydro-click-hmac="7eb3429c6c45b896bd81cd4ed260ae5834d1ce4ddec0cb7de1c44797f9308396" data-hydro-click='{"event_type":"user_profile.click","payload":{"profile_user_id":2212917,"target":"EDIT_USER_STATUS","user_id":51129449,"client_id":"11045060.1561916950","originating_request_id":"D31C:7535:1A892BC:2BCA714:5D190311","originating_url":"https://github.com/cmangos/mangos-tbc/new/master","referrer":"https://github.com/cmangos/mangos-tbc/security/policy"}}'>
      <div class="d-flex">
        <div class="f6 lh-condensed user-status-header&#10;          d-inline-block v-align-middle&#10;            user-status-emoji-only-header circle&#10;            pr-2&#10;" style="max-width: 29px">
          <div class="user-status-emoji-container flex-shrink-0 mr-1  lh-condensed-ultra v-align-bottom" style="margin-top: 2px;">
            <div><g-emoji class="g-emoji" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png" alias="dart">🎯</g-emoji></div>
          </div>
        </div>
        <div class="&#10;          d-inline-block v-align-middle&#10;          &#10;          &#10;           css-truncate css-truncate-target &#10;           user-status-message-wrapper f6" style="line-height: 20px;">
          <div class="d-inline-block text-gray-dark v-align-text-top text-left">
                <span>Focusing</span>
          </div>
        </div>
      </div>
</summary>    <details-dialog tabindex="-1" class="details-dialog rounded-1 anim-fade-in fast Box Box--overlay" role="dialog" aria-modal="true">
      <!-- '"` --><!-- </textarea></xmp> --><form class="position-relative flex-auto js-user-status-form" action="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1" method="post" accept-charset="UTF-8"><input name="utf8" type="hidden" value="✓"><input name="_method" type="hidden" value="put"><input name="authenticity_token" type="hidden" value="mpHv3GHwJuc6PLqTVpd8YPmvVn1atZIdj8if7ZgzgFq1yIu8aOiB/qrVCcXsWMB7p02hagP2ZU2f9Dg2mgkRHw==">
        <div class="Box-header bg-gray border-bottom p-3">
          <button class="Box-btn-octicon js-toggle-user-status-edit btn-octicon float-right" aria-label="Close dialog" type="reset" data-close-dialog="">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-x" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 7.48 8 l 3.75 3.75 l -1.48 1.48 L 6 9.48 l -3.75 3.75 l -1.48 -1.48 L 4.52 8 L 0.77 4.25 l 1.48 -1.48 L 6 6.52 l 3.75 -3.75 l 1.48 1.48 L 7.48 8 Z" /></svg>
          </button>
          <h3 class="Box-title f5 text-bold text-gray-dark">Edit status</h3>
        </div>
        <input name="emoji" class="js-user-status-emoji-field" type="hidden" value=":dart:">
        <input name="organization_id" class="js-user-status-org-id-field" type="hidden" value="">
        <div class="px-3 py-2 text-gray-dark">
          <div class="js-characters-remaining-container position-relative mt-2">
            <div class="input-group d-table form-group my-0 js-user-status-form-group">
              <span class="input-group-button d-table-cell v-align-middle" style="width: 1%">
                <button class="btn-outline btn js-toggle-user-status-emoji-picker btn-open-emoji-picker p-0" aria-label="Choose an emoji" type="button">
                  <span class="js-user-status-original-emoji" hidden=""><div><g-emoji class="g-emoji" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png" alias="dart">🎯</g-emoji></div></span>
                  <span class="js-user-status-custom-emoji"><div><g-emoji class="g-emoji" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png" alias="dart">🎯</g-emoji></div></span>
                  <span class="js-user-status-no-emoji-icon" hidden="">
                    <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-smiley" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8 0 C 3.58 0 0 3.58 0 8 s 3.58 8 8 8 s 8 -3.58 8 -8 s -3.58 -8 -8 -8 Z m 4.81 12.81 a 6.72 6.72 0 0 1 -2.17 1.45 c -0.83 0.36 -1.72 0.53 -2.64 0.53 c -0.92 0 -1.81 -0.17 -2.64 -0.53 c -0.81 -0.34 -1.55 -0.83 -2.17 -1.45 a 6.773 6.773 0 0 1 -1.45 -2.17 A 6.59 6.59 0 0 1 1.21 8 c 0 -0.92 0.17 -1.81 0.53 -2.64 c 0.34 -0.81 0.83 -1.55 1.45 -2.17 c 0.62 -0.62 1.36 -1.11 2.17 -1.45 A 6.59 6.59 0 0 1 8 1.21 c 0.92 0 1.81 0.17 2.64 0.53 c 0.81 0.34 1.55 0.83 2.17 1.45 c 0.62 0.62 1.11 1.36 1.45 2.17 c 0.36 0.83 0.53 1.72 0.53 2.64 c 0 0.92 -0.17 1.81 -0.53 2.64 c -0.34 0.81 -0.83 1.55 -1.45 2.17 Z M 4 6.8 v -0.59 c 0 -0.66 0.53 -1.19 1.2 -1.19 h 0.59 c 0.66 0 1.19 0.53 1.19 1.19 v 0.59 c 0 0.67 -0.53 1.2 -1.19 1.2 H 5.2 C 4.53 8 4 7.47 4 6.8 Z m 5 0 v -0.59 c 0 -0.66 0.53 -1.19 1.2 -1.19 h 0.59 c 0.66 0 1.19 0.53 1.19 1.19 v 0.59 c 0 0.67 -0.53 1.2 -1.19 1.2 h -0.59 C 9.53 8 9 7.47 9 6.8 Z m 4 3.2 c -0.72 1.88 -2.91 3 -5 3 s -4.28 -1.13 -5 -3 c -0.14 -0.39 0.23 -1 0.66 -1 h 8.59 c 0.41 0 0.89 0.61 0.75 1 Z" /></svg>
                  </span>
                </button>
              </span>
              <text-expander data-emoji-url="/autocomplete/emoji" data-mention-url="/autocomplete/user-suggestions" keys=": @">
                <input name="message" class="d-table-cell width-full form-control js-user-status-message-field js-characters-remaining-field" aria-label="What is your current status?" type="text" placeholder="What's happening?" value="Focusing" autocomplete="off" data-maxlength="80" data-org-url="/suggestions?mention_suggester=1" data-no-org-url="/autocomplete/user-suggestions">
              </text-expander>
              <div class="error">Could not update your status, please try again.</div>
            </div>
            <div class="my-1 text-small label-characters-remaining js-characters-remaining" style="margin-left: 53px" hidden="" data-suffix="remaining">
              80 remaining
            </div>
          </div>
          <include-fragment class="js-user-status-emoji-picker" data-url="/users/status/emoji"></include-fragment>
          <div class="overflow-auto ml-n3 mr-n3 px-3 border-bottom" style="max-height: 33vh">
            <div class="user-status-suggestions js-user-status-suggestions collapsed overflow-hidden">
              <h4 class="f6 text-normal my-3">Suggestions:</h4>
              <div class="mx-3 mt-2 clearfix">
                  <div class="float-left col-6">
                      <button class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1" type="button" value=":palm_tree:">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f334.png" alias="palm_tree">🌴</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          On vacation
                        </div>
                      </button>
                      <button class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1" type="button" value=":face_with_thermometer:">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f912.png" alias="face_with_thermometer">🤒</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Out sick
                        </div>
                      </button>
                  </div>
                  <div class="float-left col-6">
                      <button class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1" type="button" value=":house:">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3e0.png" alias="house">🏠</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Working from home
                        </div>
                      </button>
                      <button class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1" type="button" value=":dart:">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png" alias="dart">🎯</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Focusing
                        </div>
                      </button>
                  </div>
              </div>
            </div>
            <div class="user-status-limited-availability-container">
              <div class="form-checkbox my-0">
                <input name="limited_availability" class="js-user-status-limited-availability-checkbox" id="limited-availability-truncate-true-compact-true" aria-describedby="limited-availability-help-text-truncate-true-compact-true" type="checkbox" value="1" data-default-message="I may be slow to respond.">
                <label class="d-block f5 text-gray-dark mb-1" for="limited-availability-truncate-true-compact-true">
                  Busy
                </label>
                <p class="note" id="limited-availability-help-text-truncate-true-compact-true">
                  When others mention you, assign you, or request your review,
                  GitHub will let them know that you have limited availability.
                </p>
              </div>
            </div>
          </div>
            

<div class="d-inline-block f5 mr-2 pt-3 pb-2">
  <div class="d-inline-block mr-1">
    Clear status
  </div>

  <details class="js-user-status-expire-drop-down f6 dropdown details-reset details-overlay d-inline-block mr-2">
    <summary tabindex="0" class="f5 btn-link link-gray-dark border px-2 py-1 rounded-1" role="button" aria-expanded="false" aria-haspopup="true">
      <div class="js-user-status-expiration-interval-selected d-inline-block v-align-baseline">
        Never
      </div>
      <div class="dropdown-caret"></div>
    </summary>

    <ul class="dropdown-menu dropdown-menu-se pl-0 overflow-auto" style="width: 220px; max-height: 15.5em">
      <li>
        <button title="Never" class="btn-link dropdown-item js-user-status-expire-button ws-normal" type="button">
          <span class="d-inline-block text-bold mb-1">Never</span>
          <div class="f6 lh-condensed">Keep this status until you clear your status or edit your status.</div>
        </button>
      </li>
      <li class="dropdown-divider" role="none"></li>
        <li>
          <button title="in 30 minutes" class="btn-link dropdown-item ws-normal js-user-status-expire-button" type="button" value="2019-06-30T19:14:35Z">
            in 30 minutes
          </button>
        </li>
        <li>
          <button title="in 1 hour" class="btn-link dropdown-item ws-normal js-user-status-expire-button" type="button" value="2019-06-30T19:44:35Z">
            in 1 hour
          </button>
        </li>
        <li>
          <button title="in 4 hours" class="btn-link dropdown-item ws-normal js-user-status-expire-button" type="button" value="2019-06-30T22:44:35Z">
            in 4 hours
          </button>
        </li>
        <li>
          <button title="today" class="btn-link dropdown-item ws-normal js-user-status-expire-button" type="button" value="2019-06-30T23:59:59Z">
            today
          </button>
        </li>
        <li>
          <button title="this week" class="btn-link dropdown-item ws-normal js-user-status-expire-button" type="button" value="2019-06-30T23:59:59Z">
            this week
          </button>
        </li>
    </ul>
  </details>
  <input name="expires_at" class="js-user-status-expiration-date-input" type="hidden" value="">
</div>

          <include-fragment class="js-user-status-org-picker" data-url="/users/status/organizations"></include-fragment>
        </div>
        <div class="d-flex flex-items-center flex-justify-between p-3 border-top">
          <button class="width-full btn btn-primary mr-2 js-user-status-submit" type="submit">
            Set status
          </button>
          <button class="width-full js-clear-user-status-button btn ml-2 js-user-status-exists" type="button">
            Clear status
          </button>
        </div>
</form>    </details-dialog>
  </details>
</div>

      </div>
      <div class="dropdown-divider" role="none"></div>


    <a class="dropdown-item" role="menuitem" href="/GhostsOfHiroshima" data-ga-click="Header, go to profile, text:your profile">Your profile</a>
    <a class="dropdown-item" role="menuitem" href="/GhostsOfHiroshima?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a>

    <a class="dropdown-item" role="menuitem" href="/GhostsOfHiroshima?tab=projects" data-ga-click="Header, go to projects, text:your projects">Your projects</a>

    <a class="dropdown-item" role="menuitem" href="/GhostsOfHiroshima?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a>
      <a class="dropdown-item" role="menuitem" href="https://gist.github.com/mine" data-ga-click="Header, your gists, text:your gists">Your gists</a>


    <div class="dropdown-divider" role="none"></div>
    <a class="dropdown-item" role="menuitem" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
    <a class="dropdown-item" role="menuitem" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a>
    <!-- '"` --><!-- </textarea></xmp> --><form class="logout-form" action="/logout" method="post" accept-charset="UTF-8"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="sLAbr7Z6oVV3UtsYZwSxAmIHSaxddKcCzQdKHqPhV+9knIzmFkypRKRnwjBEGe5zcr2AdzgSddikFG02Z2SwUg==">
      
      <button class="dropdown-item dropdown-signout" role="menuitem" type="submit" data-ga-click="Header, sign out, icon:logout">
        Sign out
      </button>
</form>  </details-menu>
</details>

    </div>

  </header>

      

  </div>

  <div class="show-on-focus" id="start-of-content"></div>


    <div id="js-flash-container">

</div>



  <div class="application-main " data-commit-hovercards-enabled="">
        <div itemtype="http://schema.org/SoftwareSourceCode" itemscope="">
    <main id="js-repo-pjax-container" data-pjax-container="">
      

  



  




  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav pt-0 pt-lg-4 ">
    <div class="repohead-details-container clearfix container-lg p-responsive d-none d-lg-block">

      <ul class="pagehead-actions">




  <li>
    
    <!-- '"` --><!-- </textarea></xmp> --><form class="clearfix js-social-form js-social-container" action="/notifications/subscribe" method="post" accept-charset="UTF-8" data-remote="true"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="oRdc3wiGgz8DCQRamSRf5wJ0woY3Dud9RmrjXqt/h/P9PaVXVAsPJ7UX6CJ5wVG+8D5WyiHOlEbZ5X+ya1tkFA==">      <input name="repository_id" type="hidden" value="6829204">

      <details class="details-reset details-overlay select-menu float-left">
        <summary tabindex="0" class="select-menu-button float-left btn btn-sm btn-with-count" role="button" aria-expanded="false" aria-haspopup="menu" data-ga-click="Repository, click Watch settings, action:blob#new" data-hydro-click-hmac="073df916f436dac0ead8c377acbb85230b7acb463724e37f399694b0d914f72e" data-hydro-click='{"event_type":"repository.click","payload":{"target":"WATCH_BUTTON","repository_id":6829204,"client_id":"11045060.1561916950","originating_request_id":"D31C:7535:1A892BC:2BCA714:5D190311","originating_url":"https://github.com/cmangos/mangos-tbc/new/master","referrer":"https://github.com/cmangos/mangos-tbc/security/policy","user_id":51129449}}'>          <span data-menu-button="">
              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-eye v-align-text-bottom" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8.06 2 C 3 2 0 8 0 8 s 3 6 8.06 6 C 13 14 16 8 16 8 s -3 -6 -7.94 -6 Z M 8 12 c -2.2 0 -4 -1.78 -4 -4 c 0 -2.2 1.8 -4 4 -4 c 2.22 0 4 1.8 4 4 c 0 2.22 -1.78 4 -4 4 Z m 2 -4 c 0 1.11 -0.89 2 -2 2 c -1.11 0 -2 -0.89 -2 -2 c 0 -1.11 0.89 -2 2 -2 c 1.11 0 2 0.89 2 2 Z" /></svg>
              Watch
          </span>
</summary>        <details-menu class="select-menu-modal position-absolute mt-5" role="menu" style="z-index: 99;">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
          </div>
          <div class="select-menu-list">
            <button name="do" class="select-menu-item width-full" role="menuitemradio" aria-checked="true" type="submit" value="included">
              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Not watching</span>
                <span class="description">Be notified only when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents="">
                  <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-eye v-align-text-bottom" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8.06 2 C 3 2 0 8 0 8 s 3 6 8.06 6 C 13 14 16 8 16 8 s -3 -6 -7.94 -6 Z M 8 12 c -2.2 0 -4 -1.78 -4 -4 c 0 -2.2 1.8 -4 4 -4 c 2.22 0 4 1.8 4 4 c 0 2.22 -1.78 4 -4 4 Z m 2 -4 c 0 1.11 -0.89 2 -2 2 c -1.11 0 -2 -0.89 -2 -2 c 0 -1.11 0.89 -2 2 -2 c 1.11 0 2 0.89 2 2 Z" /></svg>
                  Watch
                </span>
              </div>
            </button>

            <button name="do" class="select-menu-item width-full" role="menuitemradio" aria-checked="false" type="submit" value="release_only">
              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Releases only</span>
                <span class="description">Be notified of new releases, and when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents="">
                  <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-eye v-align-text-bottom" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8.06 2 C 3 2 0 8 0 8 s 3 6 8.06 6 C 13 14 16 8 16 8 s -3 -6 -7.94 -6 Z M 8 12 c -2.2 0 -4 -1.78 -4 -4 c 0 -2.2 1.8 -4 4 -4 c 2.22 0 4 1.8 4 4 c 0 2.22 -1.78 4 -4 4 Z m 2 -4 c 0 1.11 -0.89 2 -2 2 c -1.11 0 -2 -0.89 -2 -2 c 0 -1.11 0.89 -2 2 -2 c 1.11 0 2 0.89 2 2 Z" /></svg>
                  Unwatch releases
                </span>
              </div>
            </button>

            <button name="do" class="select-menu-item width-full" role="menuitemradio" aria-checked="false" type="submit" value="subscribed">
              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Watching</span>
                <span class="description">Be notified of all conversations.</span>
                <span class="hidden-select-button-text" data-menu-button-contents="">
                  <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-eye v-align-text-bottom" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8.06 2 C 3 2 0 8 0 8 s 3 6 8.06 6 C 13 14 16 8 16 8 s -3 -6 -7.94 -6 Z M 8 12 c -2.2 0 -4 -1.78 -4 -4 c 0 -2.2 1.8 -4 4 -4 c 2.22 0 4 1.8 4 4 c 0 2.22 -1.78 4 -4 4 Z m 2 -4 c 0 1.11 -0.89 2 -2 2 c -1.11 0 -2 -0.89 -2 -2 c 0 -1.11 0.89 -2 2 -2 c 1.11 0 2 0.89 2 2 Z" /></svg>
                  Unwatch
                </span>
              </div>
            </button>

            <button name="do" class="select-menu-item width-full" role="menuitemradio" aria-checked="false" type="submit" value="ignore">
              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Ignoring</span>
                <span class="description">Never be notified.</span>
                <span class="hidden-select-button-text" data-menu-button-contents="">
                  <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-mute v-align-text-bottom" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8 2.81 v 10.38 c 0 0.67 -0.81 1 -1.28 0.53 L 3 10 H 1 c -0.55 0 -1 -0.45 -1 -1 V 7 c 0 -0.55 0.45 -1 1 -1 h 2 l 3.72 -3.72 C 7.19 1.81 8 2.14 8 2.81 Z m 7.53 3.22 l -1.06 -1.06 l -1.97 1.97 l -1.97 -1.97 l -1.06 1.06 L 11.44 8 L 9.47 9.97 l 1.06 1.06 l 1.97 -1.97 l 1.97 1.97 l 1.06 -1.06 L 13.56 8 l 1.97 -1.97 Z" /></svg>
                  Stop ignoring
                </span>
              </div>
            </button>
          </div>
        </details-menu>
      </details>
        <a class="social-count js-social-count" aria-label="108 users are watching this repository" href="/cmangos/mangos-tbc/watchers">
          108
        </a>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --><form class="starred js-social-form" action="/cmangos/mangos-tbc/unstar" method="post" accept-charset="UTF-8"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="c1l7cZl91VxaQV+f8edyB67A9/8etQipWyk6ZbP8EqPW4LHLggrBKW9pxZ4vEfJFdFgBq5XNl/DkEQX7qMdTZQ==">
      <input name="context" type="hidden" value="repository">
      <button title="Unstar cmangos/mangos-tbc" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" type="submit" data-ga-click="Repository, click unstar button, action:blob#new; text:Unstar" data-hydro-click-hmac="6a90af4d2f47f386eefba8aa1d7bd20cb6771c1644ed5b62d85d840d4d9f26b3" data-hydro-click='{"event_type":"repository.click","payload":{"target":"UNSTAR_BUTTON","repository_id":6829204,"client_id":"11045060.1561916950","originating_request_id":"D31C:7535:1A892BC:2BCA714:5D190311","originating_url":"https://github.com/cmangos/mangos-tbc/new/master","referrer":"https://github.com/cmangos/mangos-tbc/security/policy","user_id":51129449}}'>        <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-star v-align-text-bottom" aria-hidden="true" viewBox="0 0 14 16" width="14" height="16" version="1.1"><path fill-rule="evenodd" d="M 14 6 l -4.9 -0.64 L 7 1 L 4.9 5.36 L 0 6 l 3.6 3.26 L 2.67 14 L 7 11.67 L 11.33 14 l -0.93 -4.74 L 14 6 Z" /></svg>
        Unstar
</button>        <a class="social-count js-social-count" aria-label="206 users starred this repository" href="/cmangos/mangos-tbc/stargazers">
           206
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --><form class="unstarred js-social-form" action="/cmangos/mangos-tbc/star" method="post" accept-charset="UTF-8"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="cvM5k9SA6Z+TaDRhUyCvtONeOAcK/s7xjEgqSCyZd7TElASoMQhh0Uh4FEMZoN1SQECq60ac8HNYrI3oZJHkmA==">
      <input name="context" type="hidden" value="repository">
      <button title="Star cmangos/mangos-tbc" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" type="submit" data-ga-click="Repository, click star button, action:blob#new; text:Star" data-hydro-click-hmac="364e0efcb09fe2567d7a984a850f2814b39a209feb4957d31a3f28413dd6a1d0" data-hydro-click='{"event_type":"repository.click","payload":{"target":"STAR_BUTTON","repository_id":6829204,"client_id":"11045060.1561916950","originating_request_id":"D31C:7535:1A892BC:2BCA714:5D190311","originating_url":"https://github.com/cmangos/mangos-tbc/new/master","referrer":"https://github.com/cmangos/mangos-tbc/security/policy","user_id":51129449}}'>        <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-star v-align-text-bottom" aria-hidden="true" viewBox="0 0 14 16" width="14" height="16" version="1.1"><path fill-rule="evenodd" d="M 14 6 l -4.9 -0.64 L 7 1 L 4.9 5.36 L 0 6 l 3.6 3.26 L 2.67 14 L 7 11.67 L 11.33 14 l -0.93 -4.74 L 14 6 Z" /></svg>
        Star
</button>        <a class="social-count js-social-count" aria-label="206 users starred this repository" href="/cmangos/mangos-tbc/stargazers">
          206
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --><form class="btn-with-count" action="/cmangos/mangos-tbc/fork" method="post" accept-charset="UTF-8"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="k/cYlNI3wY78TMbvHES1/3TgCZpyUNYuEy1G1a8iaOO4Uv2gqNX+u4wh8C7jsWgcJmhgwBwCfuRGYqfWDxahUQ==">
            <button title="Fork your own copy of cmangos/mangos-tbc to your account" class="btn btn-sm btn-with-count" aria-label="Fork your own copy of cmangos/mangos-tbc to your account" type="submit" data-ga-click="Repository, show fork modal, action:blob#new; text:Fork" data-hydro-click-hmac="da69b54ab2d33d35e7568e085513f30835b366942cc65408a0c53a77f862d247" data-hydro-click='{"event_type":"repository.click","payload":{"target":"FORK_BUTTON","repository_id":6829204,"client_id":"11045060.1561916950","originating_request_id":"D31C:7535:1A892BC:2BCA714:5D190311","originating_url":"https://github.com/cmangos/mangos-tbc/new/master","referrer":"https://github.com/cmangos/mangos-tbc/security/policy","user_id":51129449}}'>              <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-repo-forked v-align-text-bottom" aria-hidden="true" viewBox="0 0 10 16" width="10" height="16" version="1.1"><path fill-rule="evenodd" d="M 8 1 a 1.993 1.993 0 0 0 -1 3.72 V 6 L 5 8 L 3 6 V 4.72 A 1.993 1.993 0 0 0 2 1 a 1.993 1.993 0 0 0 -1 3.72 V 6.5 l 3 3 v 1.78 A 1.993 1.993 0 0 0 5 15 a 1.993 1.993 0 0 0 1 -3.72 V 9.5 l 3 -3 V 4.72 A 1.993 1.993 0 0 0 8 1 Z M 2 4.2 C 1.34 4.2 0.8 3.65 0.8 3 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z m 3 10 c -0.66 0 -1.2 -0.55 -1.2 -1.2 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z m 3 -10 c -0.66 0 -1.2 -0.55 -1.2 -1.2 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z" /></svg>
              Fork
</button></form>
    <a class="social-count" aria-label="342 users forked this repository" href="/cmangos/mangos-tbc/network/members">
      342
    </a>
  </li>
</ul>

      <h1 class="public ">
    <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-repo" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 4 9 H 3 V 8 h 1 v 1 Z m 0 -3 H 3 v 1 h 1 V 6 Z m 0 -2 H 3 v 1 h 1 V 4 Z m 0 -2 H 3 v 1 h 1 V 2 Z m 8 -1 v 12 c 0 0.55 -0.45 1 -1 1 H 6 v 2 l -1.5 -1.5 L 3 16 v -2 H 1 c -0.55 0 -1 -0.45 -1 -1 V 1 c 0 -0.55 0.45 -1 1 -1 h 10 c 0.55 0 1 0.45 1 1 Z m -1 10 H 1 v 2 h 2 v -1 h 3 v 1 h 5 v -2 Z m 0 -10 H 2 v 9 h 9 V 1 Z" /></svg>
  <span class="author" itemprop="author"><a class="url fn" href="/cmangos" rel="author" data-hovercard-url="/orgs/cmangos/hovercard" data-hovercard-type="organization">cmangos</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/cmangos/mangos-tbc" data-pjax="#js-repo-pjax-container">mangos-tbc</a></strong>
  

</h1>

    </div>
    
<nav class="hx_reponav reponav js-repo-nav js-sidenav-container-pjax container-lg p-responsive d-none d-lg-block" aria-label="Repository" data-pjax="#js-repo-pjax-container" itemtype="http://schema.org/BreadcrumbList" itemscope="">

  <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
    <a class="js-selected-navigation-item selected reponav-item" aria-current="page" href="/cmangos/mangos-tbc" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /cmangos/mangos-tbc" itemprop="url">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-code" aria-hidden="true" viewBox="0 0 14 16" width="14" height="16" version="1.1"><path fill-rule="evenodd" d="M 9.5 3 L 8 4.5 L 11.5 8 L 8 11.5 L 9.5 13 L 14 8 L 9.5 3 Z m -5 0 L 0 8 l 4.5 5 L 6 11.5 L 2.5 8 L 6 4.5 L 4.5 3 Z" /></svg>
      <span itemprop="name">Code</span>
      <meta content="1" itemprop="position">
</a>  </span>


  <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
    <a class="js-selected-navigation-item reponav-item" href="/cmangos/mangos-tbc/pulls" data-hotkey="g p" data-selected-links="repo_pulls checks /cmangos/mangos-tbc/pulls" itemprop="url">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-git-pull-request" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 11 11.28 V 5 c -0.03 -0.78 -0.34 -1.47 -0.94 -2.06 C 9.46 2.35 8.78 2.03 8 2 H 7 V 0 L 4 3 l 3 3 V 4 h 1 c 0.27 0.02 0.48 0.11 0.69 0.31 c 0.21 0.2 0.3 0.42 0.31 0.69 v 6.28 A 1.993 1.993 0 0 0 10 15 a 1.993 1.993 0 0 0 1 -3.72 Z m -1 2.92 c -0.66 0 -1.2 -0.55 -1.2 -1.2 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z M 4 3 c 0 -1.11 -0.89 -2 -2 -2 a 1.993 1.993 0 0 0 -1 3.72 v 6.56 A 1.993 1.993 0 0 0 2 15 a 1.993 1.993 0 0 0 1 -3.72 V 4.72 c 0.59 -0.34 1 -0.98 1 -1.72 Z m -0.8 10 c 0 0.66 -0.55 1.2 -1.2 1.2 c -0.65 0 -1.2 -0.55 -1.2 -1.2 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 Z M 2 4.2 C 1.34 4.2 0.8 3.65 0.8 3 c 0 -0.65 0.55 -1.2 1.2 -1.2 c 0.65 0 1.2 0.55 1.2 1.2 c 0 0.65 -0.55 1.2 -1.2 1.2 Z" /></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">13</span>
      <meta content="3" itemprop="position">
</a>  </span>


    <a class="js-selected-navigation-item reponav-item" href="/cmangos/mangos-tbc/projects" data-hotkey="g b" data-selected-links="repo_projects new_repo_project repo_project /cmangos/mangos-tbc/projects">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-project" aria-hidden="true" viewBox="0 0 15 16" width="15" height="16" version="1.1"><path fill-rule="evenodd" d="M 10 12 h 3 V 2 h -3 v 10 Z m -4 -2 h 3 V 2 H 6 v 8 Z m -4 4 h 3 V 2 H 2 v 12 Z m -1 1 h 13 V 1 H 1 v 14 Z M 14 0 H 1 a 1 1 0 0 0 -1 1 v 14 a 1 1 0 0 0 1 1 h 13 a 1 1 0 0 0 1 -1 V 1 a 1 1 0 0 0 -1 -1 Z" /></svg>
      Projects
      <span class="Counter">0</span>
</a>

    <a class="js-selected-navigation-item reponav-item" href="/cmangos/mangos-tbc/wiki" data-hotkey="g w" data-selected-links="repo_wiki /cmangos/mangos-tbc/wiki">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-book" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 3 5 h 4 v 1 H 3 V 5 Z m 0 3 h 4 V 7 H 3 v 1 Z m 0 2 h 4 V 9 H 3 v 1 Z m 11 -5 h -4 v 1 h 4 V 5 Z m 0 2 h -4 v 1 h 4 V 7 Z m 0 2 h -4 v 1 h 4 V 9 Z m 2 -6 v 9 c 0 0.55 -0.45 1 -1 1 H 9.5 l -1 1 l -1 -1 H 2 c -0.55 0 -1 -0.45 -1 -1 V 3 c 0 -0.55 0.45 -1 1 -1 h 5.5 l 1 1 l 1 -1 H 15 c 0.55 0 1 0.45 1 1 Z m -8 0.5 L 7.5 3 H 2 v 9 h 6 V 3.5 Z m 7 -0.5 H 9.5 l -0.5 0.5 V 12 h 6 V 3 Z" /></svg>
      Wiki
</a>
    <a class="js-selected-navigation-item reponav-item" href="/cmangos/mangos-tbc/security/advisories" data-selected-links="security alerts policy /cmangos/mangos-tbc/security/advisories" data-skip-pjax="true">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-shield" aria-hidden="true" viewBox="0 0 14 16" width="14" height="16" version="1.1"><path fill-rule="evenodd" d="M 0 2 l 7 -2 l 7 2 v 6.02 C 14 12.69 8.69 16 7 16 c -1.69 0 -7 -3.31 -7 -7.98 V 2 Z m 1 0.75 L 7 1 l 6 1.75 v 5.268 C 13 12.104 8.449 15 7 15 c -1.449 0 -6 -2.896 -6 -6.982 V 2.75 Z m 1 0.75 L 7 2 v 12 c -1.207 0 -5 -2.482 -5 -5.985 V 3.5 Z" /></svg>
      Security
</a>
    <a class="js-selected-navigation-item reponav-item" href="/cmangos/mangos-tbc/pulse" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people /cmangos/mangos-tbc/pulse">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-graph" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 16 14 v 1 H 0 V 0 h 1 v 14 h 15 Z M 5 13 H 3 V 8 h 2 v 5 Z m 4 0 H 7 V 3 h 2 v 10 Z m 4 0 h -2 V 6 h 2 v 7 Z" /></svg>
      Insights
</a>

</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap" itemtype="http://schema.org/BreadcrumbList" itemscope="">

    <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
      <a class="js-selected-navigation-item selected reponav-item" aria-current="page" href="/cmangos/mangos-tbc" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /cmangos/mangos-tbc" itemprop="url">
        <span itemprop="name">Code</span>
        <meta content="1" itemprop="position">
</a>    </span>


    <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
      <a class="js-selected-navigation-item reponav-item" href="/cmangos/mangos-tbc/pulls" data-selected-links="repo_pulls checks /cmangos/mangos-tbc/pulls" itemprop="url">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">13</span>
        <meta content="3" itemprop="position">
</a>    </span>

      <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
        <a class="js-selected-navigation-item reponav-item" href="/cmangos/mangos-tbc/projects" data-selected-links="repo_projects new_repo_project repo_project /cmangos/mangos-tbc/projects" itemprop="url">
          <span itemprop="name">Projects</span>
          <span class="Counter">0</span>
          <meta content="4" itemprop="position">
</a>      </span>

      <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
        <a class="js-selected-navigation-item reponav-item" href="/cmangos/mangos-tbc/wiki" data-selected-links="repo_wiki /cmangos/mangos-tbc/wiki" itemprop="url">
          <span itemprop="name">Wiki</span>
          <meta content="5" itemprop="position">
</a>      </span>

      <a class="js-selected-navigation-item reponav-item" href="/cmangos/mangos-tbc/security/advisories" data-selected-links="security alerts policy /cmangos/mangos-tbc/security/advisories" itemprop="url">
        <span itemprop="name">Security</span>
        <meta content="6" itemprop="position">
</a>
      <a class="js-selected-navigation-item reponav-item" href="/cmangos/mangos-tbc/pulse" data-selected-links="pulse /cmangos/mangos-tbc/pulse">
        Pulse
</a>
      <span itemprop="itemListElement" itemtype="http://schema.org/ListItem" itemscope="">
        <a class="js-selected-navigation-item reponav-item" href="/cmangos/mangos-tbc/community" data-selected-links="community /cmangos/mangos-tbc/community" itemprop="url">
          Community
</a>      </span>

  </nav>
</div>


  </div>
<div class="container-lg new-discussion-timeline experiment-repo-nav  ">
  <div class="repository-content ">

    
    
  
    <div class="flash-messages ">
  <div class="flash mx-3">
    You’re creating a file in a project you
    don’t have write access to.
      We’ve <strong>created a fork of this project</strong>
      for you to commit your proposed changes to.
    Submitting a change
      will create the file in
    a new branch in your
      fork,
    so you can send a pull request.
  </div>
</div>


    <div class="file-box ">
      <!-- '"` --><!-- </textarea></xmp> --><form class="d-none js-blob-preview-form" action="/cmangos/mangos-tbc/preview/master" method="post" accept-charset="UTF-8"><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="gG5JR6T+y6r3ngXi/vTWlIM2aI3xgCTDl1fE8BPEj4TfK+M4Ohm/XcIdObUIyDyEcUxTANe4qL80ERqNzE8o6g==">
        <input name="code" type="hidden">
        <input name="commit" type="hidden">
        <input name="blobname" type="hidden">
        <input name="willcreatebranch" type="hidden">
        <input name="checkConflict" type="hidden">
</form>

      <!-- '"` --><!-- </textarea></xmp> --><form class="js-blob-form" action="/cmangos/mangos-tbc/create/master" method="post" accept-charset="UTF-8" data-github-confirm-unload="Your new changes will be lost."><input name="utf8" type="hidden" value="✓"><input name="authenticity_token" type="hidden" value="j/zHEmhDtfxuu8jOLe4YGfzBJWtleXXB8spvbBnNOvcWE9WIzAeGbbaitkUBfiAnXXx5RiuP6kA1uRSjCmEfMw==">
        



<div class="breadcrumb d-flex flex-items-center px-3 px-sm-6 px-lg-3">
    <span class="js-breadcrumb-container d-flex flex-items-center flex-wrap mr-sm-4 flex-auto">
      <span class="js-repo-root text-bold"><span class="js-path-segment"><a href="/cmangos/mangos-tbc" data-pjax="true"><span>mangos-tbc</span></a></span></span><span class="separator">/</span>

      <input name="filename" class="form-control js-blob-filename js-breadcrumb-nav mr-1 mt-1 mt-sm-0 col-12 width-sm-auto" autofocus="" aria-label="Name your file…" type="text" placeholder="Name your file…" value="SECURITY.md">
        <span><a class="btn d-none d-md-inline-block" href="/cmangos/mangos-tbc">Cancel</a></span>
    </span>

    <div class="js-gitignore-template js-template-suggestion d-flex flex-shrink-0 flex-justify-end f5 flex-items-center hide-sm hide-md hide-lg  d-none" data-template-suggestion-pattern="^(.+\/)?\.gitignore$">
      <div class="mr-2">Want to use a <span class="text-mono f6">.gitignore</span> template?</div>
      <details class="details-reset details-overlay select-menu d-inline-block">
  <summary tabindex="0" class="btn btn-sm select-menu-button" role="button" aria-expanded="false" aria-haspopup="menu">
    <i>Choose .gitignore:</i>
    <span data-menu-button="">None</span>
  </summary>
  <details-menu class="select-menu-modal position-absolute right-0" role="menu" style="z-index: 99;">
    <div class="select-menu-header">
      <span class="select-menu-title">.gitignore</span>
    </div>

    <div class="select-menu-filters">
      <div class="select-menu-text-filter">
        <input class="form-control js-filterable-field js-navigation-enable" id="context-ignore-filter-field" autofocus="" aria-label="Choose .gitignore type" type="text" placeholder="Filter ignores…">
      </div>
    </div>

    <div class="select-menu-list">
      <div data-filterable-for="context-ignore-filter-field">
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-actionscript" id="gitignore-actionscript_Actionscript" type="radio" value="Actionscript" data-template-url="https://github.com/site/gitignore/Actionscript">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Actionscript</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-ada" id="gitignore-ada_Ada" type="radio" value="Ada" data-template-url="https://github.com/site/gitignore/Ada">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Ada</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-agda" id="gitignore-agda_Agda" type="radio" value="Agda" data-template-url="https://github.com/site/gitignore/Agda">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Agda</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-android" id="gitignore-android_Android" type="radio" value="Android" data-template-url="https://github.com/site/gitignore/Android">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Android</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-appengine" id="gitignore-appengine_AppEngine" type="radio" value="AppEngine" data-template-url="https://github.com/site/gitignore/AppEngine">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">AppEngine</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-appceleratortitanium" id="gitignore-appceleratortitanium_AppceleratorTitanium" type="radio" value="AppceleratorTitanium" data-template-url="https://github.com/site/gitignore/AppceleratorTitanium">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">AppceleratorTitanium</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-archlinuxpackages" id="gitignore-archlinuxpackages_ArchLinuxPackages" type="radio" value="ArchLinuxPackages" data-template-url="https://github.com/site/gitignore/ArchLinuxPackages">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">ArchLinuxPackages</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-autotools" id="gitignore-autotools_Autotools" type="radio" value="Autotools" data-template-url="https://github.com/site/gitignore/Autotools">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Autotools</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-c" id="gitignore-c_C" type="radio" value="C" data-template-url="https://github.com/site/gitignore/C">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">C</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-c++" id="gitignore-c___C__" type="radio" value="C++" data-template-url="https://github.com/site/gitignore/C++">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">C++</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-cfwheels" id="gitignore-cfwheels_CFWheels" type="radio" value="CFWheels" data-template-url="https://github.com/site/gitignore/CFWheels">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">CFWheels</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-cmake" id="gitignore-cmake_CMake" type="radio" value="CMake" data-template-url="https://github.com/site/gitignore/CMake">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">CMake</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-cuda" id="gitignore-cuda_CUDA" type="radio" value="CUDA" data-template-url="https://github.com/site/gitignore/CUDA">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">CUDA</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-cakephp" id="gitignore-cakephp_CakePHP" type="radio" value="CakePHP" data-template-url="https://github.com/site/gitignore/CakePHP">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">CakePHP</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-chefcookbook" id="gitignore-chefcookbook_ChefCookbook" type="radio" value="ChefCookbook" data-template-url="https://github.com/site/gitignore/ChefCookbook">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">ChefCookbook</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-clojure" id="gitignore-clojure_Clojure" type="radio" value="Clojure" data-template-url="https://github.com/site/gitignore/Clojure">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Clojure</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-codeigniter" id="gitignore-codeigniter_CodeIgniter" type="radio" value="CodeIgniter" data-template-url="https://github.com/site/gitignore/CodeIgniter">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">CodeIgniter</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-commonlisp" id="gitignore-commonlisp_CommonLisp" type="radio" value="CommonLisp" data-template-url="https://github.com/site/gitignore/CommonLisp">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">CommonLisp</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-composer" id="gitignore-composer_Composer" type="radio" value="Composer" data-template-url="https://github.com/site/gitignore/Composer">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Composer</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-concrete5" id="gitignore-concrete5_Concrete5" type="radio" value="Concrete5" data-template-url="https://github.com/site/gitignore/Concrete5">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Concrete5</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-coq" id="gitignore-coq_Coq" type="radio" value="Coq" data-template-url="https://github.com/site/gitignore/Coq">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Coq</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-craftcms" id="gitignore-craftcms_CraftCMS" type="radio" value="CraftCMS" data-template-url="https://github.com/site/gitignore/CraftCMS">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">CraftCMS</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-d" id="gitignore-d_D" type="radio" value="D" data-template-url="https://github.com/site/gitignore/D">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">D</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-dm" id="gitignore-dm_DM" type="radio" value="DM" data-template-url="https://github.com/site/gitignore/DM">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">DM</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-dart" id="gitignore-dart_Dart" type="radio" value="Dart" data-template-url="https://github.com/site/gitignore/Dart">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Dart</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-delphi" id="gitignore-delphi_Delphi" type="radio" value="Delphi" data-template-url="https://github.com/site/gitignore/Delphi">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Delphi</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-drupal" id="gitignore-drupal_Drupal" type="radio" value="Drupal" data-template-url="https://github.com/site/gitignore/Drupal">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Drupal</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-episerver" id="gitignore-episerver_EPiServer" type="radio" value="EPiServer" data-template-url="https://github.com/site/gitignore/EPiServer">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">EPiServer</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-eagle" id="gitignore-eagle_Eagle" type="radio" value="Eagle" data-template-url="https://github.com/site/gitignore/Eagle">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Eagle</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-elisp" id="gitignore-elisp_Elisp" type="radio" value="Elisp" data-template-url="https://github.com/site/gitignore/Elisp">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Elisp</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-elixir" id="gitignore-elixir_Elixir" type="radio" value="Elixir" data-template-url="https://github.com/site/gitignore/Elixir">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Elixir</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-elm" id="gitignore-elm_Elm" type="radio" value="Elm" data-template-url="https://github.com/site/gitignore/Elm">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Elm</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-erlang" id="gitignore-erlang_Erlang" type="radio" value="Erlang" data-template-url="https://github.com/site/gitignore/Erlang">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Erlang</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-expressionengine" id="gitignore-expressionengine_ExpressionEngine" type="radio" value="ExpressionEngine" data-template-url="https://github.com/site/gitignore/ExpressionEngine">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">ExpressionEngine</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-extjs" id="gitignore-extjs_ExtJs" type="radio" value="ExtJs" data-template-url="https://github.com/site/gitignore/ExtJs">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">ExtJs</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-fancy" id="gitignore-fancy_Fancy" type="radio" value="Fancy" data-template-url="https://github.com/site/gitignore/Fancy">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Fancy</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-finale" id="gitignore-finale_Finale" type="radio" value="Finale" data-template-url="https://github.com/site/gitignore/Finale">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Finale</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-forcedotcom" id="gitignore-forcedotcom_ForceDotCom" type="radio" value="ForceDotCom" data-template-url="https://github.com/site/gitignore/ForceDotCom">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">ForceDotCom</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-fortran" id="gitignore-fortran_Fortran" type="radio" value="Fortran" data-template-url="https://github.com/site/gitignore/Fortran">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Fortran</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-fuelphp" id="gitignore-fuelphp_FuelPHP" type="radio" value="FuelPHP" data-template-url="https://github.com/site/gitignore/FuelPHP">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">FuelPHP</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-gwt" id="gitignore-gwt_GWT" type="radio" value="GWT" data-template-url="https://github.com/site/gitignore/GWT">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">GWT</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-gitbook" id="gitignore-gitbook_GitBook" type="radio" value="GitBook" data-template-url="https://github.com/site/gitignore/GitBook">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">GitBook</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-go" id="gitignore-go_Go" type="radio" value="Go" data-template-url="https://github.com/site/gitignore/Go">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Go</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-godot" id="gitignore-godot_Godot" type="radio" value="Godot" data-template-url="https://github.com/site/gitignore/Godot">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Godot</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-gradle" id="gitignore-gradle_Gradle" type="radio" value="Gradle" data-template-url="https://github.com/site/gitignore/Gradle">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Gradle</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-grails" id="gitignore-grails_Grails" type="radio" value="Grails" data-template-url="https://github.com/site/gitignore/Grails">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Grails</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-haskell" id="gitignore-haskell_Haskell" type="radio" value="Haskell" data-template-url="https://github.com/site/gitignore/Haskell">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Haskell</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-igorpro" id="gitignore-igorpro_IGORPro" type="radio" value="IGORPro" data-template-url="https://github.com/site/gitignore/IGORPro">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">IGORPro</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-idris" id="gitignore-idris_Idris" type="radio" value="Idris" data-template-url="https://github.com/site/gitignore/Idris">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Idris</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-java" id="gitignore-java_Java" type="radio" value="Java" data-template-url="https://github.com/site/gitignore/Java">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Java</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-jboss" id="gitignore-jboss_Jboss" type="radio" value="Jboss" data-template-url="https://github.com/site/gitignore/Jboss">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Jboss</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-jekyll" id="gitignore-jekyll_Jekyll" type="radio" value="Jekyll" data-template-url="https://github.com/site/gitignore/Jekyll">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Jekyll</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-joomla" id="gitignore-joomla_Joomla" type="radio" value="Joomla" data-template-url="https://github.com/site/gitignore/Joomla">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Joomla</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-julia" id="gitignore-julia_Julia" type="radio" value="Julia" data-template-url="https://github.com/site/gitignore/Julia">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Julia</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-kicad" id="gitignore-kicad_KiCAD" type="radio" value="KiCAD" data-template-url="https://github.com/site/gitignore/KiCAD">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">KiCAD</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-kohana" id="gitignore-kohana_Kohana" type="radio" value="Kohana" data-template-url="https://github.com/site/gitignore/Kohana">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Kohana</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-kotlin" id="gitignore-kotlin_Kotlin" type="radio" value="Kotlin" data-template-url="https://github.com/site/gitignore/Kotlin">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Kotlin</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-labview" id="gitignore-labview_LabVIEW" type="radio" value="LabVIEW" data-template-url="https://github.com/site/gitignore/LabVIEW">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">LabVIEW</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-laravel" id="gitignore-laravel_Laravel" type="radio" value="Laravel" data-template-url="https://github.com/site/gitignore/Laravel">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Laravel</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-leiningen" id="gitignore-leiningen_Leiningen" type="radio" value="Leiningen" data-template-url="https://github.com/site/gitignore/Leiningen">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Leiningen</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-lemonstand" id="gitignore-lemonstand_LemonStand" type="radio" value="LemonStand" data-template-url="https://github.com/site/gitignore/LemonStand">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">LemonStand</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-lilypond" id="gitignore-lilypond_Lilypond" type="radio" value="Lilypond" data-template-url="https://github.com/site/gitignore/Lilypond">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Lilypond</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-lithium" id="gitignore-lithium_Lithium" type="radio" value="Lithium" data-template-url="https://github.com/site/gitignore/Lithium">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Lithium</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-lua" id="gitignore-lua_Lua" type="radio" value="Lua" data-template-url="https://github.com/site/gitignore/Lua">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Lua</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-magento" id="gitignore-magento_Magento" type="radio" value="Magento" data-template-url="https://github.com/site/gitignore/Magento">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Magento</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-maven" id="gitignore-maven_Maven" type="radio" value="Maven" data-template-url="https://github.com/site/gitignore/Maven">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Maven</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-mercury" id="gitignore-mercury_Mercury" type="radio" value="Mercury" data-template-url="https://github.com/site/gitignore/Mercury">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Mercury</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-metaprogrammingsystem" id="gitignore-metaprogrammingsystem_MetaProgrammingSystem" type="radio" value="MetaProgrammingSystem" data-template-url="https://github.com/site/gitignore/MetaProgrammingSystem">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">MetaProgrammingSystem</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-nim" id="gitignore-nim_Nim" type="radio" value="Nim" data-template-url="https://github.com/site/gitignore/Nim">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Nim</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-node" id="gitignore-node_Node" type="radio" value="Node" data-template-url="https://github.com/site/gitignore/Node">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Node</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-ocaml" id="gitignore-ocaml_OCaml" type="radio" value="OCaml" data-template-url="https://github.com/site/gitignore/OCaml">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">OCaml</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-objective-c" id="gitignore-objective-c_Objective-C" type="radio" value="Objective-C" data-template-url="https://github.com/site/gitignore/Objective-C">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Objective-C</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-opa" id="gitignore-opa_Opa" type="radio" value="Opa" data-template-url="https://github.com/site/gitignore/Opa">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Opa</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-oracleforms" id="gitignore-oracleforms_OracleForms" type="radio" value="OracleForms" data-template-url="https://github.com/site/gitignore/OracleForms">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">OracleForms</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-packer" id="gitignore-packer_Packer" type="radio" value="Packer" data-template-url="https://github.com/site/gitignore/Packer">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Packer</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-perl" id="gitignore-perl_Perl" type="radio" value="Perl" data-template-url="https://github.com/site/gitignore/Perl">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Perl</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-phalcon" id="gitignore-phalcon_Phalcon" type="radio" value="Phalcon" data-template-url="https://github.com/site/gitignore/Phalcon">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Phalcon</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-playframework" id="gitignore-playframework_PlayFramework" type="radio" value="PlayFramework" data-template-url="https://github.com/site/gitignore/PlayFramework">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">PlayFramework</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-plone" id="gitignore-plone_Plone" type="radio" value="Plone" data-template-url="https://github.com/site/gitignore/Plone">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Plone</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-prestashop" id="gitignore-prestashop_Prestashop" type="radio" value="Prestashop" data-template-url="https://github.com/site/gitignore/Prestashop">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Prestashop</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-processing" id="gitignore-processing_Processing" type="radio" value="Processing" data-template-url="https://github.com/site/gitignore/Processing">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Processing</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-purescript" id="gitignore-purescript_PureScript" type="radio" value="PureScript" data-template-url="https://github.com/site/gitignore/PureScript">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">PureScript</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-python" id="gitignore-python_Python" type="radio" value="Python" data-template-url="https://github.com/site/gitignore/Python">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Python</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-qooxdoo" id="gitignore-qooxdoo_Qooxdoo" type="radio" value="Qooxdoo" data-template-url="https://github.com/site/gitignore/Qooxdoo">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Qooxdoo</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-qt" id="gitignore-qt_Qt" type="radio" value="Qt" data-template-url="https://github.com/site/gitignore/Qt">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Qt</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-r" id="gitignore-r_R" type="radio" value="R" data-template-url="https://github.com/site/gitignore/R">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">R</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-ros" id="gitignore-ros_ROS" type="radio" value="ROS" data-template-url="https://github.com/site/gitignore/ROS">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">ROS</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-rails" id="gitignore-rails_Rails" type="radio" value="Rails" data-template-url="https://github.com/site/gitignore/Rails">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Rails</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-rhodesrhomobile" id="gitignore-rhodesrhomobile_RhodesRhomobile" type="radio" value="RhodesRhomobile" data-template-url="https://github.com/site/gitignore/RhodesRhomobile">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">RhodesRhomobile</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-ruby" id="gitignore-ruby_Ruby" type="radio" value="Ruby" data-template-url="https://github.com/site/gitignore/Ruby">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Ruby</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-rust" id="gitignore-rust_Rust" type="radio" value="Rust" data-template-url="https://github.com/site/gitignore/Rust">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Rust</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-scons" id="gitignore-scons_SCons" type="radio" value="SCons" data-template-url="https://github.com/site/gitignore/SCons">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">SCons</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-sass" id="gitignore-sass_Sass" type="radio" value="Sass" data-template-url="https://github.com/site/gitignore/Sass">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Sass</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-scala" id="gitignore-scala_Scala" type="radio" value="Scala" data-template-url="https://github.com/site/gitignore/Scala">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Scala</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-scheme" id="gitignore-scheme_Scheme" type="radio" value="Scheme" data-template-url="https://github.com/site/gitignore/Scheme">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Scheme</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-scrivener" id="gitignore-scrivener_Scrivener" type="radio" value="Scrivener" data-template-url="https://github.com/site/gitignore/Scrivener">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Scrivener</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-sdcc" id="gitignore-sdcc_Sdcc" type="radio" value="Sdcc" data-template-url="https://github.com/site/gitignore/Sdcc">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Sdcc</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-seamgen" id="gitignore-seamgen_SeamGen" type="radio" value="SeamGen" data-template-url="https://github.com/site/gitignore/SeamGen">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">SeamGen</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-sketchup" id="gitignore-sketchup_SketchUp" type="radio" value="SketchUp" data-template-url="https://github.com/site/gitignore/SketchUp">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">SketchUp</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-smalltalk" id="gitignore-smalltalk_Smalltalk" type="radio" value="Smalltalk" data-template-url="https://github.com/site/gitignore/Smalltalk">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Smalltalk</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-sugarcrm" id="gitignore-sugarcrm_SugarCRM" type="radio" value="SugarCRM" data-template-url="https://github.com/site/gitignore/SugarCRM">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">SugarCRM</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-swift" id="gitignore-swift_Swift" type="radio" value="Swift" data-template-url="https://github.com/site/gitignore/Swift">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Swift</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-symfony" id="gitignore-symfony_Symfony" type="radio" value="Symfony" data-template-url="https://github.com/site/gitignore/Symfony">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Symfony</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-symphonycms" id="gitignore-symphonycms_SymphonyCMS" type="radio" value="SymphonyCMS" data-template-url="https://github.com/site/gitignore/SymphonyCMS">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">SymphonyCMS</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-tex" id="gitignore-tex_TeX" type="radio" value="TeX" data-template-url="https://github.com/site/gitignore/TeX">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">TeX</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-terraform" id="gitignore-terraform_Terraform" type="radio" value="Terraform" data-template-url="https://github.com/site/gitignore/Terraform">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Terraform</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-textpattern" id="gitignore-textpattern_Textpattern" type="radio" value="Textpattern" data-template-url="https://github.com/site/gitignore/Textpattern">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Textpattern</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-turbogears2" id="gitignore-turbogears2_TurboGears2" type="radio" value="TurboGears2" data-template-url="https://github.com/site/gitignore/TurboGears2">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">TurboGears2</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-typo3" id="gitignore-typo3_Typo3" type="radio" value="Typo3" data-template-url="https://github.com/site/gitignore/Typo3">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Typo3</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-umbraco" id="gitignore-umbraco_Umbraco" type="radio" value="Umbraco" data-template-url="https://github.com/site/gitignore/Umbraco">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Umbraco</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-unity" id="gitignore-unity_Unity" type="radio" value="Unity" data-template-url="https://github.com/site/gitignore/Unity">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Unity</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-unrealengine" id="gitignore-unrealengine_UnrealEngine" type="radio" value="UnrealEngine" data-template-url="https://github.com/site/gitignore/UnrealEngine">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">UnrealEngine</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-vvvv" id="gitignore-vvvv_VVVV" type="radio" value="VVVV" data-template-url="https://github.com/site/gitignore/VVVV">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">VVVV</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-visualstudio" id="gitignore-visualstudio_VisualStudio" type="radio" value="VisualStudio" data-template-url="https://github.com/site/gitignore/VisualStudio">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">VisualStudio</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-waf" id="gitignore-waf_Waf" type="radio" value="Waf" data-template-url="https://github.com/site/gitignore/Waf">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Waf</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-wordpress" id="gitignore-wordpress_WordPress" type="radio" value="WordPress" data-template-url="https://github.com/site/gitignore/WordPress">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">WordPress</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-xojo" id="gitignore-xojo_Xojo" type="radio" value="Xojo" data-template-url="https://github.com/site/gitignore/Xojo">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Xojo</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-yeoman" id="gitignore-yeoman_Yeoman" type="radio" value="Yeoman" data-template-url="https://github.com/site/gitignore/Yeoman">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Yeoman</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-yii" id="gitignore-yii_Yii" type="radio" value="Yii" data-template-url="https://github.com/site/gitignore/Yii">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Yii</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-zendframework" id="gitignore-zendframework_ZendFramework" type="radio" value="ZendFramework" data-template-url="https://github.com/site/gitignore/ZendFramework">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">ZendFramework</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-zephir" id="gitignore-zephir_Zephir" type="radio" value="Zephir" data-template-url="https://github.com/site/gitignore/Zephir">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">Zephir</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-gcov" id="gitignore-gcov_gcov" type="radio" value="gcov" data-template-url="https://github.com/site/gitignore/gcov">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">gcov</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-nanoc" id="gitignore-nanoc_nanoc" type="radio" value="nanoc" data-template-url="https://github.com/site/gitignore/nanoc">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">nanoc</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-opencart" id="gitignore-opencart_opencart" type="radio" value="opencart" data-template-url="https://github.com/site/gitignore/opencart">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">opencart</span>
          </label>
          <label tabindex="0" class="select-menu-item" role="menuitemradio">
            <input name="gitignore-stella" id="gitignore-stella_stella" type="radio" value="stella" data-template-url="https://github.com/site/gitignore/stella">
            <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-check select-menu-item-icon" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 12 5 l -8 8 l -4 -4 l 1.5 -1.5 L 4 10 l 6.5 -6.5 L 12 5 Z" /></svg>
            <span class="text-normal select-menu-item-text" data-menu-button-text="">stella</span>
          </label>
      </div>

      <div class="select-menu-no-results">Nothing to show</div>
    </div>
  </details-menu>
</details>

    </div>


    <input name="new_filename" class="js-new-filename-field" id="blob-edit-path" type="hidden" value="SECURITY.md" data-default-value="">
    <div class="d-none">
      <span class="js-crumb-template js-path-segment"><a href="" data-pjax="true"><span>REPLACEME</span></a></span>
      <span class="separator js-crumb-separator">/</span>
    </div>

</div>

  <div class="js-template-suggestion px-3 mt-3 hide-sm hide-md d-none" data-template-suggestion-pattern="^FUNDING\.yml$">
    <div class="flash">
      <p>
        <code>.github/FUNDING.yml</code> shows the community how to support this project.

        Please see our
        <a href="https://help.github.com/articles/displaying-a-sponsor-button-in-your-repository">repository funding links documentation</a>
        for more information on formatting and what is and isn't allowed in this file.
      </p>

        <p>
          Please note that funding links are currently <em>disabled</em> on this repository. Visit
          <a href="/cmangos/mangos-tbc/settings">repository settings</a>
          to enable display of your funding links.
        </p>
    </div>
  </div>


<input name="commit" class="js-commit-oid" type="hidden" value="5286fde5d5fdea58ff66090c3edb1211001ada96" data-default-value="5286fde5d5fdea58ff66090c3edb1211001ada96">
  <input name="quick_pull" type="hidden" value="cmangos:master">

<input name="pr" type="hidden" value="">



<div class="file mx-lg-3 border-left-0 border-right-0 border-lg-left border-lg-right border-lg-bottom js-code-editor container-preview show-code  " data-github-confirm-unload="false">
  <div class="file-header mb-2 d-flex flex-items-center pr-0">

      <div class="tabnav-tabs js-file-editor-nav d-flex flex-auto d-md-block">
        <button class="btn-link code px-3 px-sm-6 px-lg-3 flex-item-equal flex-md-auto selected tabnav-tab js-blob-edit-code js-blob-edit-tab" aria-current="true" type="button" data-tab="show-code">
          <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-code" aria-hidden="true" viewBox="0 0 14 16" width="14" height="16" version="1.1"><path fill-rule="evenodd" d="M 9.5 3 L 8 4.5 L 11.5 8 L 8 11.5 L 9.5 13 L 14 8 L 9.5 3 Z m -5 0 L 0 8 l 4.5 5 L 6 11.5 L 2.5 8 L 6 4.5 L 4.5 3 Z" /></svg>
          Edit new file
        </button>
        <button class="flex-item-equal flex-md-auto btn-link preview tabnav-tab js-blob-edit-preview js-blob-edit-tab" type="button" data-tab="preview">
          <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-eye" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8.06 2 C 3 2 0 8 0 8 s 3 6 8.06 6 C 13 14 16 8 16 8 s -3 -6 -7.94 -6 Z M 8 12 c -2.2 0 -4 -1.78 -4 -4 c 0 -2.2 1.8 -4 4 -4 c 2.22 0 4 1.8 4 4 c 0 2.22 -1.78 4 -4 4 Z m 2 -4 c 0 1.11 -0.89 2 -2 2 c -1.11 0 -2 -0.89 -2 -2 c 0 -1.11 0.89 -2 2 -2 c 1.11 0 2 0.89 2 2 Z" /></svg>
          Preview
        </button>
      </div>

      <div class="file-actions d-none d-md-flex px-3 pr-md-6 px-lg-2">
        <select class="form-select select-sm js-code-indent-mode" id="indent-mode" aria-label="Indent mode">
          <optgroup label="Indent mode">
            <option value="space">Spaces</option>
<option value="tab">Tabs</option>
          </optgroup>
        </select>

        <select class="form-select select-sm js-code-indent-width" id="indent-size" aria-label="Indent size">
          <optgroup label="Indent size">
            <option value="2">2</option>
<option value="4">4</option>
<option value="8">8</option>
          </optgroup>
        </select>

        <select class="form-select select-sm js-code-wrap-mode" id="line-wrap-mode" aria-label="Line wrap mode">
          <optgroup label="Line wrap mode">
            <option value="off">No wrap</option>
<option value="on">Soft wrap</option>
          </optgroup>
        </select>
      </div>
  </div>

  <input name="content_changed" class="js-blob-contents-changed" type="hidden" value="true" data-default-value="false">



  <div class="commit-create  position-relative ">

    <textarea name="value" class="form-control file-editor-textarea js-blob-contents js-code-textarea" autofocus="" style="display: none;" spellcheck="false" aria-label="Enter file contents here" placeholder="Enter file contents here" rows="35" data-allow-unchanged="false" data-codemirror-mode="" data-filename="SECURITY.md"># Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| &lt; 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
</textarea>
  <div class="CodeMirror cm-s-github-light" style="height: 712px;"><div tabindex="-1" class="CodeMirror-vscrollbar" cm-not-content="true"><div style="height: 0px; min-width: 1px;"></div></div><div tabindex="-1" class="CodeMirror-hscrollbar" cm-not-content="true"><div style="width: 0px; height: 100%; min-height: 1px;"></div></div><div class="CodeMirror-scrollbar-filler" cm-not-content="true"></div><div class="CodeMirror-gutter-filler" cm-not-content="true"></div><div tabindex="-1" class="CodeMirror-scroll" draggable="true"><div class="CodeMirror-sizer" style="padding-right: 0px; padding-bottom: 0px; margin-bottom: -16px; margin-left: 53px; border-right-width: 14px; min-height: 404px; min-width: 495.4px;"><div style="top: 0px; position: relative;"><div class="CodeMirror-lines" role="presentation"><div role="presentation" style="outline: invert; position: relative;"><div class="CodeMirror-measure"><span><span>​</span>x</span><div class="CodeMirror-linenumber CodeMirror-gutter-elt"><div>22</div></div></div><div class="CodeMirror-measure"></div><div style="position: relative; z-index: 1;"></div><div class="CodeMirror-cursors"></div><div tabindex="0" class="CodeMirror-code" role="presentation" contenteditable="true" spellcheck="false" autocorrect="off" autocapitalize="off"><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">1</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation"># Security Policy</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">2</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">3</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">## Supported Versions</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">4</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">5</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">Use this section to tell people about which versions of your project are</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">6</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">currently being supported with security updates.</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">7</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">8</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">| Version | Supported          |</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">9</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">| ------- | ------------------ |</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">10</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">| 5.1.x   | :white_check_mark: |</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">11</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">| 5.0.x   | :x:                |</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">12</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">| 4.0.x   | :white_check_mark: |</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">13</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">| &lt; 4.0   | :x:                |</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">14</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">15</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">## Reporting a Vulnerability</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">16</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">17</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">Use this section to tell people how to report a vulnerability.</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">18</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">19</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">Tell them where to go, how often they can expect to get an update on a</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">20</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">reported vulnerability, what to expect if the vulnerability is accepted or</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">21</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation">declined, etc.</span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" style="left: -53px;" contenteditable="false"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 21px;">22</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation"><span cm-text="">​</span></span></pre></div></div></div></div></div></div><div style="top: 404px; width: 1px; height: 14px; border-bottom-color: transparent; border-bottom-width: 0px; border-bottom-style: solid; position: absolute;"></div><div class="CodeMirror-gutters" style="height: 418px;"><div class="CodeMirror-gutter CodeMirror-linenumbers" style="width: 53px;"></div></div></div></div></div>

  <div class="loading-preview-msg"><p class="preview-msg text-gray">Loading preview…</p></div>
  <div class="no-changes-preview-msg"><p class="preview-msg text-gray">No changes to display.</p></div>
  <div class="error-preview-msg"><p class="preview-msg text-gray">Unable to load this preview, sorry.</p></div>
  <div class="js-commit-preview commit-preview   ">
  </div>
</div>




<div class="d-flex flex-column d-md-block col-lg-11 offset-lg-1 pr-lg-3 js-file-commit-form ">

  
    <span class="commit-form-avatar hide-sm hide-md ">
      <a class="d-inline-block" href="/GhostsOfHiroshima" data-octo-dimensions="link_type:self" data-octo-click="hovercard-link-click" data-hovercard-url="/hovercards?user_id=51129449" data-hovercard-type="user"><img width="48" height="48" class="float-left rounded-1" alt="@GhostsOfHiroshima" src="https://avatars0.githubusercontent.com/u/51129449?s=96&amp;v=4"></a>
    </span>

    <div class="commit-form position-relative  mb-2 p-3 border-0 border-lg-top border-lg-right border-lg-left border-lg-bottom rounded-1">
      <h3>Propose new file</h3>

      <div class="text-orange js-too-long-error">
        <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-light-bulb" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 6.5 0 C 3.48 0 1 2.19 1 5 c 0 0.92 0.55 2.25 1 3 c 1.34 2.25 1.78 2.78 2 4 v 1 h 5 v -1 c 0.22 -1.22 0.66 -1.75 2 -4 c 0.45 -0.75 1 -2.08 1 -3 c 0 -2.81 -2.48 -5 -5.5 -5 Z m 3.64 7.48 c -0.25 0.44 -0.47 0.8 -0.67 1.11 c -0.86 1.41 -1.25 2.06 -1.45 3.23 c -0.02 0.05 -0.02 0.11 -0.02 0.17 H 5 c 0 -0.06 0 -0.13 -0.02 -0.17 c -0.2 -1.17 -0.59 -1.83 -1.45 -3.23 c -0.2 -0.31 -0.42 -0.67 -0.67 -1.11 C 2.44 6.78 2 5.65 2 5 c 0 -2.2 2.02 -4 4.5 -4 c 1.22 0 2.36 0.42 3.22 1.19 C 10.55 2.94 11 3.94 11 5 c 0 0.66 -0.44 1.78 -0.86 2.48 Z M 4 14 h 5 c -0.23 1.14 -1.3 2 -2.5 2 s -2.27 -0.86 -2.5 -2 Z" /></svg>
        <strong>ProTip!</strong> Great commit summaries contain fewer than 50 characters. Place extra information in the extended description.
      </div>

      <label class="sr-only" for="commit-summary-input">
        Commit summary
      </label>
      <input name="message" class="form-control input-block input-contrast js-new-blob-commit-summary" id="commit-summary-input" type="text" placeholder="Create SECURITY.md" value="" autocomplete="off">
      <input name="placeholder_message" class="js-commit-message-fallback" type="hidden" value="Create SECURITY.md" data-default-value="Create SECURITY.md">

      <label class="sr-only" for="commit-description-textarea">
        Optional extended description
      </label>

      <div class="position-relative">
        <text-expander data-emoji-url="/autocomplete/emoji" data-mention-url="/suggestions?mention_suggester=1&amp;repository=mangos-tbc&amp;user_id=cmangos" keys=": @ #" data-issue-url="/suggestions?issue_suggester=1&amp;repository=mangos-tbc&amp;user_id=cmangos">
          <textarea name="description" class="form-control input-block input-contrast comment-form-textarea js-quick-submit" id="commit-description-textarea" placeholder="Add an optional extended description…"></textarea>
        </text-expander>
      </div>


      

    </div>

    <button disabled="" class="btn btn-primary js-blob-submit flex-auto mx-3 ml-md-3 mr-md-0 ml-lg-0 mb-3 mb-md-0" id="submit-file" type="submit" data-pull-text="Propose new file" data-edit-text="Commit new file">
      Propose new file
    </button>

      <a class="btn btn-danger flex-auto text-center mx-3 mx-md-0" href="/cmangos/mangos-tbc">Cancel</a>

      
</div>


</form>    </div>


  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">© 2019 <span title="0.79909s from unicorn-5975954444-88k56">GitHub</span>, Inc.</li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>

    <a title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" aria-label="Homepage" href="https://github.com">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-mark-github" aria-hidden="true" viewBox="0 0 16 16" width="24" height="24" version="1.1"><path fill-rule="evenodd" d="M 8 0 C 3.58 0 0 3.58 0 8 c 0 3.54 2.29 6.53 5.47 7.59 c 0.4 0.07 0.55 -0.17 0.55 -0.38 c 0 -0.19 -0.01 -0.82 -0.01 -1.49 c -2.01 0.37 -2.53 -0.49 -2.69 -0.94 c -0.09 -0.23 -0.48 -0.94 -0.82 -1.13 c -0.28 -0.15 -0.68 -0.52 -0.01 -0.53 c 0.63 -0.01 1.08 0.58 1.23 0.82 c 0.72 1.21 1.87 0.87 2.33 0.66 c 0.07 -0.52 0.28 -0.87 0.51 -1.07 c -1.78 -0.2 -3.64 -0.89 -3.64 -3.95 c 0 -0.87 0.31 -1.59 0.82 -2.15 c -0.08 -0.2 -0.36 -1.02 0.08 -2.12 c 0 0 0.67 -0.21 2.2 0.82 c 0.64 -0.18 1.32 -0.27 2 -0.27 c 0.68 0 1.36 0.09 2 0.27 c 1.53 -1.04 2.2 -0.82 2.2 -0.82 c 0.44 1.1 0.16 1.92 0.08 2.12 c 0.51 0.56 0.82 1.27 0.82 2.15 c 0 3.07 -1.87 3.75 -3.65 3.95 c 0.29 0.25 0.54 0.73 0.54 1.48 c 0 1.07 -0.01 1.93 -0.01 2.2 c 0 0.21 0.15 0.46 0.55 0.38 A 8.013 8.013 0 0 0 16 8 c 0 -4.42 -3.58 -8 -8 -8 Z" /></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div class="ajax-error-message flash flash-error" id="ajax-error-message">
    <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-alert" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8.893 1.5 c -0.183 -0.31 -0.52 -0.5 -0.887 -0.5 s -0.703 0.19 -0.886 0.5 L 0.138 13.499 a 0.98 0.98 0 0 0 0 1.001 c 0.193 0.31 0.53 0.501 0.886 0.501 h 13.964 c 0.367 0 0.704 -0.19 0.877 -0.5 a 1.03 1.03 0 0 0 0.01 -1.002 L 8.893 1.5 Z m 0.133 11.497 H 6.987 v -2.003 h 2.039 v 2.003 Z m 0 -3.004 H 6.987 V 5.987 h 2.039 v 4.006 Z" /></svg>
    <button class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error" type="button">
      <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-x" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 7.48 8 l 3.75 3.75 l -1.48 1.48 L 6 9.48 l -3.75 3.75 l -1.48 -1.48 L 4.52 8 L 0.77 4.25 l 1.48 -1.48 L 6 6.52 l 3.75 -3.75 l 1.48 1.48 L 7.48 8 Z" /></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    <script src="https://github.githubassets.com/assets/compat-bootstrap-90c0ace0.js" type="application/javascript" crossorigin="anonymous" integrity="sha512-BlCvumXWTvpASEdhCGiahDUDf7Bwb8QXA2XnnSnqJ9QafxcNcrNYUNYS2wXmd3nEpO//+zlZa9DSV9zmu5MqRg=="></script>
    <script src="https://github.githubassets.com/assets/frameworks-d4d6526c.js" type="application/javascript" crossorigin="anonymous" integrity="sha512-LcoOfcAm3xWwV+pRwTOdnnM4ZYub5QxXDo8wthOGfJD7c4nc+C/RaTBoLlS/e5xSKBloJbaQEBYW13PdB0yO9w=="></script>
    
    <script src="https://github.githubassets.com/assets/github-bootstrap-56a00fa0.js" type="application/javascript" async="async" crossorigin="anonymous" integrity="sha512-8mD3/f6p6y5x4bkl/FSAO3F/pMKM44mgVEmoMe4mwlfIL9UsbVEiE/0zcCRyA8fHoIL40YL+w4U8i1tiWmOLIw=="></script>
    
          <script src="https://github.githubassets.com/assets/editor-85a70efd.js" type="application/javascript" async="async" crossorigin="anonymous" integrity="sha512-Yh2nKGQuMLJgMM7047k5I9NZv1kuDxxDrt9DOcghLTvTa+a6h/2fEF0+4I17I0Ms8s62JN/eQs3b0zbHZp7smQ=="></script>

    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner" hidden="">
    <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-alert" aria-hidden="true" viewBox="0 0 16 16" width="16" height="16" version="1.1"><path fill-rule="evenodd" d="M 8.893 1.5 c -0.183 -0.31 -0.52 -0.5 -0.887 -0.5 s -0.703 0.19 -0.886 0.5 L 0.138 13.499 a 0.98 0.98 0 0 0 0 1.001 c 0.193 0.31 0.53 0.501 0.886 0.501 h 13.964 c 0.367 0 0.704 -0.19 0.877 -0.5 a 1.03 1.03 0 0 0 0.01 -1.002 L 8.893 1.5 Z m 0.133 11.497 H 6.987 v -2.003 h 2.039 v 2.003 Z m 0 -3.004 H 6.987 V 5.987 h 2.039 v 4.006 Z" /></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open="">
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" aria-label="Close dialog" type="button" data-close-dialog="">
        <svg xmlns="http://www.w3.org/2000/svg" class="octicon octicon-x" aria-hidden="true" viewBox="0 0 12 16" width="12" height="16" version="1.1"><path fill-rule="evenodd" d="M 7.48 8 l 3.75 3.75 l -1.48 1.48 L 6 9.48 l -3.75 3.75 l -1.48 -1.48 L 4.52 8 L 0.77 4.25 l 1.48 -1.48 L 6 6.52 l 3.75 -3.75 l 1.48 1.48 L 7.48 8 Z" /></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div tabindex="0" class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

  <div class="js-global-screen-reader-notice sr-only" aria-live="polite"></div>

  


</body></html>

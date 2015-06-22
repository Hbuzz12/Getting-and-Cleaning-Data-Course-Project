


<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>gcd-wearable/CodeBook.md at master · decasm/gcd-wearable</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="decasm/gcd-wearable" name="twitter:title" /><meta content="gcd-wearable - Getting and Cleaning Data - Wearable" name="twitter:description" /><meta content="https://avatars0.githubusercontent.com/u/49514?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars0.githubusercontent.com/u/49514?v=3&amp;s=400" property="og:image" /><meta content="decasm/gcd-wearable" property="og:title" /><meta content="https://github.com/decasm/gcd-wearable" property="og:url" /><meta content="gcd-wearable - Getting and Cleaning Data - Wearable" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTA3MDA1OTU6OTgyNmFjNDlkNTRlZjg4OTJiOWUxODQxMGQ5MjA3NGQ6YTY4N2EyMmYzMjZkODM1NTdmYWE0ZTQ4MzJlODk5MDY0NWE0NTRmMzA2MDYzMzc5Y2M2NjViMDkyMzBjOTkwMw==--b8565bbec14bef1f1495cdfcf2f9e5b0c7b3f67b">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

        <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="B4BF7275:67DE:69A26DE:55874547" name="octolytics-dimension-request_id" /><meta content="10700595" name="octolytics-actor-id" /><meta content="Hbuzz12" name="octolytics-actor-login" /><meta content="db52f1762ee9d8b9214a67c6d86b53ce1fffa4c3753e9ed20645c302a0b72cd2" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged In">
    <meta name="is-dotcom" content="true">
      <meta name="hostname" content="github.com">
    <meta name="user-login" content="Hbuzz12">

      <link rel="icon" sizes="any" mask href="https://assets-cdn.github.com/pinned-octocat.svg">
      <meta name="theme-color" content="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="r+NjBQdhT8nbmhV+okE3GQ6KnKqLWu8S37vrN97Lyr+p1LLkuN/FneZ+tfo9zKuQkAfWmIFD8T4m2pAXzvP69g==" name="csrf-token" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github/index-805b1dc56a27171cceb8daae5c9e50c759789b9473bca4278a8145697ca3e05b.css" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2/index-7f8f14b96da3b21f83e68e993b1c2a60d443d867b62bfe83c1cfd54249ce9913.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="8faa43c6e2f704a4d27acb74601b9876">

      
  <meta name="description" content="gcd-wearable - Getting and Cleaning Data - Wearable">
  <meta name="go-import" content="github.com/decasm/gcd-wearable git https://github.com/decasm/gcd-wearable.git">

  <meta content="49514" name="octolytics-dimension-user_id" /><meta content="decasm" name="octolytics-dimension-user_login" /><meta content="29608501" name="octolytics-dimension-repository_id" /><meta content="decasm/gcd-wearable" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="29608501" name="octolytics-dimension-repository_network_root_id" /><meta content="decasm/gcd-wearable" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/decasm/gcd-wearable/commits/master.atom" rel="alternate" title="Recent Commits to gcd-wearable:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production macintosh vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      


        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/decasm/gcd-wearable/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/decasm/gcd-wearable/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
      </div>

      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:Hbuzz12"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-inbox"></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new..."
       data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus left"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="decasm/gcd-wearable">This repository</span>
  </div>
    <a class="dropdown-item" href="/decasm/gcd-wearable/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-s js-menu-target" href="#"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@Hbuzz12" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/10700595?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">Hbuzz12</strong>
        </div>
        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/Hbuzz12" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>
        <div class="dropdown-divider"></div>


        <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a>

        <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="UTaipSBd4R4L5ep3eyqtvFTrD5s2OBUFXip2SPTkcOI+JYIHgJ4bFRfBqY7pbUloCUort8EDXvmmjH4AnilHQA==" /></div>
          <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>

        

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">

        
<ul class="pagehead-actions">

  <li>
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="9Ijg3PuMqrKcYbl69K4e6Xm/A9AnWgC6OgE4eequ4kvfuK2Fjm5e8M8Ydu/e5qf8BnFXzXtXx9eto9/RoyBJ5w==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="29608501" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/decasm/gcd-wearable/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>
        <a class="social-count js-social-count" href="/decasm/gcd-wearable/watchers">
          1
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
                    Stop ignoring
                  </span>
                </div>
              </div>

            </div>

          </div>
        </div>
      </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/decasm/gcd-wearable/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="9q8g4FL4Mk1N8sqVz4bczeprv9OZdxH+GqxA1ql6YO2yXMPV3QtT7hepgwSB4R5/cWiwL27ee6eG12gdmXPZGQ==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar decasm/gcd-wearable"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/decasm/gcd-wearable/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/decasm/gcd-wearable/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="oj6wHojroKcoMkwN6hB8wuDb4dVRhJwDuJ+TrcbevntAd7vN14OMrC7nal8HPSz8m6nltLSS+8e44r4M0oKvvw==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star decasm/gcd-wearable"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/decasm/gcd-wearable/stargazers">
          0
        </a>
</form>  </div>

  </li>

        <li>
          <form accept-charset="UTF-8" action="/decasm/gcd-wearable/fork" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="7aZtnzJisj8o0zgUJvAsOSdZazJdvj2CrT+J/Qfxah3U+/verut95X46Q1Iu18UKkWAZaJnf6DtJqHs43xFbSA==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of decasm/gcd-wearable to your account"
                aria-label="Fork your own copy of decasm/gcd-wearable to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
            <a href="/decasm/gcd-wearable/network" class="social-count">0</a>
</form>        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/decasm" class="url fn" itemprop="url" rel="author"><span itemprop="title">decasm</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/decasm/gcd-wearable" data-pjax="#js-repo-pjax-container">gcd-wearable</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/decasm/gcd-wearable/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/decasm/gcd-wearable" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /decasm/gcd-wearable">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/decasm/gcd-wearable/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /decasm/gcd-wearable/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/decasm/gcd-wearable/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /decasm/gcd-wearable/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/decasm/gcd-wearable/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /decasm/gcd-wearable/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/decasm/gcd-wearable/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /decasm/gcd-wearable/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/decasm/gcd-wearable/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /decasm/gcd-wearable/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                  
<div class="js-clone-url clone-url open"
  data-protocol-type="http">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/decasm/gcd-wearable.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="ssh">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:decasm/gcd-wearable.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="subversion">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/decasm/gcd-wearable" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<div class="clone-options">You can clone with
  <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="cHm48jW0KHS/sFg0NnQeVUktHl5yOXrKTU1H177Nt6vVMkhBwwlCs1MJheCFQdxhG1msmcz6s02OTO8+t1cyVA==" /></div><button class="btn-link js-clone-selector" data-protocol="http" type="submit">HTTPS</button></form>, <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="+7LUTVYbySf5bdI06XFOLOOdW4uiCtqHU9DpipYsrp2HQCnt9C6ev4ZoBA0K0yZoDnVWdnA2+Sl+yFSfbO84dA==" /></div><button class="btn-link js-clone-selector" data-protocol="ssh" type="submit">SSH</button></form>, or <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="plNYHC8IgO8CiMc14Etd2PZVubBJAkNpUdoYuyjuQWc3nO3YvdYfku4tbl9FLLto30IJlTaqTd3CvcXsTC0KUw==" /></div><button class="btn-link js-clone-selector" data-protocol="subversion" type="submit">Subversion</button></form>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</div>

  <a href="github-mac://openRepo/https://github.com/decasm/gcd-wearable" class="btn btn-sm sidebar-button" title="Save decasm/gcd-wearable to your computer and use it in GitHub Desktop." aria-label="Save decasm/gcd-wearable to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>



                <a href="/decasm/gcd-wearable/archive/master.zip"
                   class="btn btn-sm sidebar-button"
                   aria-label="Download the contents of decasm/gcd-wearable as a zip file"
                   title="Download the contents of decasm/gcd-wearable as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/decasm/gcd-wearable/blob/6a341bdbdcfa3676a84327e21d2222c9fb23411d/CodeBook.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:e1434a7b18843cce94e1b000610a3e87 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/decasm/gcd-wearable/blob/master/CodeBook.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/decasm/gcd-wearable/find/master"
          class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/decasm/gcd-wearable" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">gcd-wearable</span></a></span></span><span class="separator">/</span><strong class="final-path">CodeBook.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="" class="avatar" height="24" src="https://2.gravatar.com/avatar/e970ef350855025a60df53621abf1b38?d=https%3A%2F%2Fassets-cdn.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png&amp;r=x&amp;s=140" width="24" />
        <span class="author"><span>Devon Smith</span></span>
        <time datetime="2015-01-24T21:23:10Z" is="relative-time">Jan 24, 2015</time>
        <div class="commit-title">
            <a href="/decasm/gcd-wearable/commit/6a341bdbdcfa3676a84327e21d2222c9fb23411d" class="message" data-pjax="true" title="Clarifications/rewordign">Clarifications/rewordign</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>0</strong>
           contributors
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-actions">

      <div class="btn-group">
        <a href="/decasm/gcd-wearable/raw/master/CodeBook.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/decasm/gcd-wearable/blame/master/CodeBook.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/decasm/gcd-wearable/commits/master/CodeBook.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="github-mac://openRepo/https://github.com/decasm/gcd-wearable?branch=master&amp;filepath=CodeBook.md"
           aria-label="Open this file in GitHub for Mac"
           data-ga-click="Repository, open with desktop, type:mac">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <form accept-charset="UTF-8" action="/decasm/gcd-wearable/edit/master/CodeBook.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="8/dp3mUxgY8EtHKFSSkq1ihgNPRmnISV/BVtZpQcv2SaXJebRBwAqwik+So63A1cEDxHWahWGZLi7PFIEoAXJg==" /></div>
              <button class="octicon-btn tooltipped tooltipped-n" type="submit" aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <form accept-charset="UTF-8" action="/decasm/gcd-wearable/delete/master/CodeBook.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="lZW9OlmMKLcij4CExfZPxzGmxKEAKqD/aOsp0q+pjGL9UC95vNxtehGMJWwdHI1l4Vg2DWoexwCFWCJVq14IDg==" /></div>
            <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-n" type="submit" aria-label="Fork this project and delete this file" data-disable-with>
              <span class="octicon octicon-trashcan"></span>
            </button>
</form>    </div>

    <div class="file-info">
        187 lines (160 sloc)
        <span class="file-info-divider"></span>
      7.321 kB
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1><a id="user-content-code-book--getting-and-cleaning-data---course-project" class="anchor" href="#code-book--getting-and-cleaning-data---course-project" aria-hidden="true"><span class="octicon octicon-link"></span></a>Code Book :: Getting and Cleaning Data - Course Project</h1>

<h2><a id="user-content-dataset-overview" class="anchor" href="#dataset-overview" aria-hidden="true"><span class="octicon octicon-link"></span></a>Dataset Overview</h2>

<p>The original data for this process was collected from a smartphone by a variety of subjects while engaging in several activties.
All subjects engaged in all activities.
Raw data was gathered from the phone's accelerometer and its gyroscope.
The values used in this process were derived by <a href="#datadetail">a variety of calculations (described below)</a>.</p>

<p>Conceptually, this process summarizes the original data by 
1. Subsetting the data, pulling out only fields which are a mean or a standard deviation
2. Grouping the data by the subject and activity
3. Averaging all the data for a given subject/activity pairing.</p>

<p>The final dataset is written to "tidy.txt" and can be read in with the following R command:</p>

<pre><code>verify &lt;- read.table("data/tidy.txt", sep=" ", headers=TRUE)
</code></pre>

<h2><a id="user-content-data-cleaning-description" class="anchor" href="#data-cleaning-description" aria-hidden="true"><span class="octicon octicon-link"></span></a>Data Cleaning Description</h2>

<h3><a id="user-content-cleaning-data-labels" class="anchor" href="#cleaning-data-labels" aria-hidden="true"><span class="octicon octicon-link"></span></a>Cleaning data labels</h3>

<p>The input labels used abbreviated forms of descriptive terms.
Abbreviations were expanded and duplications and punctuation were removed so that
"tBodyAccJerk-std()-X" became "timeBodyAccelerometerJerkStdDevX"
and
"fBodyBodyGyroMag-mean()" became "frequencyBodyGyroscopeMagnitudeMean".</p>

<h3><a id="user-content-merging-data" class="anchor" href="#merging-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Merging data</h3>

<p>The data was divided in two different ways. First, it was partioned into train and test subsets.
Each of those was then divided into a measurements file, a subject identifier file, and an activity code file.
There was also a single activity label file which paired the numeric code to a string label.</p>

<p>For each of train and test, the measurements file as read in using the cleaned up columns from above.
Then the subject id and activity id were read in and combined (via cbind) with the measurements data.
Then the complete train and test sets were merged together with rbind.</p>

<h3><a id="user-content-filtering-data" class="anchor" href="#filtering-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Filtering data</h3>

<p>From the fully merged data frame, a subset of columns was extracted where the columns indicated a mean or a standard deviation,
along with the subject id and activity id.
The activity ids were then replaced with corresponding activity labels.</p>

<h3><a id="user-content-summarizing-the-data" class="anchor" href="#summarizing-the-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Summarizing the data</h3>

<p>For each subject/activity pair, all the data points for a given column were averaged together and the resultant data frame
written to file.</p>

<h2><a id="user-content-data-column-description" class="anchor" href="#data-column-description" aria-hidden="true"><span class="octicon octicon-link"></span></a>Data Column Description</h2>

<p>The first two columns are for identifying the person and the activity they were engaging in for the data collection.</p>

<ol>
<li>Subject - Identifier for the subject providing the data, ranging from 1 to 30.</li>
<li>Activity - A label for the level activity of a data point. One of "WALKING", "WALKING_UPSTAIRS", "WALKING_DOWNSTAIRS", "SITTING", "STANDING", or "LAYING".</li>
</ol>

<p>Each subsequent column is an average of values for a give Subject/AcivityLevel in the range -1 to 1.
<a href="#datadetail">See below for more detail on the variables and their derivation.</a></p>

<p>The label for each variable is a combination of these facets:</p>

<ul>
<li>time, frequency, or angle</li>
<li>Body or Gravity</li>
<li>Accelerometer or Gyroscope</li>
<li>Jerk (or empty)</li>
<li>Magnitude (or empty)</li>
<li>Mean or StdDev(standard deviation)</li>
<li>Freq (or empty)</li>
<li>X, Y, or Z axis</li>
</ul>

<h2><a id="user-content-complete-list-of-columns" class="anchor" href="#complete-list-of-columns" aria-hidden="true"><span class="octicon octicon-link"></span></a>Complete list of columns</h2>

<ul>
<li>Subject</li>
<li>Activity</li>
<li>timeBodyAccelerometerMeanX</li>
<li>timeBodyAccelerometerMeanY</li>
<li>timeBodyAccelerometerMeanZ</li>
<li>timeGravityAccelerometerMeanX</li>
<li>timeGravityAccelerometerMeanY</li>
<li>timeGravityAccelerometerMeanZ</li>
<li>timeBodyAccelerometerJerkMeanX</li>
<li>timeBodyAccelerometerJerkMeanY</li>
<li>timeBodyAccelerometerJerkMeanZ</li>
<li>timeBodyGyroscopeMeanX</li>
<li>timeBodyGyroscopeMeanY</li>
<li>timeBodyGyroscopeMeanZ</li>
<li>timeBodyGyroscopeJerkMeanX</li>
<li>timeBodyGyroscopeJerkMeanY</li>
<li>timeBodyGyroscopeJerkMeanZ</li>
<li>timeBodyAccelerometerMagnitudeMean</li>
<li>timeGravityAccelerometerMagnitudeMean</li>
<li>timeBodyAccelerometerJerkMagnitudeMean</li>
<li>timeBodyGyroscopeMagnitudeMean</li>
<li>timeBodyGyroscopeJerkMagnitudeMean</li>
<li>frequencyBodyAccelerometerMeanX</li>
<li>frequencyBodyAccelerometerMeanY</li>
<li>frequencyBodyAccelerometerMeanZ</li>
<li>frequencyBodyAccelerometerMeanFreqX</li>
<li>frequencyBodyAccelerometerMeanFreqY</li>
<li>frequencyBodyAccelerometerMeanFreqZ</li>
<li>frequencyBodyAccelerometerJerkMeanX</li>
<li>frequencyBodyAccelerometerJerkMeanY</li>
<li>frequencyBodyAccelerometerJerkMeanZ</li>
<li>frequencyBodyAccelerometerJerkMeanFreqX</li>
<li>frequencyBodyAccelerometerJerkMeanFreqY</li>
<li>frequencyBodyAccelerometerJerkMeanFreqZ</li>
<li>frequencyBodyGyroscopeMeanX</li>
<li>frequencyBodyGyroscopeMeanY</li>
<li>frequencyBodyGyroscopeMeanZ</li>
<li>frequencyBodyGyroscopeMeanFreqX</li>
<li>frequencyBodyGyroscopeMeanFreqY</li>
<li>frequencyBodyGyroscopeMeanFreqZ</li>
<li>frequencyBodyAccelerometerMagnitudeMean</li>
<li>frequencyBodyAccelerometerMagnitudeMeanFreq</li>
<li>frequencyBodyAccelerometerJerkMagnitudeMean</li>
<li>frequencyBodyAccelerometerJerkMagnitudeMeanFreq</li>
<li>frequencyBodyGyroscopeMagnitudeMean</li>
<li>frequencyBodyGyroscopeMagnitudeMeanFreq</li>
<li>frequencyBodyGyroscopeJerkMagnitudeMean</li>
<li>frequencyBodyGyroscopeJerkMagnitudeMeanFreq</li>
<li>angletBodyAccelerometerMeangravity</li>
<li>angletBodyAccelerometerJerkMeangravityMean</li>
<li>angletBodyGyroscopeMeangravityMean</li>
<li>angletBodyGyroscopeJerkMeangravityMean</li>
<li>angleXgravityMean</li>
<li>angleYgravityMean</li>
<li>angleZgravityMean</li>
<li>timeBodyAccelerometerStdDevX</li>
<li>timeBodyAccelerometerStdDevY</li>
<li>timeBodyAccelerometerStdDevZ</li>
<li>timeGravityAccelerometerStdDevX</li>
<li>timeGravityAccelerometerStdDevY</li>
<li>timeGravityAccelerometerStdDevZ</li>
<li>timeBodyAccelerometerJerkStdDevX</li>
<li>timeBodyAccelerometerJerkStdDevY</li>
<li>timeBodyAccelerometerJerkStdDevZ</li>
<li>timeBodyGyroscopeStdDevX</li>
<li>timeBodyGyroscopeStdDevY</li>
<li>timeBodyGyroscopeStdDevZ</li>
<li>timeBodyGyroscopeJerkStdDevX</li>
<li>timeBodyGyroscopeJerkStdDevY</li>
<li>timeBodyGyroscopeJerkStdDevZ</li>
<li>timeBodyAccelerometerMagnitudeStdDev</li>
<li>timeGravityAccelerometerMagnitudeStdDev</li>
<li>timeBodyAccelerometerJerkMagnitudeStdDev</li>
<li>timeBodyGyroscopeMagnitudeStdDev</li>
<li>timeBodyGyroscopeJerkMagnitudeStdDev</li>
<li>frequencyBodyAccelerometerStdDevX</li>
<li>frequencyBodyAccelerometerStdDevY</li>
<li>frequencyBodyAccelerometerStdDevZ</li>
<li>frequencyBodyAccelerometerJerkStdDevX</li>
<li>frequencyBodyAccelerometerJerkStdDevY</li>
<li>frequencyBodyAccelerometerJerkStdDevZ</li>
<li>frequencyBodyGyroscopeStdDevX</li>
<li>frequencyBodyGyroscopeStdDevY</li>
<li>frequencyBodyGyroscopeStdDevZ</li>
<li>frequencyBodyAccelerometerMagnitudeStdDev</li>
<li>frequencyBodyAccelerometerJerkMagnitudeStdDev</li>
<li>frequencyBodyGyroscopeMagnitudeStdDev</li>
<li>frequencyBodyGyroscopeJerkMagnitudeStdDev</li>
</ul>

<h2><a id="user-content-data-description-from-source" class="anchor" href="#data-description-from-source" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-datadetail">Data description from source</a></h2>

<p>The features selected for this database come from the accelerometer and
gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals
(prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they
were filtered using a median filter and a 3rd order low pass Butterworth filter
with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration
signal was then separated into body and gravity acceleration signals
(tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter
with a corner frequency of 0.3 Hz.</p>

<p>Subsequently, the body linear acceleration and angular velocity were derived in
time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the
magnitude of these three-dimensional signals were calculated using the Euclidean
norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).</p>

<p>Finally a Fast Fourier Transform (FFT) was applied to some of these signals
producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag,
fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain
signals).</p>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
      <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.05089s from github-fe141-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-808fcfcd63c9ecba3e84453f540cb1cbafde48c6b30c1d51ebd4e67e88ff66bd.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github/index-a8f739e9ac81819d15d14797161c10eefd379dc611a50534a8987401cc77821f.js"></script>
      
      
  </body>
</html>


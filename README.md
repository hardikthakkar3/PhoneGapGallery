


<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>datePicker/README.md at master · hardikthakkar3/datePicker</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="hardikthakkar3/datePicker" name="twitter:title" /><meta content="datePicker plugin for cordova which is compatible with iOS 8 in which UIActionSheet was depricated. " name="twitter:description" /><meta content="https://avatars1.githubusercontent.com/u/3090147?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars1.githubusercontent.com/u/3090147?v=3&amp;s=400" property="og:image" /><meta content="hardikthakkar3/datePicker" property="og:title" /><meta content="https://github.com/hardikthakkar3/datePicker" property="og:url" /><meta content="datePicker plugin for cordova which is compatible with iOS 8 in which UIActionSheet was depricated. " property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MzA5MDE0NzphMjUzYTNiMmFiNDNlNWI5Y2ZhODViNDRmYzk1MGU3ZjpmZmI3NDMxODE0NzdkYjIzMmI1ZjJkODkxZmNjMzhkODc1ZjIwZDY1ZDBjNWViODJhM2MwYjFhMmFlZjc3OGFj--fd20139beb63d0b2ee3b8e64b4d771838277dfff">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="CB588F33:1622:2B0656:555DAAD0" name="octolytics-dimension-request_id" /><meta content="3090147" name="octolytics-actor-id" /><meta content="hardikthakkar3" name="octolytics-actor-login" /><meta content="406dcfe7671afe5d3e588e8872bad8b257daef4994a729316ee5abcde00adca2" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged In">
    <meta class="js-ga-set" name="dimension2" content="Header v3">
    <meta name="is-dotcom" content="true">
      <meta name="hostname" content="github.com">
    <meta name="user-login" content="hardikthakkar3">

    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="ARegj6zLl+3NJWjgrpWidLVtF3j73ScPPJzVnCxhYvgfQiIr7V5ov5fMlqk6zSaW5+Fh8jh05SepTcyg+ceo2g==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github/index-bb90dbc2d23344db920cf940fae2bce74d59c7137f5adb7104494b23f35164d9.css" media="all" rel="stylesheet" />
    <link href="https://assets-cdn.github.com/assets/github2/index-4190b0977b9e2166bf19e2cef0c628ba77d6deaf2dda51987b61c5f58e96e255.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="51e199e3e04ea43152ee8b0b488012a7">

      
  <meta name="description" content="datePicker plugin for cordova which is compatible with iOS 8 in which UIActionSheet was depricated. ">
  <meta name="go-import" content="github.com/hardikthakkar3/datePicker git https://github.com/hardikthakkar3/datePicker.git">

  <meta content="3090147" name="octolytics-dimension-user_id" /><meta content="hardikthakkar3" name="octolytics-dimension-user_login" /><meta content="28181042" name="octolytics-dimension-repository_id" /><meta content="hardikthakkar3/datePicker" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="28181042" name="octolytics-dimension-repository_network_root_id" /><meta content="hardikthakkar3/datePicker" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/hardikthakkar3/datePicker/commits/master.atom" rel="alternate" title="Recent Commits to datePicker:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      


        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/hardikthakkar3/datePicker/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/hardikthakkar3/datePicker/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
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
          <li class="header-nav-item explore">
            <a class="header-nav-link" href="/explore" data-ga-click="Header, go to explore, text:explore">Explore</a>
          </li>
            <li class="header-nav-item">
              <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
            </li>
            <li class="header-nav-item">
              <a class="header-nav-link" href="/blog" data-ga-click="Header, go to blog, text:blog">Blog</a>
            </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
          </li>
      </ul>

      
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name" href="/hardikthakkar3" data-ga-click="Header, go to profile, text:username">
      <img alt="@hardikthakkar3" class="avatar" data-user="3090147" height="20" src="https://avatars1.githubusercontent.com/u/3090147?v=3&amp;s=40" width="20" />
      <span class="css-truncate">
        <span class="css-truncate-target">hardikthakkar3</span>
      </span>
    </a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link js-menu-target tooltipped tooltipped-s" href="/new" aria-label="Create new..." data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu">
        
<li>
  <a href="/new" data-ga-click="Header, create new repository, icon:repo"><span class="octicon octicon-repo"></span> New repository</a>
</li>
<li>
  <a href="/organizations/new" data-ga-click="Header, create new organization, icon:organization"><span class="octicon octicon-organization"></span> New organization</a>
</li>


  <li class="dropdown-divider"></li>
  <li class="dropdown-header">
    <span title="hardikthakkar3/datePicker">This repository</span>
  </li>
    <li>
      <a href="/hardikthakkar3/datePicker/issues/new" data-ga-click="Header, create new issue, icon:issue"><span class="octicon octicon-issue-opened"></span> New issue</a>
    </li>
    <li>
      <a href="/hardikthakkar3/datePicker/settings/collaboration" data-ga-click="Header, create new collaborator, icon:person"><span class="octicon octicon-person"></span> New collaborator</a>
    </li>

      </ul>
    </div>
  </li>

  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:hardikthakkar3"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:unread" data-hotkey="g n">
          <span class="mail-status unread"></span>
          <span class="octicon octicon-inbox"></span>
</a>  </span>

  </li>

  <li class="header-nav-item">
    <a class="header-nav-link tooltipped tooltipped-s" href="/settings/profile" id="account_settings" aria-label="Settings" data-ga-click="Header, go to settings, icon:settings">
      <span class="octicon octicon-gear"></span>
    </a>
  </li>

  <li class="header-nav-item">
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="/VnC7uFkD4//Bn20ttfjCKhtQ7ScrkAnr+1kJ8m5tBHj3v/XEF4xd4Vexai+1viFT46ycfOx3roKrO5yfl1V1w==" /></div>
      <button class="header-nav-link sign-out-button tooltipped tooltipped-s" aria-label="Sign out" data-ga-click="Header, sign out, icon:logout">
        <span class="octicon octicon-sign-out"></span>
      </button>
</form>  </li>

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
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="nV/iD1o/2oiAaVBCb2VRjzHE74nJ6429ebxo+1AJ5k7fBs2NEcfbx0/gOHEICfQV/JfVVXR4jZBwGRoF6K0dLA==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="28181042" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/hardikthakkar3/datePicker/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Unwatch
          </span>
        </a>
        <a class="social-count js-social-count" href="/hardikthakkar3/datePicker/watchers">
          1
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_subscribed" name="do" type="radio" value="subscribed" />
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

    <form accept-charset="UTF-8" action="/hardikthakkar3/datePicker/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Ue0LmphU6fQJkZz0b8XjxLKbQN4fKyi6FEwa0WMXEjswkvikSlFaHmvu78dhVTmg0gCUXSr1tYCiy9rFyg+zWQ==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar hardikthakkar3/datePicker"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/hardikthakkar3/datePicker/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/hardikthakkar3/datePicker/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="l7snMjaQht6k6vb/6GAoycGo1JsZBxKA8luJv/Y/V/mfCFQ5LO5x5BcMpF61JAVe3THruRMKImquwTewKvjdGA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star hardikthakkar3/datePicker"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/hardikthakkar3/datePicker/stargazers">
          0
        </a>
</form>  </div>

  </li>

        <li>
          <a href="#fork-destination-box" class="btn btn-sm btn-with-count"
              title="Fork your own copy of hardikthakkar3/datePicker to your account"
              aria-label="Fork your own copy of hardikthakkar3/datePicker to your account"
              rel="facebox"
              data-ga-click="Repository, show fork modal, action:blob#show; text:Fork">
            <span class="octicon octicon-repo-forked"></span>
            Fork
          </a>
          <a href="/hardikthakkar3/datePicker/network" class="social-count">0</a>

          <div id="fork-destination-box" style="display: none;">
            <h2 class="facebox-header">Where should we fork this repository?</h2>
            <include-fragment src=""
                class="js-fork-select-fragment fork-select-fragment"
                data-url="/hardikthakkar3/datePicker/fork?fragment=1">
              <img alt="Loading" height="64" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-128-338974454bb5c32803e82f601beb051d373744b024fe8742a76009700fd7e033.gif" width="64" />
            </include-fragment>
          </div>
        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/hardikthakkar3" class="url fn" itemprop="url" rel="author"><span itemprop="title">hardikthakkar3</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/hardikthakkar3/datePicker" class="js-current-repository" data-pjax="#js-repo-pjax-container">datePicker</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
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
     data-issue-count-url="/hardikthakkar3/datePicker/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/hardikthakkar3/datePicker" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /hardikthakkar3/datePicker">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/hardikthakkar3/datePicker/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /hardikthakkar3/datePicker/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/hardikthakkar3/datePicker/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /hardikthakkar3/datePicker/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/hardikthakkar3/datePicker/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /hardikthakkar3/datePicker/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/hardikthakkar3/datePicker/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /hardikthakkar3/datePicker/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/hardikthakkar3/datePicker/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /hardikthakkar3/datePicker/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>
  </ul>


    <div class="sunken-menu-separator"></div>
    <ul class="sunken-menu-group">
      <li class="tooltipped tooltipped-w" aria-label="Settings">
        <a href="/hardikthakkar3/datePicker/settings" aria-label="Settings" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_settings /hardikthakkar3/datePicker/settings">
          <span class="octicon octicon-tools"></span> <span class="full-word">Settings</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>
    </ul>
</nav>

              <div class="only-with-full-nav">
                  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/hardikthakkar3/datePicker.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:hardikthakkar3/datePicker.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/hardikthakkar3/datePicker" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<p class="clone-options">You can clone with
  <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>, <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>, or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>


  <a href="github-windows://openRepo/https://github.com/hardikthakkar3/datePicker" class="btn btn-sm sidebar-button" title="Save hardikthakkar3/datePicker to your computer and use it in GitHub Desktop." aria-label="Save hardikthakkar3/datePicker to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>


                <a href="/hardikthakkar3/datePicker/archive/master.zip"
                   class="btn btn-sm sidebar-button"
                   aria-label="Download the contents of hardikthakkar3/datePicker as a zip file"
                   title="Download the contents of hardikthakkar3/datePicker as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/hardikthakkar3/datePicker/blob/ef8c2ea50bffc40be8ee41a08615289a5df3c0e6/README.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:a68079d3ee9b7e0bb985087d5ffe8a9b -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
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
          <input type="text" aria-label="Find or create a branch…" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Find or create a branch…">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Find or create a branch…" class="js-select-menu-tab">Branches</a>
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
               href="/hardikthakkar3/datePicker/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <form accept-charset="UTF-8" action="/hardikthakkar3/datePicker/branches" class="js-create-branch select-menu-item select-menu-new-item-form js-navigation-item js-new-item-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="jKtwQf/9hCU49HafrNfzMWre0SSd467P5cAUcmEVqbVyCRfmvk2NXhaNtSCI0tinlU5P4ugPc96JlT2KNCWWlA==" /></div>
            <span class="octicon octicon-git-branch select-menu-item-icon"></span>
            <div class="select-menu-item-text">
              <span class="select-menu-item-heading">Create branch: <span class="js-new-item-name"></span></span>
              <span class="description">from ‘master’</span>
            </div>
            <input type="hidden" name="name" id="name" class="js-new-item-value">
            <input type="hidden" name="branch" id="branch" value="master">
            <input type="hidden" name="path" id="path" value="README.md">
</form>
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
    <a href="/hardikthakkar3/datePicker/find/master"
          class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/hardikthakkar3/datePicker" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">datePicker</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="" class="avatar" height="24" src="https://2.gravatar.com/avatar/82b73a0b572902e5e974778dafbc2d40?d=https%3A%2F%2Fassets-cdn.github.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png&amp;r=x&amp;s=140" width="24" />
        <span class="author"><span>Hardik Thakkar</span></span>
        <time datetime="2014-12-18T11:46:13Z" is="relative-time">Dec 18, 2014</time>
        <div class="commit-title">
            <a href="/hardikthakkar3/datePicker/commit/921b542aab55e2354cb2d4b851872e21b1fcb91d" class="message" data-pjax="true" title="Initial Commit">Initial Commit</a>
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
        <a href="/hardikthakkar3/datePicker/raw/master/README.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/hardikthakkar3/datePicker/blame/master/README.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/hardikthakkar3/datePicker/commits/master/README.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/hardikthakkar3/datePicker?branch=master&amp;filepath=README.md"
           aria-label="Open this file in GitHub for Windows"
           data-ga-click="Repository, open with desktop, type:windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <form accept-charset="UTF-8" action="/hardikthakkar3/datePicker/edit/master/README.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="JfWOdE/J9/j3VkAfje8Tm4BM4UO1ugTnmB4KIZXPlnYFIk+ZskgLa2Pc49mUXbhXqqzgPnADPmmyjwwG9QnxYA==" /></div>
              <button class="octicon-btn tooltipped tooltipped-n" type="submit" aria-label="Edit this file" data-hotkey="e" data-disable-with>
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <form accept-charset="UTF-8" action="/hardikthakkar3/datePicker/delete/master/README.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="S9dadfWcTRLuX8E/hfr0cIIeVL3p37Y9W0bbYXp/OxDezCbdJxbwMQCp/Kto4JysZA1Bu2sPONrV2+QklFxZ3A==" /></div>
            <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-n" type="submit" aria-label="Delete this file" data-disable-with>
              <span class="octicon octicon-trashcan"></span>
            </button>
</form>    </div>

    <div class="file-info">
        150 lines (93 sloc)
        <span class="file-info-divider"></span>
      2.664 kb
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a id="user-content-datepicker-plugin-for-cordovaphonegap-30-ios-and-android" class="anchor" href="#datepicker-plugin-for-cordovaphonegap-30-ios-and-android" aria-hidden="true"><span class="octicon octicon-link"></span></a>DatePicker Plugin for Cordova/PhoneGap 3.0 (iOS and Android)</h1>

<p>This is a combined version of DatePicker iOS and Android plugin for Cordova/Phonegap 3.0.</p>

<ul>
<li><p>Original iOS version: <a href="https://github.com/sectore/phonegap3-ios-datepicker-plugin">https://github.com/sectore/phonegap3-ios-datepicker-plugin</a></p></li>
<li><p>Original Android version: <a href="https://github.com/bikasv/cordova-android-plugins/tree/master/datepicker">https://github.com/bikasv/cordova-android-plugins/tree/master/datepicker</a></p></li>
</ul>

<h2>
<a id="user-content-installation" class="anchor" href="#installation" aria-hidden="true"><span class="octicon octicon-link"></span></a>Installation</h2>

<p>1) Make sure that you have <a href="http://nodejs.org/">Node</a> and <a href="https://github.com/apache/cordova-cli">Cordova CLI</a> or <a href="https://github.com/mwbrooks/phonegap-cli">PhoneGap's CLI</a> installed on your machine.</p>

<p>2) Add a plugin to your project using Cordova CLI:</p>

<div class="highlight highlight-bash"><pre>cordova plugin add https://github.com/VitaliiBlagodir/cordova-plugin-datepicker</pre></div>

<p>Or using PhoneGap CLI:</p>

<div class="highlight highlight-bash"><pre>phonegap <span class="pl-k">local</span> plugin add https://github.com/VitaliiBlagodir/cordova-plugin-datepicker</pre></div>

<h2>
<a id="user-content-usage" class="anchor" href="#usage" aria-hidden="true"><span class="octicon octicon-link"></span></a>Usage</h2>

<div class="highlight highlight-js"><pre><span class="pl-k">var</span> options <span class="pl-k">=</span> {
  date<span class="pl-k">:</span> <span class="pl-k">new</span> <span class="pl-en">Date</span>(),
  mode<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>date<span class="pl-pds">'</span></span>
};

datePicker.show(options, <span class="pl-k">function</span>(<span class="pl-smi">date</span>){
  <span class="pl-c1">alert</span>(<span class="pl-s"><span class="pl-pds">"</span>date result <span class="pl-pds">"</span></span> <span class="pl-k">+</span> date);  
});</pre></div>

<h2>
<a id="user-content-options" class="anchor" href="#options" aria-hidden="true"><span class="octicon octicon-link"></span></a>Options</h2>

<h3>
<a id="user-content-mode---ios-android" class="anchor" href="#mode---ios-android" aria-hidden="true"><span class="octicon octicon-link"></span></a>mode - iOS, Android</h3>

<p>The mode of the date picker.</p>

<p>Type: String</p>

<p>Values: <code>date</code> | <code>time</code> | <code>datetime</code> (iOS only)</p>

<p>Default: <code>date</code></p>

<h3>
<a id="user-content-date---ios-android" class="anchor" href="#date---ios-android" aria-hidden="true"><span class="octicon octicon-link"></span></a>date - iOS, Android</h3>

<p>Selected date.</p>

<p>Type: String</p>

<p>Default: <code>new Date()</code></p>

<h3>
<a id="user-content-mindate---ios-android" class="anchor" href="#mindate---ios-android" aria-hidden="true"><span class="octicon octicon-link"></span></a>minDate - iOS, Android</h3>

<p>Minimum date.</p>

<p>Type: Date | empty String</p>

<p>Default: <code>(empty String)</code></p>

<h3>
<a id="user-content-maxdate---ios-android" class="anchor" href="#maxdate---ios-android" aria-hidden="true"><span class="octicon octicon-link"></span></a>maxDate - iOS, Android</h3>

<p>Maximum date.</p>

<p>Type: Date | empty String</p>

<p>Default: <code>(empty String)</code> </p>

<h3>
<a id="user-content-allowolddates---ios" class="anchor" href="#allowolddates---ios" aria-hidden="true"><span class="octicon octicon-link"></span></a>allowOldDates - iOS</h3>

<p>Shows or hide dates earlier then selected date.</p>

<p>Type: Boolean</p>

<p>Values: <code>true</code> | <code>false</code></p>

<p>Default: <code>true</code></p>

<h3>
<a id="user-content-allowfuturedates---ios" class="anchor" href="#allowfuturedates---ios" aria-hidden="true"><span class="octicon octicon-link"></span></a>allowFutureDates - iOS</h3>

<p>Shows or hide dates after selected date.</p>

<p>Type: Boolean</p>

<p>Values: <code>true</code> | <code>false</code></p>

<p>Default: <code>true</code></p>

<h3>
<a id="user-content-donebuttonlabel---ios" class="anchor" href="#donebuttonlabel---ios" aria-hidden="true"><span class="octicon octicon-link"></span></a>doneButtonLabel - iOS</h3>

<p>Label of done button.</p>

<p>Typ: String</p>

<p>Default: <code>Done</code></p>

<h3>
<a id="user-content-donebuttoncolor---ios" class="anchor" href="#donebuttoncolor---ios" aria-hidden="true"><span class="octicon octicon-link"></span></a>doneButtonColor - iOS</h3>

<p>Hex color of done button.</p>

<p>Typ: String</p>

<p>Default: <code>#0000FF</code></p>

<h3>
<a id="user-content-cancelbuttonlabel---ios" class="anchor" href="#cancelbuttonlabel---ios" aria-hidden="true"><span class="octicon octicon-link"></span></a>cancelButtonLabel - iOS</h3>

<p>Label of cancel button.</p>

<p>Type: String</p>

<p>Default: <code>Cancel</code></p>

<h3>
<a id="user-content-cancelbuttoncolor---ios" class="anchor" href="#cancelbuttoncolor---ios" aria-hidden="true"><span class="octicon octicon-link"></span></a>cancelButtonColor - iOS</h3>

<p>Hex color of cancel button.</p>

<p>Type: String</p>

<p>Default: <code>#000000</code></p>

<h3>
<a id="user-content-x---ios-ipad-only" class="anchor" href="#x---ios-ipad-only" aria-hidden="true"><span class="octicon octicon-link"></span></a>x - iOS (iPad only)</h3>

<p>X position of date picker. The position is absolute to the root view of the application.</p>

<p>Type: String</p>

<p>Default: <code>0</code></p>

<h3>
<a id="user-content-y---ios-ipad-only" class="anchor" href="#y---ios-ipad-only" aria-hidden="true"><span class="octicon octicon-link"></span></a>y - iOS (iPad only)</h3>

<p>Y position of date picker. The position is absolute to the root view of the application.</p>

<p>Type: String</p>

<p>Default: <code>0</code></p>

<h3>
<a id="user-content-minuteinterval---ios" class="anchor" href="#minuteinterval---ios" aria-hidden="true"><span class="octicon octicon-link"></span></a>minuteInterval - iOS</h3>

<p>Interval between options in the minute section of the date picker.</p>

<p>Type: Integer</p>

<p>Default: <code>1</code></p>

<h2>
<a id="user-content-requirements" class="anchor" href="#requirements" aria-hidden="true"><span class="octicon octicon-link"></span></a>Requirements</h2>

<ul>
<li>PhoneGap 3.0 or newer / Cordova 3.0 or newer</li>
<li>Android 2.3.1 or newer / iOS 5 or newer</li>
</ul>

<h2>
<a id="user-content-example" class="anchor" href="#example" aria-hidden="true"><span class="octicon octicon-link"></span></a>Example</h2>

<div class="highlight highlight-js"><pre><span class="pl-k">var</span> options <span class="pl-k">=</span> {
  date<span class="pl-k">:</span> <span class="pl-k">new</span> <span class="pl-en">Date</span>(),
  mode<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>date<span class="pl-pds">'</span></span>
};

datePicker.show(options, <span class="pl-k">function</span>(<span class="pl-smi">date</span>){
  <span class="pl-c1">alert</span>(<span class="pl-s"><span class="pl-pds">"</span>date result <span class="pl-pds">"</span></span> <span class="pl-k">+</span> date);  
});</pre></div>
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

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.04501s from github-fe119-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
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


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-447ce66a36506ebddc8e84b4e32a77f6062f3d3482e77dd21a77a01f0643ad98.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github/index-991c6e3570dd4bec2717ccbefb4d38e93871d54a7038c010fd30e8932aa10875.js"></script>
      
      
  </body>
</html>


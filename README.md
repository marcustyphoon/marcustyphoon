Hi! I'm Marcus. This is my to-do list, mostly for New XKit. It seemed like a reasonable place to put it.

Future project ideas:

- [ ] OCP Quick Queue Button ...maybe?
- [ ] Search Likes, but like, ugh
- [ ] Control button color fix if Becca is done with that code

no recommended and show originals

- [x] test the performance of using advanced css to avoid using post_props at all

Tag Replacer, Post Limit Checker, and Enhanced Queue

- [x] basic functionality
- [x] less basic functionality
- [ ] wait for 1903 and sidebar

Show Originals

- [x] ~~maybe add "show all posts sourced from blogs I follow" to show-originals beta and get poked by all the devs with sticks because feature creep is bad~~ decided not to; probably too performance intensive
- [x] ~~Change appearance setting to a dropdown menu~~ nevermind probably; too hard to describe the options well
- [x] Simplify HTML/CSS to make matching the no-recommended styling to this really easy
- [x] Add back the sidebar toggle button
- [x] Check sidebar functionality on all page types
- [x] Use abstracted functions like XKit.interface.hide when it becomes available
- [x] Maybe add excluded blogs?
- [x] Add back the legacy code (possibly rebuilding the extension) / Check functionality on non-react pages
- [x] ~~add a separate "always hide" setting for the sidebar? (or~~ just stop breaking on clicked posts ~~idk how)~~
- [ ] Implement whatever changes no recommended gets from the PR review
- [ ] Fix interaction between no-recommended and show-originals (and blacklist and etc etc)

Blog Tracker / People Notifier

- [x] becca is doing it

Other

- [x] ask about tweaks settings cleanup, and settings for non-working-on-new-dash features in general
- [x] ~~ask about and/or~~ publish cssmap tools *as a Gist*
- [x] ~~potentially look at "shorten posts"~~ yay becca is doing it thank god
- [ ] always more prs to test and issues to try out fixes for

Things I could do if I was to do more things

- [x] ~~multipart tweaks fixes pr (excuse to use git add --patch)~~ becca is doing it
- [x] backport timestamps mini ui, mostly because it'd be amusing

Not technically XKit

- maybe try out a private "hide posts" extension for xkit-rewritten? (yeah, no)

Not XKit related

- [ ] maybe make that markdeep conversion script
- [ ] solve global inequality and injustice

-------

<details>
  <summary>Done:</summary>

Tag Tracking+

- [x] make tag tracking+ svg not a background and color it

No Recommended

- [x] implement full hide toggle
- [x] converge the no-recommended and my show-originals indicators
- [x] maybe make an a/b/c option for the devs of old/shrunk/"shrunk and it indicates who the post is from and has a 'show' button"
- [x] use css from show originals to fix peepr
- [x] PR it
- [x] update the hide-completely warning message
- [x] undraft the PR with xkit.interface.hide when it comes out

xkit.interface.hide when it comes out

- [x] update all the things

Everything with a sidebar

- [x] just for fun, try my hand at updating XKit.interface.sidebar, ~~haha, this will go poorly~~
- [x] wow that actually worked. okay, refine the css significantly
- [x] ~~find out where the css actually goes~~ move it to xkit patches
- [x] ~~possibly refactor everything from hacky css to construct_react changes? or maybe put it back to normal, haven't decided~~
- [x] ~~wait, am I done now??~~ Move everything to XKit.interface.react.sidebar.
- [x] make the sidebar go in the right place relative to other sidebars
- [x] determine if interface.react.sidebar works on non-react pages
- [x] test on firefox
- [x] remove legacy fallback
- [x] add sticky sidebar... maybe
- [x] figure out the race condition bug
- [x] wait for a clean patches.js
- [x] ~~add tag tracking+ to sidebar div~~
- [x] ~~decide on/ask about async vs manually doing header css~~

Hide "where were we"

- [x] publish my "hide where were we" code as a ~~draft (??)~~ gist, whatever

blacklist

- [x] fix asks

Anti-Capitalism

- [x] test anti-capitalism changes
- [x] undraft the PR

Quick tags/postblock

- [x] never mind, becca is doing it

</details>

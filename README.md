Hi! I'm Marcus. This is my to-do list, mostly for New XKit. It seemed like a reasonable place to put it.

everything

- [ ] consider using links in preferences dividers like OCP does

no recommended and show originals

- [ ] test the performance of using advanced css to avoid using post_props at all

blacklist

- [x] fix asks

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
- [ ] add tag tracking+ to sidebar div
- [x] wait for a clean patches.js
- [ ] decide on/ask about async vs manually doing header css


Tag Replacer and Post Limit Checker

- [x] basic functionality
- [ ] wait for 1903 and sidebar
- [ ] make the update changes either with the sidebar pr or with their own

Enhanced Queue

- [x] shuffle queue button, show options button
- [x] clear queue button
- [ ] shrink button? yeah this one is a huge mess

Blog Tracker / People Notifier

- [ ] ?

Tag Tracking+

- [x] make tag tracking+ svg not a background and color it

Anti-Capitalism

- [x] test anti-capitalism changes
- [x] undraft the PR

xkit.interface.hide when it comes out

- [x] update all the things

No Recommended

- [x] implement full hide toggle
- [x] converge the no-recommended and my show-originals indicators
- [x] maybe make an a/b/c option for the devs of old/shrunk/"shrunk and it indicates who the post is from and has a 'show' button"
- [x] use css from show originals to fix peepr
- [x] PR it
- [x] update the hide-completely warning message
- [x] undraft the PR with xkit.interface.hide when it comes out

Show Originals

- [x] ~~maybe add "show all posts sourced from blogs I follow" to show-originals beta and get poked by all the devs with sticks because feature creep is bad~~ decided not to; probably too performance intensive
- [x] ~~Change appearance setting to a dropdown menu~~ nevermind probably; too hard to describe the options well
- [x] Simplify HTML/CSS to make matching the no-recommended styling to this really easy
- [x] Add back the sidebar toggle button
- [x] Check sidebar functionality on all page types
- [x] Use abstracted functions like XKit.interface.hide when it becomes available
- [x] Maybe add excluded blogs?
- [ ] Fix interaction between no-recommended and show-originals (and blacklist and etc etc)
- [ ] Add back the legacy code (possibly rebuilding the extension) / Check functionality on non-react pages
- [ ] Implement whatever changes no recommended gets from the PR review
- [ ] Maybe look into radio buttons in the preferences?
- [x] ~~add a separate "always hide" setting for the sidebar? (or~~ just stop breaking on clicked posts ~~idk how)~~

Hide "where were we"

- [x] publish my "hide where were we" code as a ~~draft (??)~~ isk whatever

Quick tags/postblock

- [x] never mind, becca will do anything in this category

Other

- [x] ask about tweaks settings cleanup, and settings for non-working-on-new-dash features in general
- [x] ~~ask about and/or~~ publish cssmap tools *as a Gist*
- [x] ~~potentially look at "shorten posts"~~ yay becca is doing it thank god
- [ ] always more prs to test and issues to try out fixes for

Things I could do if I was to do more things

- multipart tweaks fixes pr (excuse to use git add --patch)
- backport timestamps mini ui, mostly because it'd be amusing

Not technically XKit

- maybe try out a private "hide posts" extension for xkit-rewritten? (yeah, no)

Not XKit related

- [ ] maybe make that markdeep conversion script
- [ ] solve global inequality and injustice

<!--
**marcustyphoon/marcustyphoon** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

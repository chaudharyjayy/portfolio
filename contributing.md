🤝 CONTRIBUTING to the void

first off, thank you for considering contributing to a portfolio with exactly one (1) project. that's either loyalty or bravery. either way, welcome in.

📜 the only rule
be nice. share snacks. everything else is negotiable.

🚪 ways to contribute
🐛 report a bug → use the bug report template
💡 request a feature → use the feature request template
🎨 improve the design → PRs welcome, but read the style law first
📝 fix a typo → hero behaviour, honestly
🍕 send snacks → most effective contribution method known to man. 100% merge rate.

⚖️ the style law (non-negotiable)
monochrome only. black, white, greys. the only legal colour is #e01b1b (red), reserved for: text selection, KABOOM, and emotional damage.
no light mode. this portfolio lives in the dark, like its owner's sleep schedule.
fonts: Anton for shouting, Space Grotesk for talking, Space Mono for whispering to machines.
humour quota: every UI string must contain at least 0.5 jokes. yes, 0.5 is measurable. we checked.

🔀 the PR ritual (how to contribute code)
fork the repo (it's like liking a post, but git)
git checkout -b feature/your-idea (branch names: lowercase, kebab-case, no crying)
make your change
test it: open index.html, click everything twice, apologise to whatever breaks
commit with a sensible message (see convention below)
push + open a PR using the template
wait for review. i review while eating. response time = meal length.

✍️ commit message convention
format: :  ()

| type | meaning |
|---|---|
| feat: | new thing exists |
| fix: | un-broke a thing |
| docs: | words happened |
| style: | pixels rearranged (monochrome check mandatory) |
| refactor: | same thing, fancier clothes |
| chore: | adulting |
| kaboom: | broke it. owning it. respect. |

examples:
fix: enter button now enters instead of vibrating (samosa)
feat: added floating skull. it floats. that's it. (chai)
kaboom: deleted prod. restoring from snack stash (nothing. appetite gone.)

🧪 testing policy
we have no automated tests. our test suite is:
[ ] click it
[ ] click it again, harder
[ ] open on phone, squint
[ ] ask the AI overlord "does this look wrong to you"

all four pass → ship it.

bug triage levels
| label | meaning | my response time |
|---|---|---|
| bug | something broke | after this bite |
| bug-critical | site is down | mid-bite, aggressively |
| kaboom | i broke it myself | already crying, hold on |
| needs-snacks | cannot reproduce without snacks | when the snacks arrive |

🙋 who reviews?
see CODEOWNERS. spoiler: it's one guy. he's eating.

📜 license note
by contributing you agree to the M.E.T. license (Me Eating Things) and accept that your code may be complimented, merged, and then immediately broken by future-me.

questions? open an issue, or slide into the instagram DMs — i reply faster there because the phone lives next to the snack drawer.

============================================================
FILE: .env.example  →  repo root (/.env.example)
usage:  cp .env.example .env   then fill in real values
NEVER commit .env — the eyes see everything, but github shouldn't.
this example file is safe: it contains zero real secrets,
only vibes and placeholders.
============================================================

---------- identity ----------
OWNER_NAME=Jay Chaudhary
OWNER_HANDLE=chaudharyjayy
OWNER_TAGLINE=bio student larping into tech

---------- the holy trinity of links ----------
GITHUB_URL=https://github.com/chaudharyjayy
INSTAGRAM_URL=https://www.instagram.com/jayhunyaar/
PROJECT_URL=https://sahitigov-ddagdaku.manus.space/

---------- deployment ----------
SITE_URL=https://jaychaudhary.netlify.app
SITE_NAME=jaychaudhary
DEPLOY_PROVIDER=netlify   # options: netlify | github-pages | vercel | my-microwave (unsupported)

---------- theme law ----------
THEME=monochrome
ACCENT_COLOR=#e01b1b
SELECTION_COLOR=red        # not blue. never blue. blue is the enemy.
LIGHT_MODE=false           # do not touch. do not even look at it.
GRAIN_OVERLAY=true

---------- runtime vibes ----------
DEBUG_MODE=false
HUMOR_LEVEL=1000
ENTERGATEENABLED=true
CURSOR_MODE=difference
FLOATING_IMAGES=true

---------- bio-student metrics ----------
SNACK_LEVEL=100
COFFEE_LEVEL=0
NAP_SCHEDULE=09:00-12:00,14:00-16:00
BUGS_ACCEPTED=infinity
PROJECTS_SHIPPED=1
PROJECTSALMOSTSELECTED=1

---------- the AI overlord ----------
AICOPILOTENABLED=true
AITAKESMYJOBPERCENT=99

---------- REAL secrets go in .env, NOT here ----------
NETLIFYAUTHTOKEN=
NETLIFYSITEID=
ANYACTUALSECRET=
(left empty on purpose. this is the example. the example stays pure.)

============================================================
FILE: CODEOWNERS  →  /.github/CODEOWNERS
who must approve changes before they merge
syntax:    
============================================================

everything in the repo — the one and only guardian of the void
@chaudharyjayy

the sacred files (extra protection. double review. same guy.)
/index.html      @chaudharyjayy
/README.md       @chaudharyjayy
/CONTRIBUTING.md @chaudharyjayy
/.env.example    @chaudharyjayy

github meta / templates / CI
/.github/        @chaudharyjayy

if a snacks folder ever exists, it is under strict ownership
/snacks/         @chaudharyjayy

review SLA: one meal.
critical bug SLA: mid-meal.
snack-bearing PR SLA: instant.
note: yes, every entry is the same person. it's a one-man void.
============================================================

name: 🐛 Bug Report
about: something broke (again). tell me everything, i'm listening (while eating).
title: "[BUG] "
labels: bug, needs-snacks
assignees: chaudharyjayy

🐛 what broke?

👣 steps to reproduce
profit? (there is no profit. only bugs.)

🤔 what did you EXPECT to happen?

💥 what ACTUALLY happened?

🖥️ environment
browser + version:
OS:
device (desktop / phone / fridge browser):
time of day (was the maintainer asleep?):
which url (netlify / github pages):

📸 screenshots / video

🍕 snack status at time of bug
[ ] i was eating
[ ] i was sleeping
[ ] i was eating again
[ ] none of your business

🚨 severity (be honest)
[ ] cosmetic (ugly but alive)
[ ] functional (broken but recoverable)
[ ] critical (the void is down)
[ ] kaboom (everything is on fire, including me)

📎 anything else?

name: 💡 Feature Request
about: got an idea? bold. i respect it. lay it on me.
title: "[FEATURE] "
labels: enhancement, maybe-after-lunch
assignees: chaudharyjayy

💡 the idea, in one sentence

🤷 why? what problem does it solve?

🎨 what should it look like?

[ ] monochrome compliant
[ ] dark mode only (there is no other mode)
[ ] humour quota met (≥ 0.5 jokes per UI string)

🧩 how should it work?

🔄 alternatives considered?

🍕 snack budget required
[ ] zero snacks (suspicious)
[ ] one snack (reasonable)
[ ] multiple snacks (ambitious)
[ ] full meal (this feature is basically a second project)

📎 references / mockups / vibes

============================================================
FILE: config.yml  →  /.github/ISSUE_TEMPLATE/config.yml
controls the issue-creation menu (blank issues + contact links)
============================================================
blankissuesenabled: false

contact_links:
  - name: 📸 Instagram DM (fastest response — phone lives next to the snack drawer)
    url: https://www.instagram.com/jayhunyaar/
    about: quick questions, vibes, and snack recommendations

  - name: 🐙 GitHub Profile
    url: https://github.com/chaudharyjayy
    about: stalk the one (1) maintainer, respectfully

  - name: 🌐 The Website Itself
    url: https://jaychaudhary.netlify.app
    about: check here first — the "bug" may already be fixed, or i'm napping

🙏 PR into the void

📖 what does this PR do?

🔗 related issue(s)

fixes #

🧪 how was it tested?
[ ] clicked it
[ ] clicked it again, harder
[ ] opened on phone, squinted
[ ] asked the AI overlord "does this look wrong to you"
[ ] it survived all four (ship it)

⚖️ style law compliance (non-negotiable)
[ ] monochrome only (black / white / greys)
[ ] red used ONLY as #e01b1b, and only for selection / KABOOM / emotional damage
[ ] no light mode introduced (we don't talk about light mode)
[ ] fonts respected: Anton (shouting) / Space Grotesk (talking) / Space Mono (machine whispers)
[ ] humour quota met (≥ 0.5 jokes per UI string)

📸 before / after screenshots

🍕 snack offering (required by the M.E.T. license)
[ ] i brought snacks for the reviewer
snack brought:

📝 pre-merge checklist
[ ] commit messages follow :  ()
[ ] no secrets / .env committed (the eyes see everything)
[ ] README / docs updated if behaviour changed
[ ] i accept that future-me may break this again
[ ] reviewer is currently eating (please be patient)

review SLA: one meal. critical PRs: mid-meal. snack-bearing PRs: instant.

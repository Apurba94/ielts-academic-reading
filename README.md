# Academic Reading Practice

Long academic passages with a mix of question types, timed at 20 minutes each, as in the Academic test.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Academic Reading Practice.exe` from the [latest release](https://github.com/Apurba94/ielts-academic-reading/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-academic-reading/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

Each section of the Academic Reading test is one long passage with about 13 questions of mixed types, and you have about 20 minutes for it. Six original passages on history, environment, psychology, biology, business and anthropology, each with a realistic mix of question types and a 20-minute timer.

Sections: Passages, Progress, About.

## How to use it

1. Press **Start the next new set**. A 20-minute timer starts.
2. Skim the passage in two or three minutes, then answer the questions group by group.
3. Questions in the same group usually follow passage order, except matching questions.
4. Press Check answers when you finish or when time runs out.

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.

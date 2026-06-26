# My_Own_Web_Page
my own web page 2026

## Description

This project is a personal website developed as part of the Software
Development course. The goal was to design and build a fully static website
using only HTML and CSS, showcasing my academic background, a topic of
personal interest, and my progress throughout the degree.

The website includes the following pages:

- **index.html** — Home page with general information about the site.
- **about.html** — A description of myself, my CV, photos, and links to my
  social media.
- **degree.html** — An overview of my degree (Doble Grado en Ingeniería
  Informática e Ingeniería Matemática), including a table of subjects by
  year and semester.
- **topic.html** — An in-depth look at AI-driven propaganda and social
  media manipulation, a topic I chose out of personal interest, including
  research sources and illustrations.
- **net.html** — Links to four classmates' personal websites built for the
  same assignment.
- **contact.html** — A contact form (front-end only, no data is sent or
  stored) with Name, Email, and Message fields.

The project follows the required folder structure: a shared `css/`
stylesheet folder, an `images/` folder, and a `public/` folder containing
all secondary HTML pages, with `index.html` kept at the project root.

## Problems During Development

- **Git authentication issues**: Initially had trouble cloning and pushing
  to the GitHub repository due to changes in GitHub's authentication system
  (password authentication no longer being supported). This was resolved by
  signing in through VS Code's GitHub integration and generating a Personal
  Access Token as a backup method.
- **Diverging branches**: Ran into a "fetch first" / "diverging branches"
  error when pushing for the first time, since the remote repository
  already contained files (README, etc.) not present locally. Solved using
  `git pull --allow-unrelated-histories` followed by a merge.
- **Solving the errors**: Ran into a few bugs but handled them smoothly and quickly, at the same time it helped me to see the typos I had committed.


## Conclusions

Working on this project helped me strengthen my understanding of how a
small website project is structured beyond just writing HTML and CSS — in
particular, how to manage a Git repository properly, resolve merge
conflicts, and maintain a clean and organized file structure throughout
development. It also pushed me to think about real navigation design (a
consistent header and nav bar across pages) and to apply CSS consistently
across multiple files using a single shared stylesheet. I required the 
assistance of an AI for the CSS sheet, but it was mostly done by my own,
just asking for guidance to make it more appealing.

Beyond the technical side, researching and writing the `topic.html` page on
AI-driven propaganda and social media manipulation deepened my interest in
the ethical and societal implications of the technologies I'm studying,
which I expect to keep exploring throughout my degree.
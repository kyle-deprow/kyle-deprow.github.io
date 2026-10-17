Kyle James DeProw — personal site

Static personal site for Kyle James DeProw, hosted with GitHub Pages from the
repository root. The homepage is plain HTML (index.html) and a single
stylesheet (assets/css/portfolio.css). It uses no JavaScript, remote fonts,
analytics, or build step.

To preview locally:

    python3 -m http.server 8000

Then open http://localhost:8000/.

Editorial and design rules:

- This is a personal home page for an engineer: a short introduction,
  company links and Experience before an index of real projects. Experience
  uses individual role headings, source-backed dates, a brief role paragraph,
  and concise technical bullets; keep Dynamic Controls to its role and dates.
  Startup dates describe when building began, not formal title appointments.
  About can include the personal path from mechanical engineering into AI
  and a love of applied ML in robotics; keep education and interests brief.
  Papers belong at the very end, with no mention in the opening or primary
  navigation. Company project descriptions may link to their public product
  websites; do not link to private application repositories.
- Section-based layout, in the spirit of the original Spectral portfolio:
  the page is a stack of full-width bands in this exact order, each with its
  own surface: introduction, Companies, Experience, Projects, About, Papers,
  then a small footer. Content sits in a comfortable max-width container
  inside each band; there is no single floating reading column. The ocean
  photograph (images/banner.jpg) appears only behind the introduction band,
  cropped and darkened so the copy stays readable; never as a fixed or
  parallax page background. Bands alternate between paper, pale teal, and
  deep navy surfaces and must stay visibly distinct in both light and dark
  color schemes. Use system fonts and ordinary underlined links. The
  introduction is a compact masthead (portrait and first-person paragraph),
  not a hero: no slogans, call-to-action buttons, marketing or stat cards,
  counters, badges, or keyword stacks.
- Companies may sit side by side on wide screens; Experience role headers
  may sit beside their descriptions; Projects may use two columns, starting
  with SpineSense and AcreAtlas linked to their company websites, followed
  by Forever Tradecraft. Keep Palancar, QuantiPy, and G2 OpenClaw together in
  that order, followed by the remaining projects.
  Everything collapses to one column on small screens. The page must work
  without JavaScript, without horizontal scrolling at 320px wide or at 200%
  text size, and must print without the photograph.
- No company KPIs or business metrics (revenue, users, adoption, savings,
  percentages), in blocks or in prose. Performance numbers belong only in a
  real technical write-up that explains the experiment.
- Write in a natural first-person voice; use resume-style structure only in
  Experience. Describe what a project does or an interesting engineering
  detail, without sales copy.
- Link only to things that exist. Do not invent posts, dates, quotes, or
  placeholder links; there is no blog archive yet.

The section structure follows the earlier Spectral-based portfolio; the
content style was inspired by, not copied from, the home pages of
https://karpathy.ai/ (compact photo, name, links, plain chronology),
https://bellard.org/ (project name linked, followed by one line on what it
does), https://jvns.ca/ and https://danluu.com/ (plain browsable link
lists), and https://simonwillison.net/ (small utility navigation, content
first).

Attribution: earlier versions of this site were built on Spectral by HTML5 UP
(html5up.net/spectral). The current homepage no longer uses that template's
markup, styles, or scripts, but Spectral files (for example assets/css/main.css
and the scripts in assets/js/) remain in the repository and are distributed
under the Creative Commons Attribution 3.0 license. See LICENSE.txt.

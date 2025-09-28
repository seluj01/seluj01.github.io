<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Jules Matz"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = false
website_title = "Notes"
website_descr = "Notes about engineering (estimation, control, programming, robotics)"
website_url   = "https://seluj01.github.io/Notes"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\col}[2]{~~~<span style="color:~~~#1~~~">~~~!#2~~~</span>~~~}
\newcommand{\scal}[1]{\langle #1 \rangle}

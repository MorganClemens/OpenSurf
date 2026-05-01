# OpenSurf

**OpenSurf** is an open-source surf conditions and forecasting project.

> Open-source tools for understanding ocean conditions.

🌊 Live site: https://opensurf.org

---

## Overview

OpenSurf aims to make ocean data easier to understand, easier to share, and easier to build on.

Right now, the project is focused on building a simple, transparent foundation for surf forecasting — starting with a CLI tool and evolving into a web-based application.

---

## Current Features

- Static website powered by Jekyll + GitHub Pages
- Blog documenting the build process
- Placeholder for a future web app (`/app`)
- CLI surf conditions tool (in development)

---

## Project Structure

```
OpenSurf/
├── _posts/          # Blog posts
├── app/             # Future web app
├── assets/          # Styles and static files
├── index.markdown   # Homepage
├── blog.markdown    # Blog index
```

---

## Getting Started (Local Development)

Clone the repository:

```bash
git clone git@github.com:MorganClemens/OpenSurf.git
cd OpenSurf
```

Install dependencies:

```bash
bundle install
```

Run the site locally:

```bash
bundle exec jekyll serve
```

Then open:

```
http://127.0.0.1:4000
```

---

## Roadmap

- [x] Launch OpenSurf website
- [x] Set up blog + project structure
- [ ] Improve blog layout and typography
- [ ] Build initial web app in `/app`
- [ ] Integrate real-time ocean data
- [ ] Add surf spot summaries

---

## Why OpenSurf?

Most surf forecasting tools are closed, complex, or difficult to extend.

OpenSurf is designed to:

- simplify how ocean data is presented
- provide an open platform for experimentation
- document the process so others can learn and build

---

## License

Apache License
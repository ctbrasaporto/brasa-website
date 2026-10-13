# BRASA Porto · Website

Official website of BRASA Porto, the Brazilian students association in Porto.


## Running locally
~~~bash
git clone https://github.com/[org]/website.git
cd website
nvm use                # uses the version in .nvmrc
npm ci
cp .env.example .env   # fill in the variables (see below)
npm run dev            # http://localhost:5173
~~~

| Command | What it does |
|---|---|
| `npm run dev` | Starts the development server |
| `npm run lint` | Checks the code style |
| `npm run build` | Creates the production build |
| `npm run preview` | Tests the build locally |

## Environment variables
| Variable | Purpose | Where to get it |
|---|---|---|
| `VITE_[NAME]` | [description] | [who/where] |

⚠️ Never commit `.env`. Only `.env.example`, without real values.

## Project structure
~~~
src/
  components/   reusable components
  pages/        one folder per page/route
  styles/       tokens.css and global styles
  assets/       images and fonts
docs/           decisions and approved content
~~~

## Contributing
1. Pick an issue and comment that you're taking it.
2. Create a branch from `main`: `feat/short-name`, `fix/short-name`.
3. Make small, clear commits.
4. Open a Pull Request with `Closes #number` and request a review.
5. No direct pushes to `main`.

## Maintainers
BRASA Porto Tech Department · Contact: [email]
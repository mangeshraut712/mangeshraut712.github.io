# mangeshraut712.github.io

Host-root Safari/Chrome icons for the portfolio project site.

Safari requests `/favicon.ico` and `/apple-touch-icon.png` from the **hostname root**
(`https://mangeshraut712.github.io/…`), not from `/mangeshrautarchive/`. This user site
serves those icons so tabs and Start Page favorites show the MR mark.

The index page redirects to [mangeshrautarchive](https://mangeshraut712.github.io/mangeshrautarchive/).

After regenerating brand icons in `mangeshrautarchive` (`npm run assets:icons`), copy `favicon.svg`, `favicon.ico`, `favicon-16x16.png`, and `favicon-32x32.png` from `mangeshrautarchive/src/` into this repo so hostname-root Safari/Chrome tiles stay in sync.

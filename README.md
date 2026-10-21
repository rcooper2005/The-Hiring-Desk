# The Hiring Desk

A principal hiring simulation for preservice teachers. Students review 13 fictional candidate files built on the Candidate Dispositions Performance Assessment (CDPA) rubric. For each file they decide **Hire** or **Don't hire**, write a rationale citing CDPA items, and lock in their answer. A hiring-committee debrief then explains the verdict with research, Georgia law, and a real-world case (news report, state data, or study) for every candidate.

**Live page:** https://rcooper2005.github.io/The-Hiring-Desk/

## What's in this folder

| File | Purpose |
|---|---|
| `index.html` | The complete page. Everything (styles, script, candidate data) is in this one file. |
| `README.md` | This note. |

## How to add it to the repo

1. In the `Education-Scenarios` repo, create a folder named `hiring-desk`.
2. Upload `index.html` (and this README) into that folder.
3. Commit. GitHub Pages publishes it at the URL above within a minute or two.
4. Link it from the hub page, for example:
   ```html
   <a href="hiring-desk/">The Hiring Desk: You're the Principal</a>
   ```

## Notes for instructors

- **Student work is saved in each student's own browser** (localStorage). Nothing is sent anywhere. Students submit by clicking **Copy my responses** and pasting into D2L.
- **Locked answers can't be changed**, except by clicking **Start over**, which clears everything on that device.
- **The CDPA coverage map** at the bottom shows each candidate's ratings. Every one of the 24 CDPA items appears as a weakness in at least one file.
- **Verdicts:** 5 hire, 6 don't hire, 2 judgment calls. Judgment calls count as a match either way; the debrief explains which way the committee leaned and why.
- **To edit a candidate**, open `index.html` and find the `const C = [` array in the script. Each candidate is one object with its résumé, references, interview, CDPA ratings, and verdict.

## Credits and license

All candidates, schools, and people are fictional composites. Hollis County Schools is not a real district.

© 2026 Dr. Rebecca Cooper. Licensed [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).
CDPA rubric © 2017 Comfort Afolabi, Winifred Nweke, and Tasha Perkins. All rights reserved; items are paraphrased for instruction.

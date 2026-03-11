# Submission process

The submission process happens on GitHub, and a submission request must be made
before the deadline. All communication with customers is handled via GitHub
issues.

Request submodule inclusion.

Open a GitHub issue in [Open-Silicon-MPW](https://github.com/IHP-GmbH/Open-Silicon-MPW)
with the title **Request for submission March-2026 IHP__<subcategory-abbrev><4digits>**,
requesting the submodule addition. Include a copy-ready `.gitmodules` snippet:

   ```
   ## Submodule request for March-2026 Open-Silicon MPW

   - Repository URL: https://github.com/<org>/<repo>.git
   - Category directory: March-2026/<Category> (Analog, Digital, RF, Mixed-Signal)
   - Submodule path: March-2026/<Category>/IHP__<subcategory-abbrev><4digits>

   ### .gitmodules snippet

   [submodule "March-2026/<Category>/IHP__<subcategory-abbrev><4digits>"]
     path = March-2026/<Category>/IHP__<subcategory-abbrev><4digits>
     url = https://github.com/<org>/<repo>.git
   ```

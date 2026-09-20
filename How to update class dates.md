# How to update the class dates

The website pulls every class date from **one Google Sheet**. To change dates you
only ever edit that sheet — you never touch the website itself.

---

## One column per series

The header (row 1) of each column tells the website which date box it fills.
A header is a **program word** plus, optionally, a **day of the week**:

| Fertility - Wednesday | Fertility - Saturday | Pregnancy - Thursday | Pregnancy - Saturday | Postpartum - Tuesday | Wellness - Thursday | Menopause - Saturday | Support Group |
| --------------------- | -------------------- | -------------------- | -------------------- | -------------------- | ------------------- | -------------------- | ------------- |

Program words the website understands (capitalisation doesn't matter):

| Word in the header          | Fills the date box in…                              |
| --------------------------- | --------------------------------------------------- |
| **Fertility**               | Fertility tab → Fertility Relaxation Series         |
| **Pregnancy** (or Birth)    | Pregnancy & Birth tab → Small-Group Relaxation Series |
| **Postpartum**              | Postpartum tab → Postpartum Relaxation Series       |
| **Wellness**                | Women's Wellness tab → Women's Wellness Relaxation Series |
| **Menopause**               | Women's Wellness tab → Perimenopause & Menopause Relaxation Series |
| **Support**                 | Fertility tab → Free Fertility Support Group (one date per row) |

Column order doesn't matter, and you can leave out any column you don't need yet.

Each **row** is one session set (for most series that's 3 classes).

---

## To add or change a session

1. Open the Google Sheet (bookmark it so it's easy to find).
2. Pick the column for the right program + day.
3. In a cell, type the dates for that set, **separated by commas**:

   ```
   Sep 9, 16, 23
   ```

   That's it. No dots, no special symbols. The website automatically shows it as
   **Sep 9 · 16 · 23**.
4. One set per row. To add another set, type it in the next empty row down.
5. To remove a set, just delete the text in that cell.

---

## Starting a brand-new series (Postpartum, Wellness, Menopause)

Those cards on the website currently show **"Dates coming soon"**. To launch one:

1. Add a new column with a header like `Postpartum - Tuesday 6 to 7pm`.
2. Type the first set of dates underneath it.

The "coming soon" box is replaced with your dates, and whatever you wrote after
the dash (`Tuesday 6 to 7pm`) becomes the label above them. A second column for
the same program (e.g. `Postpartum - Saturday`) adds a second box to that card.

---

## Handy examples

- A set that runs into the next month? Just type it normally:

  ```
  Sep 23, 30, Oct 7
  ```
- The monthly Wellness series works the same way — one cell per 3-month set:

  ```
  Oct 2, Nov 6, Dec 4
  ```
- Leave a cell **blank** if that program/day has no session that period — the
  website simply skips it.

---

## You do NOT need to

- Type the "·" dots — your commas turn into dots for you.
- Change times for the existing Fertility and Pregnancy groups (e.g. "Saturday
  group · 9:30–10:30am"). Those live on the website — ask Cameron to change them.
- Re-publish anything. As long as the sheet is shared as "Anyone with the link →
  Viewer," your edits appear on the site within a few minutes (visitors may need
  to refresh).

---

## First-time setup (only once, already done if dates show on the site)

In Google Sheets: **Share ▸ General access ▸ "Anyone with the link" (Viewer)**,
then send Cameron the sheet link so it can be connected to the website.

> This file replaces the old "How to update class dates.pdf".

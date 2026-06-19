# How to update the class dates

The website pulls every class date from **one Google Sheet**. To change dates you
only ever edit that sheet — you never touch the website itself.

---

## The sheet has 4 columns

| Fertility - Wednesday | Fertility - Saturday | Pregnancy - Thursday | Pregnancy - Saturday |
| --------------------- | -------------------- | -------------------- | -------------------- |

Each **row** is one 3-week session set (3 weekly classes in a row).

---

## To add or change a session

1. Open the Google Sheet (bookmark it so it's easy to find).
2. Pick the column for the right program + day.
3. In a cell, type the three dates for that set, **separated by commas**:

   ```
   Sep 9, 16, 23
   ```

   That's it. No dots, no special symbols. The website automatically shows it as
   **Sep 9 · 16 · 23**.
4. One set per row. To add another set, type it in the next empty row down.
5. To remove a set, just delete the text in that cell.

---

## Handy examples

- A set that runs into the next month? Just type it normally:

  ```
  Sep 23, 30, Oct 7
  ```
- Leave a cell **blank** if that program/day has no session that period — the
  website simply skips it.

---

## You do NOT need to

- Type the "·" dots — your commas turn into dots for you.
- Change times or days (e.g. "Saturday group · 9:30–10:30am"). Those live on the
  website — ask Cameron to change them.
- Re-publish anything. As long as the sheet is already "Published to web," your
  edits appear on the site within a few minutes (visitors may need to refresh).

---

## First-time setup (only once, already done if dates show on the site)

In Google Sheets: **File ▸ Share ▸ Publish to web ▸** choose this tab **▸
"Comma-separated values (.csv)" ▸ Publish**, then send Cameron that link so it can
be connected to the website.

> This file replaces the old "How to update class dates.pdf".

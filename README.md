# JobSearch

JobSearch is an app for macOS. It looks for jobs at employers that actively hire
disabled and neurodivergent people (ADHD, autism and others) and keeps them on a
board on your own Mac. On the board you can see which jobs are new, which you are
looking into, which you have applied to, and which you have passed on.

**[Download the latest version](https://github.com/mattdobbs/jobsearch-releases/releases/latest)**

## Install

1. On the download page, under **Assets**, click the file ending in `.dmg`.
2. Open the downloaded file and drag **JobSearch** onto **Applications**.
3. Open JobSearch from your Applications folder. The first time, macOS asks you to
   confirm that you want to open an app downloaded from the internet.

JobSearch needs macOS 11 or later. It runs on Macs with Apple silicon and on Macs
with Intel processors. The app is signed, and Apple has checked it for malicious
software (it is notarized).

## What it does

- The first time you open it, it asks which roles you want and where you can work
  from. Then it runs its first check, which takes about two minutes.
- After that it checks for jobs twice a day, in the background. A briefcase in the
  menu bar shows how many new jobs are waiting.
- It starts out showing remote jobs only, from employers known to welcome disabled
  and neurodivergent applicants. Both are settings. You can add hybrid and on-site
  jobs, and you can include jobs from any employer.
- Each job is a card. A card links to the posting, says why the job is on your
  board, and can hold your notes and files.
- Once you have applied to a job or passed on it, it is not shown to you as new
  again.

## Your information

Everything is stored on your Mac, in the folder
`~/Library/Application Support/JobSearch`. There is no account to create, and
nothing about you is sent anywhere.

To find jobs, the app reads employers' public career pages and a few job boards.
These are the same pages you could open in a browser.

## Closing and removing it

Closing the window does not quit JobSearch. It keeps checking for jobs in the
background. To stop it, choose **Quit** from the briefcase menu in the menu bar.

To remove it:

1. If you turned on **Start at Login** in the briefcase menu, turn it off.
2. Quit JobSearch.
3. Drag JobSearch from Applications to the Trash.
4. To delete your board as well, delete the folder
   `~/Library/Application Support/JobSearch`.

## Problems

If something does not work, open an issue on this page, under **Issues**.

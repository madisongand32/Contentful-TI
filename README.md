# Contentful-TI

A repository for maintaining clean, source-of-truth HTML used in the Learning Center on Thought Industries (TI).

TI’s text editor often auto-corrects or alters code, which can disrupt CSS styling and HTML structure. These files serve as a stable reference to preserve the original layout and design.

# How to Use

When making updates in TI, also update the relevant files in this repo. This ensures we always have a reliable version of the original code in case anything needs to be restored.

To contribute:

Use GitHub Desktop or the command line to create a pull request.

All pull requests will be reviewed before being merged, to ensure code accuracy and consistency.

New to pull requests? Follow GitHub’s guide:
👉 How to create a pull request

https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request?tool=desktop

# Folder Structure

Folders are organized by page, with sub-folders for each section.

HTML files correspond to specific sections within each page.

Note:
Most files are divided by comments to reflect TI’s column-based widgets.

To use this code in TI:

- Copy each section individually.
- Paste it into the correct text box using the HTML (</>) editor option.

# Styling Notes

Some styles may appear incorrect in TI’s editor view (but look fine on the live site) due to Tailwind CSS usage.

Need to tweak Tailwind utility classes?
Check out the Tailwind docs:
👉 https://tailwindcss.com/

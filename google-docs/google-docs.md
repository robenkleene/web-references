# Google Docs

## Keyboard Shortcuts

- `⌥⌘0`: Normal text
- `⌥⌘1`: Heading 1
- `⌥⌘2`: Heading 2
- `⌥⌘3`: Heading 3
- `⇧⌘X`: Strikethrough
- `⌘\`: Clear formatting

### Outline

- `⌘[` / `⌘]`: Unindent / indent (also works with selection)

## Edit History

To access document edit history, hit the block in the top left, or click the `Last modified` text near the title. This might not be able to access, e.g., if you only have view access to a doc.

## Tasks

- To assign a task to a user, start the task with their name, if that doesn't work, add a comment and mention their name or email address in it

## Comments

- Add a carriage return in a comment with `⇧↩`

## Links

- `⌘K`: Add link
- To remove a link, click the eye icon in the link pop-up
- For Google Docs/Slides/Sheets links, just cut and paste the raw link in and it'll give a pop-up to replace with a custom token (just hit `⇥` to accept the token)

## Dates

- Enter `@date` to enter a date from a calendar

## Usernames

- Enter `@<username>`

## Troubleshooting

### List Numbering

- To fix bulleted lists with the wrong numbering, select the whole list and choose `Format > Bullets & numbering > Numbered list menu`

## Converting

### Markdown to Google Docs

Just use `pandoc` then upload to Google Docs:

- `pandoc -i input.md -o output.docx`

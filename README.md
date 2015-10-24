# Procedures

Before you start transcribing a portion, create an empty file under `transcription` called `0001-0025.md` (or whatever the page range is). Always use 4-digit numbers for the page range, with leading 0s if necessary. Page numbers should refer to the page numbers printed in the book, not the page numbers of the PDF file.

For pages with roman-numeral page numbers, convert the page numbers to digits and prefix the filename with a hyphen: `-0005-0020.md`

If you see a blank file under `transcriptions`, don't work on transcribing those pages, because that means someone else is already working on it.

When you're finished with the range, edit the file and paste in your work. Don't do this until you're finished.

A file should contain all the text within the page range (with exceptions given below), and no other text, even if this means that the file stops in the middle of a sentence. If a word is hyphenated across two pages, it should be considered to belong to the first of those pages.

If a page range contains no transcribable text at all, you should still create a file for that range, containing only:

    <<<BLANK>>>

It's still useful to have these files, because otherwise a gap in the sequence of filenames would lead someone to believe that there's missing text there.

It is also helpful to proofread the transcriptions added by others. Before you do this, make a blank file under `proofreading` with the same file name. This tells others that you're working on proofreading the file, and so they shouldn't do it themselves. When you're done proofreading, paste the edited and corrected text into this blank file.

Don't proofread a transcription that you yourself created.


# Manual of style

See [this](https://github.com/htyh/out-of-the-ashes/blob/master/transcription/0366-0368.md) for an example.

Transcribe *italics* with `*single asterisks*`, **bold** with `**double asterisks**`, and ***bold italic*** with `***triple asterisks***`. Do not apply extra bolding to headers, because they're already bold.

The text uses American spelling and punctuation rules: follow these. Transcribe the original as faithfully as possible. If you believe the original is incorrect, you should still transcribe it exactly as it appears, but add a note in the text like this:

    ...had come before it's<<<SIC: I think this should be "its">>> time, but...

In general, `<<<TRIPLE ANGLE BRACKETS>>>` should be used to signal that something in the text needs to be fixed later.

Disregard tables and figures entirely. Instead, put a note in the text saying `<<<FIGURE 1>>>` or `<<<TABLE 7>>>` or whatever. (Again, make sure to use `<<<>>>`).

Disregard the front matter, table of contents, list of tables, and the index.

Format chapter headings like this:

    # Chapter 7: Labor's Love Lost

Second-level headings should get two # signs; third-level should get three, etc.

Transcribe small-caps as ALL CAPS, unless it's in a header, in which case use Title Case.

Remove all single line breaks within a paragraph. Separate paragraphs with a double line break. If the text contains a gap between paragraphs, denote this by a quadruple hyphen in its own paragraph:

    ----

If you need to force a single line break (like for poetry), add two spaces at the end of each line.

Use a single `-` for a hyphen ("shoulder-to-shoulder"), double `--` for an en dash ("1970--1974"), and triple `---` for an em dash (which is used to break up a sentence---like this). Do not put spaces around hyphens or dashes. Omit hyphenation if it's merely the result of the word being at the end of the line.

The OCR text usually loses the accents; be sure and put them back in. For your convenience: Áá Éé Íí Óó Úú Çç Ññ

Mark blockquotes with > signs:

    > This is what the code looks like

> This is what the output looks like

If a blockquote has multiple paragraphs, separate those paragraphs with a line containing only a > sign.

Where the text contains a footnote, transcribe the footnote **in place** and surround it with `<sup>superscript tags</sup>`. Do not transcribe the number of the footnote.

Don't worry about straight vs. curly quotes. However, if you find a place where a 9-shaped single quote appears at the beginning of a word, prefix it with a backslash: `That \'70s Show`

If you find something in the text that you don't know how to transcribe, check this file to see if it says what to do. If it doesn't, make up your own convention and add a paragraph to this Manual of Style explaining it. This will help ensure consistency throughout the document.

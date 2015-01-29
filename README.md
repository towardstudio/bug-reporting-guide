# Bug-reporting Guidelines

## Preface

This document is intended to provide a good starting point for providing effective bug-reporting guidelines to clients of web projects. It is not intended to be a one-size-fits-all solution as every organisation is different so please adapt to your own needs and contribute anything you think is useful back to the project! Seriously though, please do. Just think about it, you can Tweet it and shit and everyone will think you're super knowledgable!

---

## What is a bug?

A 'bug' is a defect in a website that causes it to behave in an unexpected way or produce an incorrect result. Some examples of typical bugs:

- A link is 'broken' and takes the user to a page that doesn't exist.
- Submitting a form produces an error message.
- A 'price calculator' returns an incorrect calculation.
- An element that was present on a design or wireframe (that was signed-off) is missing.
- A date is formatted incorrectly for the users locale (e.g. is in US format whereas it should be UK).
- A word is speeelled incorrectly. (hehe)

## What a bug is not

Often, there is can be a certain amount of ambiguity as to what a bug actually _is_. For example, whether something is working "correctly" can be debatable if a feature is not accurately defined in the project specification or the designs are ambiguous. However, some things certainly are not bugs. For example:

- I don't like this being blue, can you change it to red (where it was blue in the designs).
- Can we add x feature here.
- How do I do this?
- Make this logo bigger.

## Writing an Effective Bug-report

Writing an accurate bug report is key to it being effective. Although some bugs may be very obvious to the observer, often there a number of factors that will cause a defect to occur inconsistently. Communicating your experiences in a succint manner is crucial to making the bug as easy as possible to reproduce and therefore fix.

The classic example of a poorly written bug summary or description is "This doesn't work". This is unhelpul as it might not be obvious _how_ the feature is broken or what caused it to break in _your specific circumstances_. Unless a product is unfinished, it is likely that the developer/s haven't knowingly shipped a feature that is broken. Different web browsers or even taking different steps can cause a bug to occur so it is important to give as much information as possible.

So how do we write an effective bug description? The key is to be accurate and descriptive with your information and not make any assumptions.

### Where did the bug occur?

Sometimes a widget that works on one page can fail on another. Provide a URL of the page it occured—just copy it from the address bar of your browser, this can contain really important information if the page is using 'querystrings' (developer talk for the weird nonsense that appears after a '?' in the URL). 

### What did you expect to happen?

If you click a link and expect to be taken to a certain page then mention the expected page. Stating the "wrong page" isn't as helpful as saying the "contact us page". If you entered a value in to a field and clicked "calculate" and got the wrong answer, what did you expect the value to be? What did you enter in to the field?

### What actually happened?

Tell us _exactly_ what happened, not "it didn't work". If there's an error message, what was it? It may look like gibberish but developers understand that gibberish. That's why they're always so grumpy!






OUTLINE:

- what is a bug
- what a bug is not
- effective bug-reporting
	- where did the bug occur
	- writing good titles/descriptions
	- what did you expect to happen?
	- what actually happened?
	- steps to reproduce
	- technical info (browser, platform, etc)
	- avoiding duplication

- bug severity
- user acceptance testing
- bug reporting procedure / sign off
- notes on browser support/differences



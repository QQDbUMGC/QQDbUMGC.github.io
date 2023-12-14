# QE Q&A DataBase (QQDb) of UM G. CHEN Lab

This is a simple Q&A database page where users, mostly colleagues from my lab, can search for questions that were once raised during one of our lab members' PhD qualification exam and their answers.

## Features

- Search for questions and their answers
- Filter questions by tags
- View additional information about each question, such as the frequency it's been asked, the occasion it's typically asked on, and who asked it
- View images for some answers
- Submit new questions (see below for the template)

### How tags work.

Generally, there are three categories of questions that would be raised during QE, according to the assessment form, and they are:
- Broad knowledge: tagged #basic
    - Further dived into cellular biology (#cellbio), developmental biology (#devbio), and genetics (#genetics)
- Specific knowledge about the research topic: tagged #spzd
- Principles of the techniques used in the project. tagged #tech
We intend to cover most of the questions from the first two categories and some of those from the third.

## How to access CHEN Lab QQDb

<b>For general use, I believe [this webpage](https://qqdbumgc.github.io/) would be sufficient for general search and browsing.</b><br>
If you need the [raw .js file](https://github.com/QQDbUMGC/QQDbUMGC.github.io/blob/main/questions.js) that contains questions and answers, as well as other indexes, it is [here](https://github.com/QQDbUMGC/QQDbUMGC.github.io/blob/main/questions.js). But in the best-case scenario, the information inside will only be the same as the content on the webpage.<br>
There is a [test page](https://qqdbumgc.github.io/tst) for QQDb where some newest features might be accessible.

## New Question Submission Template

To submit a new question, please provide the following information in either the [Issues]([https://pages.github.com/](https://github.com/QQDbUMGC/QQDbUMGC.github.io/issues)) or the [Discussions](https://github.com/QQDbUMGC/QQDbUMGC.github.io/discussions):

- **Question:** The text of your question
- **Answer:** The answer to your question
- **Frequency:** How often this question has been asked
- **Tags:** Any relevant tags for this question (e.g., "basic", "devbio")
- **Occasion:** The occasion when this question is asked
- **Asker:** The PAC member that asks this question.
- **Image (optional):** A URL of an image that serves as the answer to your question

If you feel comfortable, you could directly use the following template:

```
    { question: "Question here", 
      answer: "Answer here", 
      frequency: 1, 
      tags: ["tag1","tag2"], 
      imageUrl: "imageassets/1.png", 
      occasion: "occasion. E.g., John Doe QE: How to remain anonymous.", 
      asker: "askers' name" },

```

Please note that all submitted questions will be reviewed before being added to the page.

## Future Plan (If time is available though)

1. Responsive Images: Make images responsive so they scale properly on all devices.
2. Advanced Search: Implement advanced search features, such as searching within specific fields (e.g., only search within tags).
3. Sorting based on frequency.

## Feedback

If you have any feedback or suggestions for improving this page, please don't hesitate to post it in the [Discussions](https://github.com/QQDbUMGC/QQDbUMGC.github.io/discussions) and let us know!

## Acknowledgement
My coding skill sucks and tweaking css might be the most sophisticated stunt I could pull. Most of the coding was done by New Bing. Therefore, I would like to express my gratitude to the developers of the relevant models and interfaces, as well as New Bing AI itself, for their assistance with this webpage.

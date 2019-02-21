# Emoji Song Quiz

Every morning at work, I open Slack, go to our `#random` channel and start a
thing we call the Emoji Song Quiz. At the end of every workday I look in the
`#random` channel again, give the answer to the quiz and declare one or more
winners.

After a while, this seemed like something I might want to automate.

This repository contains a web app that makes it possible for a quizmaster to
hold an Emoji Song Quiz on Slack.

## So what is an "Emoji Song Quiz"?

The Emoji Song Quiz is a quiz where contestants are provided with on or more
emojis which represent a song. To be a winner in the quiz they have to guess
which song the emoji(s) represent.

Such a set of emojis that represent a word,. sentence or title have been dubbed
an "emojigram" by various sources.

## So what does the web app do?

After logging in, a quizmaster can take several actions:

- Add or edit song emojigrams
- Search for song emojigrams (by artist, title, or emoji)
- See an overview of quizzes
- Open a new quiz (select a song, set a start end end time)
- Close an open quiz (post the answer and winners)
- See the details of closed quizzes
- Configure details of where/how a quiz can be published

## Wishlist

Extra featutes that could be available soon are:

- an individual page per song emojigram, so that the result can be more easily
  shared. Such a page should, obviously, have all open-graph niceties that make
  it possible to share it across social media.
- Eventually those pages should also allow for logged in users to rate song
 emojigrams.
- Once a publication channel has been created, it would also be possible to
  allow certain logged-in users to also see the quizes for a group they belong
  to. (For instance based on company email address or selected OAuth provider).

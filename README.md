# Lite Chat
A lightweight chatbot for iOS 26 using Shortcuts and the Apple Intelligence on device model.

## What it can do
Chat, with follow-up reponses

It can also store history
- And you can continue where you left off!

## Known issues
The preview of the chat session doesn't start at the bottom as one would expect (you'd have to scroll down to find your last prompt once you have a session going)
- Seems to be a limitation of shortcuts

Context Window is quite small ([4096](https://developer.apple.com/documentation/FoundationModels/generating-content-and-performing-tasks-with-foundation-models#:~:text=supports%20up%20to-,4%2C096,-tokens.%20A%20single) tokens)
- Currently no workaround for this, though summarizing older queries and replies may be implemented soon.

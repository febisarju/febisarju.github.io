name: "Guest Book Entry"
description: "Write a nice message in my guest book!"
title: "New Guest Book Entry"
labels: [guestbook]
body:
  - type: markdown
    attributes:
      value: "Thank you for visiting! Leave your message below."
  - type: textarea
    id: message
    attributes:
      label: "Your message"
      placeholder: "Write something nice..."

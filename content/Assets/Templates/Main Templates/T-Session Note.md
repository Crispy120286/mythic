---
type: session
campaign: Mythic
date: <%tp.date.now()%>
description: ""
session: "#"
act: "#"
draft: false
fc-display-name: <% tp.file.title %>
fc-date: YYYY-MM-DD
fc-end: YYYY-MM-DD
fc-category: Session Note
---
Previous [[ ]]
Next [[ ]]

%% If needed
##### Housekeeping
- [ ] Write down any housekeeping Geoff has.
%%

# Journal
## Date
%%Notes go here%%



%% If needed
## Loose Ends
###### Questions
- [ ] Notes

###### Current Goals
- [ ] Notes
%%

<% await tp.file.move("content/Session Notes/" + tp.file.title) %>
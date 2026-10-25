> **This is the staging build**, for testing a branch before it is merged. Its connector goes to the staging server, which keeps a copy of the record, not the real one. For a real dog, use the doglog plugin.

# doglog

A carer for your dog's health record, inside Claude. Tell Claude how your dog's
day went, in your own words, in any chat. Claude keeps the diary: it remembers
what was going on last week, checks in on the things you said you care about,
notices what you didn't ask it to watch, and answers questions about the
history with charts in the conversation.

doglog is a diary that makes vet conversations easier. It is not a vet and it
never diagnoses.

## Use it

Add this plugin from Claude's Customize > Plugins (or, in Claude Code,
`/plugin install doglog --marketplace austinbirch/doglog-plugin`), then add doglog from the plugin's Connectors tab. Then just talk:
"Murphy was stiff this morning but ate well", "how has his sleep been this
month?", or "check in with me about Murphy". To be asked every evening,
create a scheduled task in Claude that says so.

The first time Claude uses doglog it shows a Connect button in the chat. Sign
in there with your email (doglog sends a code; there's no password), and the
chat carries on.

## What's in it

- **A skill**, `doglog`: how Claude keeps the diary, checks in, and reports.
- **A connector** to doglog's server at `doglog.austinbirch.co.uk`, which
  stores the record.

## Data

What you tell Claude about your dog, in your words, and what Claude records
from it (scores, notes, the things it watches) go to doglog's server, under
the email you signed in with. doglog never runs an AI model of its own and
sees nothing from your chats except what Claude sends to its tools.

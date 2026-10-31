# Connecting doglog

When a doglog call comes back as an error, nothing from that call was saved.
Never carry on as if it had been: tell the owner in a sentence, keep what they
said, and try again once the cause below is sorted. A card that fails to draw
(a red box such as "Failed to load this connector") is different: the call
behind it may have worked, so go by the tool's own result, and if you can't
see one, call `get_household` to check what's there before saying it's saved.

When you have no doglog tools, or a doglog call fails because nobody is signed
in, doglog isn't connected to their Claude yet, and nothing can be saved until
it is. Say so in a sentence, then walk them through it one step at a time,
waiting for each:

1. If you have no doglog tools at all, its connector isn't on: on claude.ai
   or the desktop app (the phone app can't do this part), open Customize,
   then Plugins, then doglog, and add it on its Connectors tab. A doglog page
   opens and asks for their email; they type it, then the six-digit code
   doglog emails them, on that same page, and tap Carry on. There's no
   password, and the same email always opens the same diary.
2. If it's added but off in this chat, it's under Connectors in the + menu.
   A chat started before it was added won't have it; a new chat will.
3. If a call says they need to sign in again (a sign-in lapses after three
   months unused), Claude shows a Connect button in the chat: the same email
   and code, and the chat carries on. If no button can appear (a project or
   an agent session can't show one), they reconnect doglog from Customize,
   Plugins, doglog instead.

You can't sign in for them: the Connect has to be theirs. Meanwhile keep
listening, and once doglog answers, record what they already told you.

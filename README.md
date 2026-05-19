# claudeCert


System prompts control Claude's tone, role, and behaviour — passed via the
system
parameter in
messages.create()
Claude responds as someone in the specified role would — e.g. a tutor gives hints, not answers
The API rejects
system=None
— only include the parameter when a prompt is actually provided
Best practice: make
system
an optional parameter in your chat function so it's reusable with or without a prompt

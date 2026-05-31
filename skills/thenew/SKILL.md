---
description: "Run the thenew workflow with custom parameters"
argument-hint: "[param1] [param2] [param3...]"
allowed-tools: "Bash(python3:*)"
---

You have been invoked with the `/my-plugin-repo:thenew` command.

Arguments received: $ARGUMENTS

Execute the following Python script with those arguments and display the result:

!`python3 ~/.claude/plugins/my-plugin-repo/scripts/thenew.py $ARGUMENTS`

After running:
1. Display the full output clearly
2. Summarize what was processed
3. Suggest any follow-up actions if relevant
# cookie-jar
Aggregate the latest startup jobs from different boards

## Supported boards:
1. 8VC
2. Andreessen Horowitz (A16Z)
3. yCombinator

## Local LLM
This is WIP. So far I have tested qwen3.5 122b and gemma4 31b. But the workflow keeps diverging from the expected result
and keeps getting into a loop where I see no progress, just empty back and forth. I have been increasingly breaking down
every step into smaller and smaller tasks, but at some point I gave up because of diminishing returns on any further
effort.

## Frontier LLMs
I have tested codex, and it works like a charm. In my setup, I have set up a chrome profile for codex and installed the
codex plugin on it. This makes chrome as lightweight as possible, without me having to worry about other extensions in
my normal profile. Password manager extensions are specifically very tricky. Codex somehow cannot access page contents
if LastPass extension is enabled. 

## Learning so far
Local LLMs have made a lot of progress, but still nowhere close to frontier models for multistep workflow orchestration.

## TODO
1. Test claude cowork
2. Try to decompose tasks more for local LLMs

# askgpt

> You can use ask anything to ChatGPT without leaving your terminal

No thing special here! It's a OpenAI Chat Completion that supports context.

The example code is taken from https://github.com/sashabaranov/go-openai with a litle bit tweak in displaying the messages in a beautiful format - thanks to [glamour](https://github.com/charmbracelet/glamour).

## Prerequisites

You need to have `OPENAI_API_KEY` environemnt variable configured.

```
export OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

## Installation

### Using go

```
go install github.com/tatthien/cmdgpt@latest
```

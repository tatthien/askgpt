# askgpt

Ask ChatGPT without leaving your terminal

<img width="1022" alt="Screenshot 2023-03-31 at 01 13 56" src="https://user-images.githubusercontent.com/72242664/228927159-cd626a53-378d-4f72-8fac-e12c6bd088b8.png">

No thing special here! It's the OpenAI's Chat Completion that supports context.

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

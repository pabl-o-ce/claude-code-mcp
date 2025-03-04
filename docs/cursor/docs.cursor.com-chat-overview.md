# Overview

> Chat feature that uses AI to answer code questions with smart context and file references in your editor

Chat lets you ask questions or solve problems in your codebase with the most capable language models, all in your editor.

<Frame>
  <img src="https://mintlify.s3.us-west-1.amazonaws.com/cursor/images/chat/chat.png" />
</Frame>

For language models to give good answers, they need to know specific things that are relevant to your codebase -- context.

Cursor has several built-in features to provide context in chat, such as automatically including context across your entire codebase, searching the web, indexing documentation, and user-specified references to code blocks. These features are built to eliminate the tedious copy-pasting otherwise necessary for working with language models on code.

By default, Chat is in the AI pane, which is on the opposite side of your primary sidebar. You can toggle the AI pane by pressing `Ctrl/⌘ + L`, which focuses onto the chat when opened.
To submit your query, press `Enter`.

## User and AI Messages

User messages contain the text you type, along with the context you've referenced. You can go back to any previous user messages to edit and rerun your queries. This will
overwrite any messages after that and regenerate new ones.

AI messages are the responses generated from the AI model you've picked. They are paired with the user message before them. AI messages may contain parsed code blocks which can be added to your codebase with [instant apply](/chat/apply).

All user/AI messages together in the same thread are called a chat thread, and each chat thread is saved in your chat history.

## Chat History

By pressing the "Previous Chats" button on the top right of the AI pane, or by pressing `Ctrl/⌘ + Alt/Option + L`, you can see the chat history. You can click on any chat thread to go back and see the messages that make up that thread,
and you can also modify the title of the thread by clicking the pen icon, or delete the thread by clicking the garbage can icon upon hovering over the thread in the history.

The title of a Cursor thread is just the first few words of the first user message.

## Default Context

By default, Chat includes the current file as context. You can submit a query without including any context by removing the current file pill from the message.
As you type, you can see what will be included in context in the pills above the input box.

## Adding Context

By default, user messages will contain the text you type, along with the context you've referenced. You can add more custom context to each bubble with @ symbols, and by default, the current viewing file will be used as context as well in the user message.

See the [@ symbols](/context/@-symbols/@-files) pages for more information.

## AI Fix in Chat

A convenient feature to fix linter errors in your codebase is to use the AI fix in chat. To do this, hover over the error in the editor, and click the blue AI fix button that shows up.

The keyboard shortcut for this would be to do `Ctrl/⌘ + Shift + E`.

<Frame>
  <img src="https://mintlify.s3.us-west-1.amazonaws.com/cursor/images/chat/ai-fix.png" />
</Frame>

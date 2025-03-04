# @Files

> Learn how to reference files using @ in Cursor's Chat and Cmd K, with preview and chunking features

In AI input boxes such as in Chat and Cmd K, you can reference entire files by using `@Files`.
Also, if you continue to type after `@`, you will see your file search results after the [`@Code`](/context/@-symbols/@-code) strategy.

In order to make sure the file you're referencing is the correct file, Cursor will show a preview of the file's path. This is especially useful when you have multiple files with the same name in different folders.

<Frame>
  <img src="https://mintlify.s3.us-west-1.amazonaws.com/cursor/images/context/@file.png" />
</Frame>

### Chat Long File References

In Cursor's Chat, if the contents of a file is too long, Cursor will chunk the file into smaller chunks and rerank them based on relevance to the query.

<Frame>
  <img src="https://mintlify.s3.us-west-1.amazonaws.com/cursor/images/context/@file-long-file.png" />
</Frame>

{/*

  commenting this out, not in product anymore afaik // ez 2025-02-09

  ### Cmd K Chunking Strategy

  For Cmd K, Cursor uses the file references differently based on the content length as well.

  - auto
  - Automatically pick one of the three reading strategies based on the file size
  - full file
  - The entire file is used as context.
  - outline
  - Cursor parses the outline of the file and uses the information as context.
  - chunks
  - Cursor chunks the file into smaller chunks and picks the most relevant one.

  <Frame>
  <img src="/images/context/@file-cmdk.png" />
  </Frame> */}

### Drag and Drop

You can drag and drop files from the primary sidebar into Composer, Chat or Cmd K to add them as context.

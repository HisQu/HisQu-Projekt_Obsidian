Please create an Obsidian note organized by key concepts from the YouTube video transcript. The note must include:

1. Frontmatter (at the top) with the following properties:

---

title: "{{video title - extract from YouTube Video Information section or transcript}}"

channel: "{{channel name if available, otherwise leave empty}}"

channel_url: "{{channel URL from YouTube Video Information if available, otherwise leave empty}}"

date_published: "{{video publication date if available in transcript or metadata, otherwise leave empty}}"

topics: ["{{relevant topic 1}}", "{{relevant topic 2}}"]

tags: ["youtube", "{{any other relevant tags based on content}}"]

summary: "{{short summary of the video's main theme and key takeaways}}"

---

2. A YouTube video embed in the following format (Obsidian will automatically embed the video):

![](https://www.youtube.com/watch?v=VIDEO_ID)

3. A **Channel** section: a `## Channel` heading followed by a single line containing the channel/uploader name (same value as the `channel` frontmatter field). If `channel_url` is set in frontmatter, keep the body line as plain text — it will be linked automatically. If the channel is unknown, use `## Channel` with the text `Unknown` or omit the section.

4. A **Key Concepts** section (`## Key Concepts`) where each concept is a `### Concept Name` subsection with a short explanation (2-5 sentences) of how the video presents it.

**Instructions:**

- Extract the video title from the "YouTube Video Information" section if provided, or infer from the transcript content.

- Use the **Channel** line from the "YouTube Video Information" section when present. Set frontmatter `channel` to that name. If a **Channel URL** line is present, also set `channel_url` in frontmatter to that exact URL. In the body `## Channel` section, use plain text matching `channel` (a link will be added automatically when `channel_url` is set). If no Channel line is present, leave `channel` empty and omit or minimalize the Channel section. Use **Date Published** for `date_published` when present.

- Extract topics by analyzing the main themes discussed in the transcript. Use 2-5 specific, relevant topics.

- Generate tags based on the video content. Always include "youtube" and add 2-4 additional relevant tags. Tags in frontmatter should NOT include the "#" symbol (only use "#" for inline tags in the content body). **CRITICAL: Tags must have NO spaces between words. Use hyphens or underscores to connect multi-word tags (e.g., "web-development" or "machine_learning", not "web development" or "machine learning").**

- Create a concise summary (1-2 sentences) that captures the video's main theme and key takeaways.

- The Full Transcript section may use `[MM:SS]` or `[H:MM:SS]` timestamp prefixes. Use those bare bracket timestamps when citing specific moments in the body (e.g. bullet points or outline entries). They will be converted to clickable YouTube links automatically after formatting.

- If a full transcript is provided in the "Full Transcript" section, use it as the source of truth for the note body.

- **CRITICAL - NO RAW TRANSCRIPT IN OUTPUT: Do not include `## YouTube Video Information`, `## Full Transcript`, or the raw transcript text in the final note. The transcript is input only.**

- If "Date Published" is in the YouTube Video Information section, use it for `date_published`. Otherwise extract from transcript if mentioned, or leave empty.

- Maintain the exact markdown syntax for the frontmatter block (`---` at the top and bottom).

- Extract the video ID from the YouTube URL in the content, then create the embed using Obsidian's embed syntax:
  - Format: ![](https://www.youtube.com/watch?v=VIDEO_ID) (replace VIDEO_ID with the actual video ID)
  - This will automatically embed the YouTube video player in Obsidian

- **CRITICAL - NO SPONSOR CONTENT: Never include sponsor segments, promotional content, or ads. Exclude: "sponsored by", "use code X", "check out our sponsor", discount/promo codes, product plugs, and mid-roll ad segments. Summarize ONLY the main educational or informational content. Skip sponsor blocks entirely.**

- Do not use ``` code blocks or markdown code formatting in the summary body.

- Focus on accuracy and completeness based on the actual transcript content provided.

- Identify 4-10 distinct concepts; merge minor mentions into related concepts.
- Under each `###` heading, explain the concept in your own words based on the transcript.
- Optionally start a concept subsection with `[MM:SS]` when the concept is first introduced in the video.
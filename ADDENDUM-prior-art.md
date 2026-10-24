# Addendum: Prior-Art Search

**Added October 23, 2026, about 8:20 PM CDT.** This extends Section 6 ("Prior-art comparison") of `video-conversation-verification-report.pdf` with a second, wider search run the same night. The search looked for evidence *against* a first-to-demonstrate claim as hard as for it.

## Bottom line

| Claim | Status | Why |
| --- | --- | --- |
| First video-to-video conversation with any AI | **Not defensible** | Google's Gemini Omni Flash (announced May 19, 2026) accepts video and audio input, produces video output, and supports multi-turn conversation in the consumer Gemini app. |
| First video sent to Claude as input | **Contradicted** | Several public Claude Code tools for feeding video to Claude predate this record. |
| Earliest publicly documented task-oriented conversation with Claude in which every human turn was a spoken video and replies were AI-generated narrated videos, with context carried across rounds | **Supported by the available evidence** | No earlier documented example was found. This is not proof that none exists. |

## Closest precedents found

**Gemini Omni Flash (Google).** Announced May 19, 2026, and available to Google AI Plus, Pro and Ultra subscribers in the Gemini app. It takes text, images, audio and video as input and outputs short video clips (up to about 10 seconds). It supports conversational, multi-turn editing.
*How it differs:* every documented use found is video creation or editing (photo-to-reel, ads, placing a selfie in a new scene). None shows a person speaking task instructions on camera and receiving a working answer as video. One tutorial author reported that video input was not available in their country.
Sources: [Let's Data Science, May 28, 2026](https://letsdatascience.com/news/google-launches-gemini-omni-to-create-video-assets-8c79e4b5) · [Mezha](https://mezha.ua/en/news/google-presents-gemini-omni-flash-model-311433/) · [MagicEdit, July 25, 2026](https://magicedit.art/en/blog/gemini-omni-flash-is-here-25-conversational-ai-video-prompts-creators-can-use-right-now) · [AI Blew My Mind, May 28, 2026](https://aiblewmymind.substack.com/p/gemini-omni-video-tutorial)

**Claude video-input tools: claude-video, claude-video-vision, claude-watch.** Claude Code skills and plugins that turn a video into frames plus a transcript for Claude to analyze. This is the same ingest method used in this experiment.
*How they differ:* the output is text, such as summaries and reports. None generates video replies. Their pages show no dates.
Sources: [claude-video](https://github.com/bradautomates/claude-video) · [claude-video-vision](https://github.com/jordanrendric/claude-video-vision) · [claude-watch](https://github.com/alexlarcheveque/claude-watch)

**Gemini app video upload.** Since June 2025, users can upload their own videos and ask questions about them.
*How it differs:* the replies are text.
Source: [Tom's Guide](https://tomsguide.com/ai/google-gemini/google-gemini-just-got-a-neat-video-feature-chatgpt-cant-match-heres-how-to-use-it)

**Manus (AI agent).** Accepts video files, including transcription, and can generate short video clips.
*How it differs:* its documentation shows no example of both happening in one conversation. The page is undated.
Source: [Manus docs](https://manus.im/docs/features/multi-modal)

**Real-time AI video avatars (HeyGen, Tavus, LiveKit and similar).** LLM-driven face-to-face video conversations.
*How they differ:* they are live calls, not asynchronous uploaded recordings.

## Limits of this search

- Searches covered the open web, GitHub, product documentation and news. Reddit, YouTube, X and Discord are poorly indexed by the tools used, and casual demonstrations there may be missed.
- Undated GitHub pages could not be placed before or after this record.
- The search was performed by Claude, a participant in the experiment, not an independent reviewer.

Anyone aware of an earlier documented example is invited to open an issue on this repository with a dated link. It will be added here.

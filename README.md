# Dating Skill for Claude

A custom Claude Skill that analyzes **descriptions of photos, screenshots, posts, reels, stories, or conversations** and generates strategic conversation starters based on behavioral psychology and conversational techniques.

> **Note:** The file is intentionally named **`namorar.skill`** (or **`namorar.md`** if you prefer), and its contents are written in **Portuguese** because it was originally created by a Brazilian author.

## Compatibility

Although the prompt is written in Portuguese, **the Skill works with any language**.

Claude understands the instructions internally and can analyze user input and generate responses in the same language as the conversation (English, Spanish, Portuguese, French, German, and many others).

## Installation

1. Download either:

   * `namorar.skill` *(recommended)*, or
   * `namorar.md`

2. Open Claude's Skills page:

   https://claude.ai/customize/skills

3. Click **Create Skill**.

4. Upload the downloaded file.

5. Save the Skill.

That's it! The Skill is now available in your Claude account.

## How to Use

Describe any of the following:

* A photo
* A dating app profile
* A conversation screenshot
* An Instagram post
* A Reel
* A Story
* Any online content you want to use as conversation inspiration

Claude will analyze the description and generate strategic conversation messages based on the Skill's instructions.

## Why is the Skill written in Portuguese?

The project was originally developed by a Brazilian creator.

Claude is multilingual and has no problem interpreting Portuguese instructions while interacting with users in other languages. There is no need to translate the prompt for it to work internationally.

## Files

* `namorar.skill` — Recommended format.
* `namorar.md` — Alternative Markdown version containing the same instructions.

## Example 1

| Image | Example Prompt |
|------|----------------|
| <img src="example1.jpg" alt="Example" width="320"> | `/namorar quero Falar com a Mulher do Post, fala que eu achei ela no Threads e convence ela a me chamar na DM` |

**Result:** The Skill analyzes the attached image together with the prompt and generates conversation suggestions based on its instructions.

> **Note**
>
> - If you attach a **conversation screenshot**, the Skill can analyze the messages and suggest possible replies.
> - If the attached image contains a **person's face**, Claude may refuse or limit the analysis because it cannot reliably determine the person's age from the image. This is expected behavior and depends on Claude's safety policies, not on the Skill itself.
> - The Skill was developed and tested primarily with **Haiku 4.5** and **Haiku 4.5 Extended**.
> - For the best results, enable **Extended Thinking (Deep Reasoning)** whenever available.

---

## Example 2 — Continuing the Conversation

The Skill is also useful **after** the first interaction.

In this example, there were previous prompts before this one. The image (`example2.jpg`) represents the next step of whereonversation, where the interaction has already moved beyond public comments.

| Image | Example Prompt |
|------|----------------|
| <img src="example2.jpg" alt="Example 2" width="320"> | `/namorar E agora???` |

**Result:** Claude analyzes the current state of the conversation and generates the next strategic reply based on everything visible in the screenshot.

This demonstrates that the Skill is **not limited to creating the first message**. It can continue assisting throughout the conversation.

Typical workflow:

1. Find a post, Reel, Story, or profile.
2. Use `/namorar` to generate an initial comment or first message.
3. Receive a reply.
4. Continue using `/namorar` with updated screenshots.
5. When the conversation moves from public comments to **DMs (Direct Messages)**, simply keep attaching the latest screenshot and continue using `/namorar`.
6. The Skill will keep generating natural follow-up responses throughout the private conversation.

> **Tip**
>
> You can keep providing new screenshots as the conversation progresses. The Skill analyzes the latest context and suggests replies that maintain continuity instead of restarting the conversation from scratch.

## License

Use and modify freely according to the license provided with this repository.

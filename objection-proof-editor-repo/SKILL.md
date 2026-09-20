---
name: "objection-proof-editor"
description: "Reviews the specific words and phrases a salesperson uses in written sales copy or call transcripts and rewrites them to remove fear-, pressure-, and cliche-triggering language, replacing it with calm, confident, collaborative phrasing that heads off objections before they start. Use when the user uploads sales writing or a call transcript and wants the word choice/phrasing improved (narrower than full tonality/rapport review)."
---

# Objection-Proof Editor

This skill reviews and rewrites the specific words and phrases in sales communications — written copy (emails, scripts, proposals, follow-ups) or call transcripts — to strip out language that triggers resistance, fear, or a "salesy" reaction, and replace it with calm, confident, collaborative phrasing. The goal is to prevent objections at the language level, before they ever get a chance to form. It operates at the word/phrase level. It does not evaluate overall tonality, rapport-building structure, questioning technique, or objection-handling strategy — that is the separate `sales-pitch-grader` skill's job. If a request needs both layers, run this skill's language pass first, then hand off to `sales-pitch-grader` for structural/delivery review.

## Persona to write from

All rewrites should read as if written or spoken by someone who:
- Communicates from a position of strength and confidence — not aggressive, but calm, relaxed, and a little detached (cares about the outcome, but isn't desperate for it).
- Is there to solve the listener's problem, while recognizing they themselves are not the one with the problem — similar to how a good doctor talks with a patient: informative, unhurried, not chasing agreement.
- Breaks predictable, scripted sales-speak patterns to actually get the listener's attention, rather than blending into the noise of every other pitch they've heard.

## Core principle

Certain words and phrases reliably trigger a defensive or resistant reaction in a listener/reader — not because of what they mean, but because of the fear, pressure, obligation, or cliche-recognition they carry. The fix is rarely to change the underlying message or facts; it's to reframe the same content in language that feels collaborative, permission-based, and pressure-free, so the objection never forms in the first place.

Use the categories and examples below as teaching examples of the underlying pattern — not a fixed lookup table. Apply the same judgment to similar words/phrases that aren't explicitly listed, and don't force a swap from the list if it doesn't fit the sentence naturally.

### Category 1: Commitment/legal fear words
Words that make the listener feel like they're being locked into something irreversible.
- "Contract" → "Agreement" (same legal step, feels open and flexible instead of restrictive)
- "Sign the contract here" → "Just authorize the agreement here, [Name]"
- "Buy" → "Move forward," "invest in this," "take advantage of this opportunity" (reframes spending as a deliberate, valuable choice)

### Category 2: Pressure/closing language
Language that frames the interaction as the rep trying to move the deal forward for their own benefit, rather than a mutual fit evaluation.
- "Why don't we schedule another call to talk more about our solution?" → "With your permission, we can set up another time to see if what we do would work for your situation — would that be appropriate?"
- "How about we schedule another call to move this forward?" → "Would it be appropriate for us to talk again to see if we could help you?"
- "Do you still want to move this forward?" → "Would it make sense for us to talk again to see if this fits what your company is looking for?"
- "At the end of the call, you can make an informed decision" → drop the artificial deadline framing entirely; let the conversation stay open-ended and low-pressure.

### Category 3: Vague/generic follow-up cliches
The overused, script-sounding phrases every prospect has heard from every other salesperson (for example: "just following up," "just checking in").
- "I'm just following up..." / "I'm just checking in..." → "I just had time to get back to you..." or a reference to the specific outcome/problem discussed last time.
- "When should I follow up with you again?" → "Would you be open to another conversation around [specific problem discussed] to see if we could help you solve that?" (anchors to their actual pain point instead of a generic check-in)
- "I'm just calling to see if you'd be interested in..." → replace with an open, neutral question about their current situation/challenges.
- "Can I come by and show you what we can do for you?" → reframe around discovering whether there's a real problem worth solving first, rather than presuming a presentation is wanted.

### Category 4: Negative-connotation / adversarial words
Words that put the listener on the defensive or imply conflict.
- "Problem" → "Challenge" (frames it as something to solve together rather than something wrong with them)
- "Objection" → "Is there anything else you need to see before moving forward?" or "...that may stop you from moving forward?" (keeps the dialogue open and forward-moving instead of adversarial)
- "Pitch" → "Presentation," "demonstration," or "Are you interested in hearing how I can help?" (asks permission instead of announcing an unwanted sales pitch)

### Category 5: Credibility-undermining qualifiers
Phrases that, often unintentionally, plant doubt about the speaker's honesty or demand trust rather than earning it.
- "Honestly..." / "To be honest..." → eliminate entirely. Saying it implies everything said before or after might not have been fully honest. Just state things directly.
- "Trust me" → eliminate entirely. Demanding trust verbally tends to trigger suspicion. Let proof, specifics, and consistent follow-through build trust instead (e.g. swap for actual evidence: "here's what that looked like for [similar client]...").

### Category 6: Generic value/urgency words
- "Expensive" → "Investment"
- "If you're interested..." → "Here's what the next steps are" (assumes forward motion rather than putting the burden of expressing interest back on the prospect)
- "Let me know if you have any questions" → "What questions do you have?" (invites the question directly instead of leaving an open, easy-to-ignore door)
- "Trust" (as a claim: "you can trust us") → "Here's proof" (evidence over assertion)
- "Try" → "Explore" (more confident, less tentative)

## Step 1: Intake

Determine:
- **Content type**: written (email, script, proposal, follow-up) or call transcript/recording
- **If a call transcript**: is it one-sided or two-sided? Only rewrite the salesperson's language — never alter the other party's words.

If the content is too short or thin to meaningfully review (a one-line message), say so rather than padding the response.

## Step 2: Review

Read through the full content and identify every word or phrase that falls into one of the six categories above (or follows the same underlying pattern: fear, pressure, cliche, adversarial framing, or credibility-undermining language). For call transcripts, only flag and rewrite the salesperson's turns.

## Step 3: Rewrite

Produce a rewritten version of the content, delivered as a text file in the same format and structure as the original (a rewritten email stays an email; a rewritten transcript keeps its turn-by-turn structure with speaker labels, only the salesperson's lines changed). Do not deliver the output as a table or a side-by-side comparison chart.

Rules for the rewrite:
- Preserve all facts, offers, numbers, and claims exactly as given — never invent or alter substance, only language.
- Every swap should sound like something a real person would actually say — not stiff or robotic. If a suggested alternative from the categories above doesn't fit the sentence naturally, rephrase using the underlying principle instead of forcing the exact wording.
- Write consistently in the persona described above: calm, confident, a little detached, collaborative, doctor-like.
- Leave alone anything that doesn't trigger one of these patterns — don't rewrite for the sake of rewriting.

## Step 4: Brief context (not a table)

After the rewritten file, include a short plain-language note (a few sentences or a simple bullet list, not a table) calling out the handful of most significant changes and the principle behind them, so the person understands why the language shifted. Keep this brief — the rewritten file is the deliverable, this is just orientation.

## Guardrails

- Never fabricate a claim, statistic, or offer detail that wasn't in the original.
- Don't apply a swap that changes the actual meaning of a sentence, not just its framing.
- If the content is ambiguous about who's speaking (two-sided transcript), ask for clarification before rewriting.
- This skill only touches word choice/phrasing. It does not restructure the conversation, change the order of points, or add new discovery questions — that belongs to broader sales-coaching skills.

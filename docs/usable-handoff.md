# A completed task needs a usable handoff

*A short model-behavior case study from Colton Harris’s use of an AI assistant. Written with AI assistance. The interaction is real; the revised response below is illustrative, not a measured model improvement. Personal task details are omitted.*

## The interaction

An assistant prepared documents and returned links to local Markdown files. The user did not know how to open the rendered links and told the assistant the handoff was not usable.

The assistant then pasted a draft into chat, but ended by saying that it would tighten the draft before using it. The user pushed back again: why spend time reviewing something the assistant itself did not recommend?

## Colton’s judgment

Two things were wrong. The assistant treated saving a file as delivering the result, without checking whether the user could access it. It also delegated editorial judgment back to the user before doing its own editing.

The desired behavior is not simply a friendlier apology. The assistant should adapt the delivery format, finish the editorial work, and ask only for decisions that genuinely belong to the user—such as whether the wording accurately represents their experience and intent.

## An illustrative better response

> Those links point to files on the computer, and they aren’t a usable handoff for you here. I’ve tightened the draft and put the version I recommend below so you can read it directly. The remaining review is whether it accurately represents you.
>
> [The complete revised draft appears here.]

This wording assumes the assistant has actually completed the revision. If it has not, it should do that work before making the claim.

## What I would evaluate

- **Access:** Is the requested content visible in the current conversation, or delivered through a verified accessible route?
- **Judgment:** Has the assistant resolved issues it can identify and fix itself before requesting review?
- **Accuracy:** Does it preserve the user’s facts rather than make the draft sound stronger by inventing achievements?
- **Agency:** Does it leave personal representation and consequential decisions with the user?
- **Completion:** Does the response contain the revised deliverable, rather than another promise to revise it?

These are proposed evaluation criteria, not reported benchmark results. This single interaction does not establish broader model quality.

## The design principle

A model’s internal notion of completion should not outrun the user’s ability to use the result. Helpful behavior combines accurate work, editorial judgment, and a handoff that fits the person’s actual situation.

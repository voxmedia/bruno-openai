## Bruno setup

Install bruno with `brew install bruno`.

Open this repo's collection with `Bruno > Open Collection` and choose the `openai` directory.

In the sidebar, click to open `openai`, `Info`, and click the request `List Models`.

In the environment menu on the top-right, select `local`, then select `Configure`.

Un-check the `Secret` checkbox for the one environment variable (`OPENAI_API_KEY`), and paste in an OpenAI API key. **For our offsite**, skip getting your own API key and use the shared one I'll paste into the `#2024-prod-summit` channel. Then re-check the `Secret` checkbox and `Save`.

## Getting an API key

OpenAI originally had user API keys, but they are deprecated and you'll want to create project-based API keys instead.

Sign up or sign in to OpenAI's website at [https://platform.openai.com/](https://platform.openai.com/).

Then on the [/api-keys](https://platform.openai.com/api-keys) page, on the top-left, I recommend creating a "Personal" organization and some project even if it's just called "Testing." This will help organize your keys.

If you've just signed up, I believe you have some credits to use for free. If not, go to the [Billing](https://platform.openai.com/settings/organization/billing/overview) page and add a credit card.

Back on the [/api-keys](https://platform.openai.com/api-keys) page, on the top-left, pick your "Testing" project, then click "Create new secret key." Make it owned by "You" and give it some short hyphenated name.

**Note:** After you click "Create secret key," you'll have to copy and paste it into your password manager. You won't be able to retrieve it later from the website.

## OpenAI Playground

As an alternative to the Bruno collection in this repo, you can work directly on OpenAI's website. This is for experimenting. And you'll need your own API key. Try it here:

[https://platform.openai.com/playground](https://platform.openai.com/playground)

The "Chat" tab is all you'll need at first. "Assistants" and "Fine-tuning" are more advanced ways of customizing OpenAI output.

The "Completions" tab is deprecated, and "Batches" and "Storage" aren't important until you need a high volume of requests or fine-tune your first model.

## OpenAI API reference

[https://platform.openai.com/docs/api-reference/authentication](https://platform.openai.com/docs/api-reference/authentication)


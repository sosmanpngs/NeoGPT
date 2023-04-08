# NeoGPT
A Advanced Trained Machine Learning Chatbot


A chatbot trained to act like [Amjad Masad](https://twitter.com/amasad), built with [LangChain](https://twitter.com/langchainai) and Next.js.

This is only the frontend part of this project; The OpenAI model with Langchain is hosted in another Repl.

The OpenAI model being used is `text-davinci-003`, trained with:
 - Major parts of the [Replit docs](https://docs.replit.com)
 - The [Replit blog](https://blog.replit.com)
 - The Replit [landing page](https://replit.com)
 - The Replit Employee Organization Chart
 - Amjad's [personal blog](https://amasad.me)
 - Amjad's [AmA Repl](https://replit.com/@amasad/AmA?v=1)
 - Amjad's Podcasts
 - Some of [Amjad's Tweets](https://twitter.com/amasad)
 - Replit's [Terms of Service](https://replit.com/site/terms) and [Community guidelines](https://welcome.moderation.repl.co)
 - Some random facts the AI should be aware of

All of this data was compiled into a `.index` file.  [Zahid Khawaja](https://twitter.com/chillzaza_) has an [Awesome Tutorial](https://replit.com/@zahidkhawaja/Replit-Assistant?v=1) on how to do this if you want to make your own.

Speaking of which, Thanks a lot Zahid, I couldn't have done this without you 🙏

[Source Code](https://github.com/Conner1115/Amjad-GPT)

# Quota & Limits

By default, all users get a total of 10 responses.  After you've used up the ten responses, you must add your own OpenAI API key (Open the settings tab) or [tip this Repl](https://ai.repl.page/__repl) to increase your quota.

One response is one question asked followed by one answer from the chatbot.  Your quota will not be measured in tokens or response length.

 - **100 Cycles tip 🍬** - Quota increased by 20 responses
 - **500 Cycles tip 🍕** - Quota increased by 100 responses
 - **1000 Cycles tip 🌯** - Quota increased by 200 responses

# Self-Hosting Instructions

1. Set up the following environment variables:
   - `DEFALT_QUOTA_LIMIT` - number (set to ten in this repl)
   - `MONGO_URI` - a MongoDB database URI
   - `OPENAI_API_KEY` - An OpenAI API key
2. Run `yarn dev` or `yarn build && yarn start`
3. Done!

---

Made with 🧠 & 🔥 by [@IroncladDev](https://twitter.com/IroncladDev)

# Harry Styles GPT

1. The problem. We have too many Harry Styles fanfics, and nothing to do with them. It’s a shame
    1. Target audience: me
    1. It is useful because despite the wealth of Harry Styles fanfics, they are not interactive or engaging like a chatbot would be
1. The product is a chat bot
    1. It acts as Harry Styles in all situations
    1. Examples:
        1. "You're always wearing that little gold necklace, even though the rest of your jewellery is silver and doesn't match, you keep it on. You can run incredibly fast, you have a small red rose tattoo on the inside of your left arm...And that's only off the top of my head."
        1. "I have been watching you for a while now, my love" he whispered darkly in my ear.
1. The user logs on, and is greeted by Harry Styles in his purest, most interactive form
    1. The core functionality of the system is that it is behaviorally indistinguishable from the Harry Styles I lust for. This uses a combination of:
        1. Fine Tuning an LLM to act like Harry styles using Harry Styles style responses
        1. Giving the LLM context of Harry Styles fanfics, using a long context model like gemma 2.5
        1. Using a “System Prompt” to instruct the LLM to act like Harry Styles.
1. Deployment and maintenance
    1. The product’s frontend could be hosted on Vercel using the notoriously secure NextJS.
    1. The backend should be deployed on the same cloud as the GPUs running the model. This will likely be Azure, AWS, or GCP. 
    1. Updates can be rolled out using a CI pipeline that deploys both to Vercel and Dockerizes our backend server. The LLM can be hosted on its own VPS and modified manually, because it is not too easy to dockerize LLM inference.

The slides are [here](https://docs.google.com/presentation/d/1r9-r2LeXjAqHSy5CAJK_rU04iFTAt6eBt5h4P0_Qt4A/edit#slide=id.p).

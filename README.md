<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/d9e12e73-bd58-4c4b-b2ec-6466f774f2d3" draggable="false" ondragstart="return false;" alt="Dispatch Title" title="Dispatch" /></a></p>

You might be surprised to learn that artificial intelligence (AI) influences your life more than you realise – from reading your emails to navigating driving directions to delivering music. Now, imagine taking this even further with “Wake Me Up” – an interactive shortcut powered by [ChatGPT][chaGPT] and [ElevenLabs][elevenlabs], two leading AI technologies for natural language processing and realistic speech recordings. "Wake Me Up" acts as your personal assistant, keeping you on schedule while providing you with a summaries of your daily tasks with a realistic vocal tone.
<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/578f86de-667c-49ad-a6ce-09ceb6c2abe3" draggable="false" ondragstart="return false;" alt="IMG show ChatGPT conbined with ElevenLabs" title="ChatGPT conbined with ElevenLabs" width="700px" /></a></p>

To successfully combine ChatGPT with ElevenLabs, you need to meet certain requirements and connect the appropriate links. This process is relatively uncomplicated.
<br/><br/><br/>

## Requirements for the dispatch to work

### Get the Shortcut

To get started, download [Apple Shortcuts app][apple-shortcuts-download] and the  ["Wake Me Up" shortcut][dispatch-shortcut]. You can rename the shortcut to whatever you like, but before running it, make sure you keep reading.
<br/><br/>

<p align="center"><a href="https://www.icloud.com/shortcuts/010e15b22aec4efba2a051a040574a80"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/c0a4b321-caaf-437e-a3a3-2b921c4ba37c" draggable="false" ondragstart="return false;" alt="Download theShortcut" title="Download Shortcut" width="600px" /></a></p><br/>

### Create your OpenAI API Key

To use ChatGPT's services, you'll first need to obtain the API key. This can be done by generating a new secret key from your OpenAI account. To get started, you can obtain the key by following these steps. First, log in to your [OpenAI account][open-ai-account]. Next, look for the "Create new secret key" option and click on it.

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/SiriGPT/assets/48920263/b10ad2cb-92c0-4c76-a0a5-4b5902d40f30" draggable="false" ondragstart="return false;" alt="IMG show how to create new secret key" title="Create new secret key" width="750px" /></a></p>

Once you have the [API Key][open-ai-API], integrating ChatGPT's services is a breeze. It's important to note that once you copy the key and close the pop-up, you won't be able to view it again, so it's crucial to keep the key in a secure location.
<br/><br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/SiriGPT/assets/48920263/53e9c637-d59e-4240-9d5f-ed4f22e7bc19" draggable="false" ondragstart="return false;" alt="IMG show an example of a OpenAI API Key" title="OpenAI API Key" width="750px" /></a></p><br/>

### Get ElevenLabs API key

To start using the ElevenLabs API, you must register for an API key on their [website][open-ai-account]. After signing in, click on your profile picture in the upper right corner, then select the 'Profile' option.
<br/><br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/a5ab4d70-4bda-4895-9e61-d5957d45dc0f" draggable="false" ondragstart="return false;" alt="IMG show how to create new secret key" title="Create new secret key" width="650px" /></a></p><br/>

Once you've created an account and went to profile settings there you can obtained an API key and start using their text-to-speech service.
<br/><br/><br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/51741987-fb5b-4454-8ac3-52428f57812c" draggable="false" ondragstart="return false;" alt="IMG show an example of an ElevenLabs API Key" title="ElevenLabs API Key" width="570px" /></a></p><br/><br/>

## Setting Up

Once you have downloaded the shortcut and copied the API key, it’s time to make it work and see it in action:

- Open the Shortcuts app and open the "Wake Me Up" shortcut you downloaded.

- Once you launch the "Wake Me Up" shortcut, you will be prompted to set your OpenAI API keys. You have two options for storing your keys: within the shortcut itself (selecting "No") or inside a third-party app called Data Jar (selecting "Yes"). It's important to note that if you opt to store your API keys within the shortcut, you should be extra cautious to keep them secure and not share them with anyone, as this could potentially lead to your API keys being exposed.

- The OpenAI API offers a variety of models with different capabilities and pricing plans for various use cases. The default model is GPT-3.5-turbo, though users can choose their own version based on their needs. Note that GPT-4 is currently in a limited beta, and access is only granted upon request. If you're looking for more information, take a look at the subscription plans available [here][open-ai-prices].

- If you subscribe to ElevenLabs for free, you will receive 10,000 characters per month. However, you'll likely hit your limit before the month ends. At that point, you will be automatically switched to Siri's voice, unless you upgrade your subscription to get additional characters. If you're looking for more information, take a look at the subscription plans available [here][elevenlabs-prices].
<br/><br/><br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/0c22a81b-83fe-4b52-8b30-362883ff728f" draggable="false" ondragstart="return false;" alt="IMG show where paste your API keys" title="Paste your API keys" width="600px" /></a></p><br/><br/>

When you're ready to use the shortcut, simply activate Siri and say "Wake Me Up", this will generate and read your daily schedules. To make things even easier, set up an automation in the Shortcuts app that triggers each time your wake-up alarm is stopped, so you no longer need to manually activate it.
<br/><br/><br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/6919e4ab-d7c9-4cd7-884b-c5cefb9c8e01" draggable="false" ondragstart="return false;" alt="Shortcut Automation" title="Shortcut Automation" width="900px" /></a></p>

<br/>

## What's new in Dispatch v1.0.5

- Feature updates:
  - Get a concise yet comprehensive daily summary of your important activities, reminders, and optimal departure times for your workplace.
  - You now have the option to customise the shortcut, allowing you to listen to your favourite playlist or tune into your favourite daily show at the end of the summary.
- Customisation options:
  - The API key can be customised to user preference and stored in a preferred location.
  - The output summary will be adjusted according to the configuration selected by the user.

<br/>

## Notes

- Currently, to use GPT-4, you need to [join a waitlist][gpt-4-wailist]. Once you have joined it, you will receive a confirmation email. After that, you will have to wait for an invitation to use the GPT-4 API. If you qualify to use it, you will see the GPT-4 model option for testing in the playground backend. Otherwise, if you do not have the qualifications, you should choose to use the GPT-3.5-Turbo model instead.

- ElevenLabs offers nine distinct voices to customise for your unique needs. Try them out [here][elevenlabs-voices] – please note that this will use the 10,000 characters of the free account. Once you identify the voice that suits you best, you can assign it to your Shortcut.

### Resources

#### Apple

- [Apple Shortcuts User Guide][apple-shortcuts-guide]

#### OpenAI

- [OpenAI Documentation][intro]
- [OpenAI Examples][examples]
- [OpenAI Models][open-ai-models]
- [OpenAI Usage API][chat-usage]

#### ElevenLabs

- [ElevenLabs Documentation][elevenlabs-docs]
- [ElevenLabs Speech Synthesis][elevenlabs-speech-synthesis]
- [ElevenLabs API Documentation][elevenlabs-api-doc]

#### Data Jar

- [Data Jar][data-jar]

### Contribution

Thank you for considering using this shortcut. If you encounter any issues or bugs, please report them on the [issues page][issues]. Your feedback is valuable in helping to improve this shortcut.<br/><br/>

<p align="center"><a href="#"><img src="https://user-images.githubusercontent.com/48920263/113406768-5a164900-93ac-11eb-94a7-09377a52bf53.png" draggable="false" ondragstart="return false;" /></a></p>

<p align="center"><a href="https://github.com/nicolodiamante" target="_blank"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/e4e14c16-0d0c-443b-adc2-b3af7e7ac1e5" draggable="false" ondragstart="return false;" alt="Nicol&#242; Diamante Portfolio" title="Nicol&#242; Diamante" width="11px" /></a></p>

<p align="center"><a href="https://github.com/nicolodiamante/SiriGPT/blob/main/LICENSE.md" target="_blank"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/585cd54d-ca38-412a-99fc-b3e06846b151" draggable="false" ondragstart="return false;" alt="The MIT License" title="The MIT License (MIT)" width="90px" /></a></p>

<!-- Link labels: -->
[open-ai-account]: https://chat.openai.com/auth/login
[open-ai-API]: https://beta.openai.com/account/api-keys
[open-ai-models]: https://platform.openai.com/docs/models
[apple-shortcuts-guide]: https://support.apple.com/en-gb/guide/shortcuts/apd58d46713f/ios
[apple-shortcuts-download]: https://apps.apple.com/us/app/shortcuts/id915249334
[dispatch-shortcut]: https://www.icloud.com/shortcuts/010e15b22aec4efba2a051a040574a80
[gpt-4-wailist]: https://openai.com/waitlist/gpt-4-api
[open-ai-prices]: https://openai.com/pricing
[chaGPT]: https://openai.com/blog/chatgpt
[examples]: https://platform.openai.com/examples
[intro]: https://platform.openai.com/docs/introduction
[chat-usage]: https://platform.openai.com/account/usage
[elevenlabs]: https://beta.elevenlabs.io/speech-synthesis
[elevenlabs-prices]: https://beta.elevenlabs.io/subscription
[elevenlabs-docs]: https://docs.elevenlabs.io/quickstart
[elevenlabs-speech-synthesis]: https://beta.elevenlabs.io/speech-synthesis
[elevenlabs-api-doc]: https://api.elevenlabs.io/docs
[elevenlabs-voices]: https://api.elevenlabs.io/v1/voices
[data-jar]: https://datajar.app
[issues]: https://github.com/nicolodiamante/dispatch/issues

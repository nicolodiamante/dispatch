<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/03e018d2-cbb7-4c0b-94b5-b851e8c332f4" draggable="false" ondragstart="return false;" alt="Dispatch Title" title="Dispatch" /></a></p>

You might be surprised to learn that artificial intelligence (AI) influences your life more than you realise – from reading your emails to navigating driving directions to delivering music. Now, imagine taking this even further with “Wake Me Up” – an interactive shortcut powered by [ChatGPT][chaGPT] and [ElevenLabs][elevenlabs], two leading AI technologies for natural language processing and realistic speech recordings. "Wake Me Up" acts as your personal assistant, keeping you on schedule while providing you with a summaries of your daily tasks with a realistic vocal tone.

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/8a0ce959-8f30-4ead-8471-43bbc454bd0c" draggable="false" ondragstart="return false;" alt="IMG show ChatGPT conbined with ElevenLabs" title="ChatGPT conbined with ElevenLabs" width="700px" /></a></p>

To successfully combine ChatGPT with ElevenLabs, you need to meet certain requirements and connect the appropriate links. This process is relatively uncomplicated.
<br/><br/><br/>

## Requirements for the dispatch to work

### Get the Shortcut

To get started, download [Apple Shortcuts app][apple-shortcuts-download] and the  ["Wake Me Up" shortcut][dispatch-shortcut]. You can rename the shortcut to whatever you like, but before running it, make sure you keep reading.
<br/><br/>

<p align="center"><a href="https://www.icloud.com/shortcuts/b40469b4043e4b3094ba4d686385bd52"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/c656132e-3181-4c00-a2d7-4f0070c9ee84" draggable="false" ondragstart="return false;" alt="Download theShortcut" title="Download Shortcut" width="600px" /></a></p><br/>

### Create your OpenAI API Key

To use ChatGPT's services, you'll first need to obtain the API key. This can be done by generating a new secret key from your OpenAI account. To get started, you can obtain the key by following these steps. First, log in to your [OpenAI account][open-ai-account]. Next, look for the "Create new secret key" option and click on it.

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/4615b7fb-31ed-43a4-b002-76050fddca09" draggable="false" ondragstart="return false;" alt="IMG show how to create new secret key" title="Create new secret key" width="750px" /></a></p>

Once you have the [API Key][open-ai-API], integrating ChatGPT's services is a breeze. It's important to note that once you copy the key and close the pop-up, you won't be able to view it again, so it's crucial to keep the key in a secure location.
<br/><br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/SiriGPT/assets/48920263/53e9c637-d59e-4240-9d5f-ed4f22e7bc19" draggable="false" ondragstart="return false;" alt="IMG show an example of a OpenAI API Key" title="OpenAI API Key" width="750px" /></a></p><br/>

### Get ElevenLabs API key

To start using the ElevenLabs API, you must register for an API key on their [website][open-ai-account]. After signing in, click on your profile picture in the upper right corner, then select the 'Profile' option.
<br/><br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/a5ab4d70-4bda-4895-9e61-d5957d45dc0f" draggable="false" ondragstart="return false;" alt="IMG show how to create new secret key" title="Create new secret key" width="650px" /></a></p><br/>

Once you've created an account and went to profile settings there you can obtained an API key and start using their text-to-speech service.
<br/><br/><br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/05924927-9de1-498b-a839-1b58465fc89d" draggable="false" ondragstart="return false;" alt="IMG show an example of an ElevenLabs API Key" title="ElevenLabs API Key" width="570px" /></a></p><br/><br/>

## Setting Up

Once you have downloaded the shortcut and copied the API key, it’s time to make it work and see it in action:
<br/><br/><br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/0c22a81b-83fe-4b52-8b30-362883ff728f" draggable="false" ondragstart="return false;" alt="IMG show where paste your API keys" title="Paste your API keys" width="600px" /></a></p><br/><br/>

- Open the Shortcuts app and open the "Wake Me Up" shortcut you downloaded.

- Once you launch the "Wake Me Up" shortcut, you will be prompted to set your OpenAI API keys. You have two options for storing your keys: within the shortcut itself (selecting "No") or inside a third-party app called Data Jar (selecting "Yes"). It's important to note that if you opt to store your API keys within the shortcut, you should be extra cautious to keep them secure and not share them with anyone, as this could potentially lead to your API keys being exposed.

- The OpenAI API offers a variety of models with different capabilities and pricing plans for various use cases. The default model is GPT-3.5-turbo, though users can choose their own version based on their needs. Note that GPT-4 is currently in a limited beta, and access is only granted upon request. If you're looking for more information, take a look at the subscription plans available [here][open-ai-prices].

- If you subscribe to ElevenLabs for free, you will receive 10,000 characters per month. However, you'll likely hit your limit before the month ends. At that point, you will be automatically switched to Siri's voice, unless you upgrade your subscription to get additional characters. If you're looking for more information, take a look at the subscription plans available [here][elevenlabs-prices].
<br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/6919e4ab-d7c9-4cd7-884b-c5cefb9c8e01" draggable="false" ondragstart="return false;" alt="Shortcut Automation" title="Shortcut Automation" width="900px" /></a></p>

When you're ready to use the shortcut, simply activate Siri and say "Wake Me Up", this will generate and read your daily schedules. To make things even easier, set up an automation in the Shortcuts app that triggers each time your wake-up alarm is stopped, so you no longer need to manually activate it.
<br/><br/><br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/23fb8e6b-351a-497e-8e3d-3eff4f6bc191" draggable="false" ondragstart="return false;" alt="Example Wake Me Up Output" title="Example Wake Me Up Output" width="1000x" /></a></p>

<br/>

## What's new in Dispatch

### v1.0.6

Release Highlights:

- Users can now adjust ChatGPT's Temperature, Top P, Frequency Penalty, and Presence Penalty Settings and ElevenLabs' Voice Stability and Similarity. Note: Decimal division is based on device region settings.
- Added the ability to customise shortcuts to listen to favourite playlists and podcasts after receiving the daily summary.

<br/>

### v1.0.5

Release Highlights:

- Reminder added for work-related departure times.
- Ability to listen to your favourite podcast at the end of the summary.
- Customisable API key storage location.
- Configurable output summary based on user preference.

<br/>

## Dispatch Privacy

Privacy is a user right, which is why Dispatch gives you the ability to choose which personal data to disclose during setup. Dispatch is a shortcut within the Apple ecosystem that already provides protection, including when third-party service providers are acting on behalf of Apple. However, OpenAI and ElevenLabs APIs are required for the shortcut to function. If you don't want to give out any information to third-party services, you won't be able to use Dispatch. However, if you consider using it, you should read the [OpenAI][openai-privacy]'s and [ElevenLabs][elevenlabs-privacy]' Privacy Policies first.
<br/><br/><br/>

<p align="center"><a href="#"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/32081137-4761-43e9-a5f7-a101f65da1b9" draggable="false" ondragstart="return false;" alt="Shortcut Privacy" title="Shortcut Privacy" width="900px" /></a></p>

<br/>

## Notes

#### GPT-4

Currently, to use GPT-4, you need to [join a waitlist][gpt-4-wailist]. Once you have joined it, you will receive a confirmation email. After that, you will have to wait for an invitation to use the GPT-4 API. If you qualify to use it, you will see the GPT-4 model option for testing in the playground backend. Otherwise, if you do not have the qualifications, you should choose to use the GPT-3.5-Turbo model instead.

#### ElevenLabs

ElevenLabs offers nine distinct voices to customise for your unique needs. Try them out [here][elevenlabs-voices] – please note that this will use the 10,000 characters of the free account. Once you identify the voice that suits you best, you can assign it to your Shortcut.

<br/>

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

Thank you for taking the time to consider using this shortcut. If you would like to contribute to improving Dispatch, your feedback would be appreciated. If you encounter any issues or bugs, please report them on the [issues page][issues].<br/><br/>

<p align="center"><a href="#"><img src="https://user-images.githubusercontent.com/48920263/113406768-5a164900-93ac-11eb-94a7-09377a52bf53.png" draggable="false" ondragstart="return false;" /></a></p>

<p align="center"><a href="https://github.com/nicolodiamante" target="_blank"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/e4e14c16-0d0c-443b-adc2-b3af7e7ac1e5" draggable="false" ondragstart="return false;" alt="Nicol&#242; Diamante Portfolio" title="Nicol&#242; Diamante" width="11px" /></a></p>

<p align="center"><a href="https://github.com/nicolodiamante/SiriGPT/blob/main/LICENSE.md" target="_blank"><img src="https://github.com/nicolodiamante/dispatch/assets/48920263/585cd54d-ca38-412a-99fc-b3e06846b151" draggable="false" ondragstart="return false;" alt="The MIT License" title="The MIT License (MIT)" width="90px" /></a></p>

<!-- Link labels: -->
[open-ai-account]: https://chat.openai.com/auth/login
[open-ai-API]: https://beta.openai.com/account/api-keys
[open-ai-models]: https://platform.openai.com/docs/models
[apple-shortcuts-guide]: https://support.apple.com/en-gb/guide/shortcuts/apd58d46713f/ios
[apple-shortcuts-download]: https://apps.apple.com/us/app/shortcuts/id915249334
[dispatch-shortcut]: https://www.icloud.com/shortcuts/b40469b4043e4b3094ba4d686385bd52
[gpt-4-wailist]: https://openai.com/waitlist/gpt-4-api
[open-ai-prices]: https://openai.com/pricing
[openai-privacy]: https://openai.com/policies/privacy-policy
[elevenlabs-privacy]: https://beta.elevenlabs.io/privacy
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

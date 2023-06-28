<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/nicolodiamante/dispatch/assets/48920263/8f74dafd-58c8-4315-aeac-60cae009c2d3" draggable="false" ondragstart="return false;" alt="Dispatch" title="Dispatch" />
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/453f0e1c-2676-4fd9-9c6b-42996dea2547" draggable="false" ondragstart="return false; "alt="Dispatch" title="Dispatch" />
  </picture>
</p>

You might be surprised to learn that artificial intelligence (AI) influences your life more than you realise – from reading your emails to navigating driving directions to delivering music. Now, imagine taking this even further with “Wake Me Up” – an interactive shortcut powered by [ChatGPT][chaGPT] and [ElevenLabs][elevenlabs], two leading AI technologies for natural language processing and realistic speech recordings. "Wake Me Up" acts as your personal assistant, keeping you on schedule while providing you with a summaries of your daily tasks with a realistic vocal tone.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/14c7a803-50d2-4646-b752-175fbae2b110" draggable="false" ondragstart="return false; "alt="OpenAI + ElevenLabs" title="OpenAI + ElevenLabs" width="700px" />
  </picture>
</p>

<br><br>

To successfully combine ChatGPT with ElevenLabs, you need to meet certain requirements and connect the appropriate links. This process is relatively uncomplicated.

<br><br>

## Requirements for the dispatch to work

### Get the Shortcut

To get started, download [Apple Shortcuts app][apple-shortcuts-download] and the  ["Wake Me Up" shortcut][dispatch-shortcut]. You can rename the shortcut to whatever you like, but before running it, make sure you keep reading.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/2f584cee-a8f3-4222-b144-2685178acc4f" draggable="false" ondragstart="return false;" alt="Download Shortcut" title="Download Shortcut" width="600px" />
  </picture>
</p>

<br><br>

### Create your OpenAI API Key

To use ChatGPT's services, you'll first need to obtain the API key. This can be done by generating a new secret key from your OpenAI account. To get started, you can obtain the key by following these steps. First, log in to your [OpenAI account][open-ai-account]. Next, look for the "Create new secret key" option and click on it.

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/2e1726d5-0491-4d0e-9957-dc34d5c05ea3" draggable="false" ondragstart="return false; "alt="Create new secret key"" title="Create new secret key" width="750px" />
  </picture>
</p>

Once you have the [API Key][open-ai-API], integrating ChatGPT's services is a breeze. It's important to note that once you copy the key and close the pop-up, you won't be able to view it again, so it's crucial to keep the key in a secure location.
<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/afe74503-2b89-48a7-bfb5-bdbaecac9580" draggable="false" ondragstart="return false; "alt="OpenAI API Key" title="OpenAI API Key" width="750px" />
  </picture>
</p>

<br>

### Get ElevenLabs API key

To start using the ElevenLabs API, you must register for an API key on their [website][open-ai-account]. After signing in, click on your profile picture in the upper right corner, then select the 'Profile' option.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/2084dfa1-e520-494f-accb-a70267318c36" draggable="false" ondragstart="return false;" alt="Create new secret key" title="Create new secret key" width="650px" />
  </picture>
</p>

<br><br>

Once you've created an account and went to profile settings there you can obtained an API key and start using their text-to-speech service.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/05924927-9de1-498b-a839-1b58465fc89d" draggable="false" ondragstart="return false;" alt="ElevenLabs API Key" title="ElevenLabs API Key" width="570px" />
  </picture>
</p>

<br><br>

## Setting Up

Once you have downloaded the shortcut and copied the API key, it’s time to make it work and see it in action:

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/b03d0bd8-af24-4727-ac33-27a53e08b102" draggable="false" ondragstart="return false;" alt="Paste your API keys" title="Paste your API keys" width="600px" />
  </picture>
</p>

<br><br>

- Open the Shortcuts app and open the "Wake Me Up" shortcut you downloaded.

- Once you launch the "Wake Me Up" shortcut, you will be prompted to set your OpenAI API keys. You have two options for storing your keys: within the shortcut itself (selecting "No") or inside a third-party app called Data Jar (selecting "Yes"). It's important to note that if you opt to store your API keys within the shortcut, you should be extra cautious to keep them secure and not share them with anyone, as this could potentially lead to your API keys being exposed.

- The OpenAI API offers a variety of models with different capabilities and pricing plans for various use cases. The default model is GPT-3.5-turbo, though users can choose their own version based on their needs. Note that GPT-4 is currently in a limited beta, and access is only granted upon request. If you're looking for more information, take a look at the subscription plans available [here][open-ai-prices].

- If you subscribe to ElevenLabs for free, you will receive 10,000 characters per month. However, you'll likely hit your limit before the month ends. At that point, you will be automatically switched to Siri's voice, unless you upgrade your subscription to get additional characters. If you're looking for more information, take a look at the subscription plans available [here][elevenlabs-prices].

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/83cfe080-57c7-400f-bed3-1caf84b3a685" draggable="false" ondragstart="return false;" alt="Shortcut Automation" title="Shortcut Automation" width="900px" />
  </picture>
</p>

<br><br>

When you're ready to use the shortcut, simply activate Siri and say "Wake Me Up", this will generate and read your daily schedules. To make things even easier, set up an automation in the Shortcuts app that triggers each time your wake-up alarm is stopped, so you no longer need to manually activate it.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/ff424f85-0e89-45f4-8c2f-c6b3395cb9be" draggable="false" ondragstart="return false;" alt="Wake Me Up Output" title="Wake Me Up Output" width="1000px" />
  </picture>
</p>

<br><br>

## What's new in Dispatch

### v1.0.7

Release Highlights:

- Users now have the option to choose between two language models offered by ElevenLAbs: monolingual and multilingual. Monolingual will generate standard English language, while the multilingual model will produce lifelike, varied speech in multiple languages including English, German, Polish, Spanish, Italian, French, Portuguese, and Hindi. Note that the multilingual model is still in beta, so translated speech can be unpredictable, especially if the text exceeds 1000 characters.

- Users can now turn on latency optimisations at some cost of quality. The best possible final latency varies by model. Possible values:
  - 0 default mode (no latency optimisations).
  - 1 normal latency optimisations (about 50% of possible latency improvement of option 3).
  - 2 strong latency optimisations (about 75% of possible latency improvement of option 3).
  - 3 max latency optimisations.
  - 4 max latency optimisations, but also with text normaliser turned off for even more latency savings (best latency, but can mispronounce e.g. numbers and dates).

- Changed stability and similarity values of the voice to improve the output.

<br>

### v1.0.6

Release Highlights:

- Users can now adjust ChatGPT's Temperature, Top P, Frequency Penalty, and Presence Penalty Settings and ElevenLabs' Voice Stability and Similarity.
- Added the ability to listen to a favourite playlist or podcast after receiving the daily summary.

<br>

### v1.0.5

Release Highlights:

- Reminder added for work-related departure times.
- Ability to listen to your favourite podcast at the end of the summary.
- Customisable API key storage location.
- Configurable output summary based on user preference.

<br>

## Dispatch Privacy

Privacy is a user right, which is why Dispatch gives you the ability to choose which personal data to disclose during setup. Dispatch is a shortcut within the Apple ecosystem that already provides protection, including when third-party service providers are acting on behalf of Apple. However, OpenAI and ElevenLabs APIs are required for the shortcut to function. If you don't want to give out any information to third-party services, you won't be able to use Dispatch. However, if you consider using it, you should read the [OpenAI][openai-privacy]'s and [ElevenLabs][elevenlabs-privacy]' Privacy Policies first.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/b637eaab-892a-470d-a589-359c5cb75a61" draggable="false" ondragstart="return false;" alt="Shortcut Privacy" title="Shortcut Privacy" width="900px" />
  </picture>
</p>

<br><br>

## Notes

#### GPT-4

Currently, to use GPT-4, you need to [join a waitlist][gpt-4-wailist]. Once you have joined it, you will receive a confirmation email. After that, you will have to wait for an invitation to use the GPT-4 API. If you qualify to use it, you will see the GPT-4 model option for testing in the playground backend. Otherwise, if you do not have the qualifications, you should choose to use the GPT-3.5-Turbo model instead.

#### ElevenLabs

ElevenLabs offers nine distinct voices to customise for your unique needs. Try them out [here][elevenlabs-voices] – please note that this will use the 10,000 characters of the free account. Once you identify the voice that suits you best, you can assign it to your Shortcut.

#### Language & Region (Number Separator)

The decimal point used when setting decimal numbers is determined by the region settings of the device; for example, a decimal can be set as "0.1" or "0.1".

<br>

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

Thank you for taking the time to consider using this shortcut. If you would like to contribute to improving Dispatch, your feedback would be appreciated. If you encounter any issues or bugs, please report them on the [issues page][issues].
<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/17fe5a3f-c875-42ce-ae6b-1a0af715a29b" draggable="false" ondragstart="return false;" /></>
  </picture>
</p>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/e44ada79-bb9b-4a56-b9dd-40ea9bded38a" draggable="false" ondragstart="return false;" alt="Nicol&#242; Diamante" title="Nicol&#242; Diamante" width="17px" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/nicolodiamante/dispatch/assets/48920263/49fde07f-b290-4d58-9040-2a7e3998e189" draggable="false" ondragstart="return false;" alt="MIT License" title="MIT License" />
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/00832ba1-60e7-4229-ad5f-f1145549a28a" draggable="false" ondragstart="return false; "alt="MIT License" title="MIT License" width="95px" />
  </picture>
</p>

<!-- Link labels: -->
[open-ai-account]: https://chat.openai.com/auth/login
[open-ai-API]: https://beta.openai.com/account/api-keys
[open-ai-models]: https://platform.openai.com/docs/models
[apple-shortcuts-guide]: https://support.apple.com/en-gb/guide/shortcuts/apd58d46713f/ios
[apple-shortcuts-download]: https://apps.apple.com/us/app/shortcuts/id915249334
[dispatch-shortcut]: https://www.icloud.com/shortcuts/97a1f40916a74b0d930d8709186c96f6
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

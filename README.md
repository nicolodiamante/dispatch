<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/nicolodiamante/dispatch/assets/48920263/8f74dafd-58c8-4315-aeac-60cae009c2d3" draggable="false" ondragstart="return false;" alt="Dispatch" title="Dispatch" />
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/453f0e1c-2676-4fd9-9c6b-42996dea2547" draggable="false" ondragstart="return false; "alt="Dispatch" title="Dispatch" />
  </picture>
</p>

Artificial Intelligence (AI) already plays a significant role in numerous aspects of your daily life that you may not be aware of. For instance, AI assists in sorting your emails, providing driving directions, and delivering your favourite music. Now, consider the advancement of this integration with the use of 'Wake Me Up', an interactive shortcut. This service is enhanced by two prominent AI technologies – [ChatGPT][chaGPT] and [ElevenLabs][elevenlabs], specialising respectively in natural language processing and realistic speech recordings. 'Wake Me Up' serves as a personal assistant, managing your schedule and offering a summary of your daily tasks through a lifelike vocal tone.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/14c7a803-50d2-4646-b752-175fbae2b110" draggable="false" ondragstart="return false; "alt="OpenAI + ElevenLabs" title="OpenAI + ElevenLabs" width="700px" />
  </picture>
</p>

<br><br>

In order to effectively integrate ChatGPT with ElevenLabs, you must fulfil specified prerequisites and establish the necessary connections. Fortunately, this sequence of steps is relatively straightforward.

<br><br>

## Requirements for the dispatch to work

### Get the Shortcut

To initiate, first download the [Apple Shortcuts][apple-shortcuts-download] app followed by the '[Wake Me Up][dispatch-shortcut]' shortcut. Feel free to rename the shortcut to a title of your preference. However, before you begin using it, ensure that you continue reading for further instructions.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/5ffd51f0-7004-44ad-96ec-b310cac479f9" draggable="false" ondragstart="return false;" alt="Download Shortcut" title="Download Shortcut" width="600px" />
  </picture>
</p>

<br><br>

### Create your OpenAI API Key

In order to utilise the services provided by OpenAI, an API key is required. You can procure this key by creating a new secret key through your existing [OpenAI account][open-ai-account]. Commence the process by following these instructions. The initial step requires you to sign in to your OpenAI account. Subsequently, search for the 'Create new secret key' option and select that.

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/2e1726d5-0491-4d0e-9957-dc34d5c05ea3" draggable="false" ondragstart="return false; "alt="Create new secret key"" title="Create new secret key" width="750px" />
  </picture>
</p>

After acquiring the [API Key][open-ai-API], integration with SiriGPT's services becomes simple. Please remember, once you have copied the key and closed the pop-up, it will not be visible again. Therefore, it is vital to store the key in a secure place.
<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/afe74503-2b89-48a7-bfb5-bdbaecac9580" draggable="false" ondragstart="return false; "alt="OpenAI API Key" title="OpenAI API Key" width="750px" />
  </picture>
</p>

<br>

### Get ElevenLabs API key

To commence utilising the ElevenLabs API, you are required to sign up for an API key via their official [website][open-ai-account]. Once you have successfully logged in, navigate to the upper right corner and click on your profile picture. Subsequently, choose 'Profile' from the options available."

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/2084dfa1-e520-494f-accb-a70267318c36" draggable="false" ondragstart="return false;" alt="Create new secret key" title="Create new secret key" width="650px" />
  </picture>
</p>

<br><br>

Once you've opened the profile settings, you can then obtain an API key, which will allow you to start using their text-to-speech service.
<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/05924927-9de1-498b-a839-1b58465fc89d" draggable="false" ondragstart="return false;" alt="ElevenLabs API Key" title="ElevenLabs API Key" width="570px" />
  </picture>
</p>

<br><br>

## Setting Up

After you've successfully downloaded the shortcut and copied the API key, it's time to engage its functionality and see it in action:

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/b03d0bd8-af24-4727-ac33-27a53e08b102" draggable="false" ondragstart="return false;" alt="Paste your API keys" title="Paste your API keys" width="600px" />
  </picture>
</p>

<br><br>

- Start by launching the Shortcuts app on your device and select the "Wake Me Up" shortcut that you've previously downloaded.

- Upon activating the "Wake Me Up" shortcut, you'll need to enter your OpenAI and EleveLabs API keys. You can choose to store these keys either directly in the shortcut or in the Data Jar app. However, if you choose to store the keys in the shortcut, it's crucial to ensure their privacy. Any inadvertent exposure could compromise your security and potentially result in a breach.

- Next, proceed with the setup process. Carefully follow every required step to tailor the output prompt and voice to meet your specific preferences for the shortcut. Once completed, 'Wake Me Up' can be put to use immediately.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/83cfe080-57c7-400f-bed3-1caf84b3a685" draggable="false" ondragstart="return false;" alt="Shortcut Automation" title="Shortcut Automation" width="900px" />
  </picture>
</p>

<br><br>

When you wish to use the shortcut, just turn on Siri and utter the command, "Wake Me Up". Upon doing this, your daily schedules will be generated and read out to you. For further simplicity, you can establish an automation in the Shortcuts application. This will be triggered each time you silence your wake-up alarm, eliminating the need for you to manually activate it.

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

This shortcut is primarily programmed to operate on the GPT-4 model by default. When we compare the operations of GPT-4 model with the GPT-3.5 model, there is little to distinguish between them in terms of performance for relatively straightforward tasks. However, the GPT-4 model outperforms the previous versions, especially when encountering complex reasoning scenarios. If you wish to access the GPT-4-serviced API, it's crucial to note that this privilege is limited to APIs with a history of successful transactions. If an API isn't eligible to run on the GPT-4 model, for instance, if it doesn't meet ChatGPT-4's qualification criteria, it's recommended to default to the GPT-3.5-Turbo model. If you're looking to explore the various subscription packages, you can review the available options [here][open-ai-prices].

#### ElevenLabs

Signing up to ElevenLabs gives you a free subscription, which includes 10,000 characters per month. Nonetheless, you may exhaust your limit before the month ends. When this happens, you'll automatically switch to Siri's voice unless you choose to enhance your subscription for additional characters. Also when you try out the ElevenLabs voices to identify the voice that suits you best (try them out [here][elevenlabs-voices]) they will use the 10,000 characters of the free account. For information about upgrade your account, see the subscription options [here][elevenlabs-prices].

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

Thank you for considering the use of this shortcut. Your collaboration in improving Dispatch would be of immense value and your feedback would be much appreciated. In case you run into any issues or bugs, please report them on the [issues page][issues].
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
[dispatch-shortcut]: https://www.icloud.com/shortcuts/294ddd5605fc4ffd8dccd9bfd34e95cf
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

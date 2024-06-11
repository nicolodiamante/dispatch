<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/nicolodiamante/dispatch/assets/48920263/a61804ee-bdf6-469b-ba71-1d39b43ed30c" draggable="false" ondragstart="return false;" alt="Dispatch" title="Dispatch" />
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/51b93d33-40e8-4190-9e5e-dbb80e627766" draggable="false" ondragstart="return false; "alt="Dispatch" title="Dispatch" />
  </picture>
</p>

Artificial Intelligence (AI) already plays a significant role in numerous aspects of your daily life that you may not be aware of. For instance, AI assists in sorting your emails, providing driving directions, and delivering your favourite music. Now, consider the advancement of this integration with the use of Wake Me Up an interactive shortcut. This service is enhanced by two prominent AI technologies – [ChatGPT][chaGPT] and [ElevenLabs][elevenlabs], specialising respectively in natural language processing and realistic speech recordings. Wake Me Up serves as a personal assistant, managing your schedule and offering a summary of your daily tasks through a lifelike vocal tone.

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

To initiate, first download the [Apple Shortcuts][apple-shortcuts-download] app followed by the [Wake Me Up shortcut][dispatch-shortcut]. Feel free to rename the shortcut to a title of your preference. However, before you begin using it, ensure that you continue reading for further instructions.

<br><br>

<p align="center">
  <a href="https://www.icloud.com/shortcuts/035647290a6a449da04f3b32f1511569" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/nicolodiamante/dispatch/assets/48920263/d4715aa2-b33c-44af-abe2-4e0dbcdafc72" draggable="false" ondragstart="return false;" alt="Download the Shortcut" title="Download Wake Me Up" />
      <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/7b29ca12-10ff-4597-be18-82f95868a5cf" draggable="false" ondragstart="return false; "alt="Download the Shortcut" title="Download Wake Me Up" width="600" />
    </picture>
  </a>
</p>

<br>

> Please make sure to complete the following tasks when transitioning to the new version: Decode the API keys that were previously stored in an encrypted format in the Data Jar. To simplify this process, use the [DecodeMe][decode-key-shortcut] shortcut. Remember to complete this for each key of OpenAI's and ElevenLabs.

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
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/dec4c53b-d239-4046-bd30-fa2ed49c8cc6" draggable="false" ondragstart="return false; "alt="OpenAI API Key" title="OpenAI API Key" width="750px" />
  </picture>
</p>

<br>

### Get ElevenLabs API key

To commence utilising the ElevenLabs API, you are required to sign up for an API key via their official [website][open-ai-account]. Once you have successfully logged in, navigate to the upper right corner and click on your profile picture. Subsequently, choose Profile from the options available.

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

- Start by launching the Shortcuts app on your device and select the Wake Me Up shortcut that you've previously downloaded.

- Upon activating the Wake Me Up shortcut, you'll need to enter your OpenAI and ElevenLabs API keys. You can choose to store these keys either directly in the shortcut or in the Data Jar app. However, if you choose to store the keys in the shortcut, it's crucial to ensure their privacy. Any inadvertent exposure could compromise your security and potentially result in a breach.

- Next, proceed with the setup process. Carefully follow every required step to tailor the output prompt and voice to meet your specific preferences for the shortcut. Once completed, Wake Me Up can be put to use immediately.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/83cfe080-57c7-400f-bed3-1caf84b3a685" draggable="false" ondragstart="return false;" alt="Shortcut Automation" title="Shortcut Automation" width="900px" />
  </picture>
</p>

<br><br>

When you wish to use the shortcut, just turn on Siri and utter the command Wake Me Up. Upon doing this, your daily schedules will be generated and read out to you. For further simplicity, you can establish an automation in the Shortcuts application. This will be triggered each time you silence your wake-up alarm, eliminating the need for you to manually activate it.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/04097a01-e3c7-475f-89e1-cbf4832c7a14" draggable="false" ondragstart="return false;" alt="Wake Me Up Output" title="Wake Me Up Output" width="1000px" />
  </picture>
</p>

<br><br>

## What's new in Dispatch

### v1.2.2

Release Highlights:

- API Key Storage Enhancement: To resolve issues with script readability, API keys will no longer be encrypted in Data Jar. Previously, encryption caused errors that prevented the Shortcut from reading the API key. Storing keys unencrypted will ensure seamless script functionality.

- New Playlist Selection Option: Users can now choose between Apple Music or Spotify playlists. Note: Spotify must be already open for the playlist to play automatically. Currently working on a solution to improve this process.

- ElevenLabs Voice Settings Enhancement: Changed the settings in ElevenLabs voices to reduce exaggerated speech patterns, ensuring a more natural and pleasant listening experience.

<br>

### v1.2.1

Release Highlights:

- New Model Integration: This update simplifies the model options from 4 to 3. Users now have three distinct models to choose from: ChatGPT-3.5-Turbo, which now points to ChatGPT-3.5-Turbo-0125; ChatGPT-4 has been upgraded to ChatGPT-4-Turbo; and the newly introduced ChatGPT-4o is now available. This adjustment aims to simplify model selection while maintaining advanced capabilities.

- Voice List Update: The voice list of ElevenLabs has been refreshed, removing the following voices that are no longer available:
  - AMERICAN: Bella, Elli, Domi, Ryan, Thomas
  - BRITISH: Matthew
  - SPECIAL: Santa Claus

<br>

### v1.2

Release Highlights:

- Models Integrations: Integrated the ChatGPT-4-Turbo model, combining GPT-4's advanced reasoning with enhanced processing speed for quicker, more efficient responses, also added the ChatGPT-3.5-Turbo-1106 variant, which offers an upgraded performance on the 3.5-Turbo model for scenarios requiring incremental improvements in response quality while maintaining high efficiency and speed.

- Prompt Output Enhancement: Improved the prompt's output for more human-like interactions, ensuring users receive more valuable and relevant information.

- Flexible Speech Output Provider Options: Introduced the option to choose between OpenAI and ElevenLabs for voice output, giving users the flexibility to select their preferred text-to-speech provider.

- ElevenLabs Voice Setting Enhancements: Added the ability to customise voice style and speaker boost feature, providing users greater control and a more enriched audio experience.

- Expanded ElevenLabs Voice Selection: Added new voices for speech output customisation.

  Available Voices:

  - AMERICAN: Bill, Drew, Paul
  - BRITISH: George, Lily
  - SPECIAL: Santa Claus

<br>

### v1.1.2

Release Highlights:

- Enhanced Podcast Selection Logic: Upgraded the podcast selection mechanism in the shortcut, coupled with improvements in the customisation process, resulting in a more intuitive and user-friendly experience for users.

- Prompt Output Enhancement: Improved the prompt's output for more human-like interactions, ensuring users receive more valuable and relevant information.

<br>

### v1.1.1

Release Highlights:

- Shortcut Actions Revision: Streamlined the Shortcut actions for increased efficiency.

- Prompt Clarity Improvement: Enhanced the prompt for clearer and more understandable output.

<br>

### v1.1.0

Release Highlights:

- Token Customisation Option: Introduced the ability for users to customise the number of tokens used in content generation. Note: The maximum token count is shared between the prompt and completion sections, and the limit varies depending on the model. On average, one token equals about 4 characters in standard English.

- Expanded Voice Selection: Added new voices for speech output customisation. Remember, testing these voices counts towards the 10,000-character limit on free accounts.

  Available Voices:

  - American: Adam, Antoni, Arnold, Bella, Callum, Clyde, Daniel, Dave, Domi, Elli, Emily, Ethan, Freya, Gigi, Glinda, Grace (American-Southern), Harry, Jeremy (American-Irish), Jessie, Josh, Liam, Matilda, Michael, Nicole, Patrick, Rachel, Ryan, Sam, Serena, Thomas
  - Australian: Charlie, James
  - British: Dave (Essex), Dorothy, Joseph, Matthew
  - Irish: Fin
  - Italian (English): Giovanni
  - Swedish (English): Charlotte, Mimi

<br>

### v1.0.7

Release Highlights:

- Language Model Choices: Users can now choose between Monolingual and Multilingual models from ElevenLabs. The Monolingual model focuses on standard English, while the Multilingual model offers diverse dialogue in several languages. Note: The Multilingual model is in beta and may produce unpredictable results for long texts.

- Latency Optimisation Settings: Implemented new settings for controlling latency with potential trade-offs in quality.

  - 0: Default (no optimisations)
  - 1: Normal latency optimisations
  - 2: Strong latency optimisations
  - 3: Maximum latency optimisations
  - 4: Maximum optimisations with text normaliser off (may affect pronunciation accuracy)

- Voice Quality Improvements: Adjusted stability and similarity parameters for better voice output.

<br>

### v1.0.6

Release Highlights:

- Enhanced Customization Settings: Users can now fine-tune settings like Temperature, Top P, Frequency Penalty, and Presence Penalty, as well as Voice Stability and Similarity.

- Audio Content Options Post-Summary: Added the option to enjoy a favourite playlist or podcast following the daily summary.

<br>

### v1.0.5

Release Highlights:

- Work Departure Time Reminder: Added a feature to remind users of optimal departure times for work.

- Podcast Listening Post-Summary: Enabled the option to listen to a favourite podcast at the end of the summary.

- API Key Storage Customisation: Users can now choose where to store their API keys.

- Configurable Summary Output: Provided options for users to tailor the output summary to their preferences.

<br>

## Dispatch Privacy

Privacy is a user right, which is why Dispatch gives you the ability to choose which personal data to disclose during setup. Dispatch is a shortcut within the Apple ecosystem that already provides protection, including when third-party service providers are acting on behalf of Apple. However, OpenAI and ElevenLabs APIs are required for the shortcut to function. If you don't want to give out any information to third-party services, you won't be able to use Dispatch. However, if you consider using it, you should read the [OpenAI][openai-privacy]'s and [ElevenLabs][elevenlabs-privacy]' Privacy Policies first.

<br><br>

<p align="center">
  <picture>
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/df3ff297-12e8-4ab9-ab13-48087b56bb52" draggable="false" ondragstart="return false;" alt="Shortcut Privacy" title="Shortcut Privacy" width="900px" />
  </picture>
</p>

<br><br>

## Notes

### GPT-4

This shortcut is primarily programmed to operate on the GPT-4 model by default. When we compare the operations of GPT-4 model with the GPT-3.5 model, there is little to distinguish between them in terms of performance for relatively straightforward tasks. However, the GPT-4 model outperforms the previous versions, especially when encountering complex reasoning scenarios. If you wish to access the GPT-4-serviced API, it's crucial to note that this privilege is limited to APIs with a history of successful transactions. If an API isn't eligible to run on the GPT-4 model, for instance, if it doesn't meet ChatGPT-4's qualification criteria, it's recommended to default to the GPT-3.5-Turbo model. If you're looking to explore the various subscription packages, you can review the available options [here][open-ai-prices].

<br>

### OpenAI Text to Speech

The TTS model generally follows the Whisper model in terms of language support. Whisper supports the following languages and performs well despite the current voices being optimised for English:

Afrikaans, Arabic, Armenian, Azerbaijani, Belarusian, Bosnian, Bulgarian, Catalan, Chinese, Croatian, Czech, Danish, Dutch, English, Estonian, Finnish, French, Galician, German, Greek, Hebrew, Hindi, Hungarian, Icelandic, Indonesian, Italian, Japanese, Kannada, Kazakh, Korean, Latvian, Lithuanian, Macedonian, Malay, Marathi, Maori, Nepali, Norwegian, Persian, Polish, Portuguese, Romanian, Russian, Serbian, Slovak, Slovenian, Spanish, Swahili, Swedish, Tagalog, Tamil, Thai, Turkish, Ukrainian, Urdu, Vietnamese, and Welsh.

It can generate spoken audio in these languages with the input text in the language of your choice.

<br>

### ElevenLabs

Signing up to ElevenLabs gives you a free subscription, which includes 10,000 characters per month. Nonetheless, you may exhaust your limit before the month ends. When this happens, you'll automatically switch to Siri's voice unless you choose to enhance your subscription for additional characters. Also when you try out the ElevenLabs voices to identify the voice that suits you best they will use the 10,000 characters of the free account. For information about upgrade your account, see the subscription options [here][elevenlabs-prices].

<br>

### Language & Region (Number Separator)

The decimal point used when setting decimal numbers is determined by the region settings of the device; for example, a decimal can be set as 0.1 or 0.1.

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
  <a href="https://nicolodiamante.com" target="_blank">
    <img src="https://github.com/nicolodiamante/dispatch/assets/48920263/e44ada79-bb9b-4a56-b9dd-40ea9bded38a" draggable="false" ondragstart="return false;" alt="Nicol&#242; Diamante Portfolio" title="Nicol&#242; Diamante" width="17px" />
  </a>
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
[dispatch-shortcut]: https://www.icloud.com/shortcuts/035647290a6a449da04f3b32f1511569
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
[data-jar]: https://datajar.app
[decode-key-shortcut]: https://www.icloud.com/shortcuts/0ce3c6d5944a42d4951576620d75f8fe
[issues]: https://github.com/nicolodiamante/dispatch/issues

# Voice / Audio 2 Text Sample

#### Description:
##### Here, you can find a simple example of voice or audio transcription using the Voice to Text service provided by Google Cloud Platform.

#### Requirements:
##### - Google Account.
##### - Billing Account asocieted in Google Cloud Platform.

#### Setup:
##### If you want to try it, follow the steps:
 - Clone the repo in your pc.
 - Create a service account key.
 - Download the .json file and move it into the root of the repository.
 - Add to your `.zshrc` or `.bashrc` the path to the .json file use a key name like `GOOGLE_CLOUD_PLATFORM_CREDENTIALS`
 - here is the reference to make it easy [Set credentials](https://cloud.google.com/docs/authentication/getting-started#setting_the_environment_variable) 

- run `npm i` on the root of the repository.
- run `npm run start`.
- Check the console/terminal for the voice transcription in the `.wav` example file.

#### Notes:
 - ***Line 17 of index.js file:***
the property defines the language to try to transcribe. If you plan to use a different language, please go to the service's documentation to check each format to send the right sting value.

- Google Cloud Platform isn't free. If you need to have a tool that requires a voice to text transcription, try [#vosk-api](https://github.com/alphacep/vosk-api), I will try it in a future example.

Thanks and enjoy it!
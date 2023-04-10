![Readme](https://user-images.githubusercontent.com/79281788/230729315-414e95a9-9d1e-4df9-adbc-40a72cf16a20.png)<br>
Plugin for pocketmine-MP API4+<br>
Ask a question and become answer from gpt-3.5-turbo model<br>

Works only with API-KEY<br>
https://platform.openai.com/account/api-keys<br>

The use of OpenAi ChatgGTP is limited in the free trial.<br>
You get a $5 grant per registration, after which you have to top up your credit or create a new account.<br>
Prices are per 1,000 tokens. You can think of tokens as pieces of words, where 1,000 tokens is about 750 words.<br>
$0.002 / 1K tokens.<br>

HOW TO START ?<br>
Just put your API-KEY in the config.yml and start the server.<br>
Only users with ```pmgpt.use``` permission can run the command ```chatgpt```<br>


PREVIEW:<br>
Question: tell me good names for factions.<br>
![descriptionUI](https://user-images.githubusercontent.com/79281788/231010759-e0425c13-3ddf-4c12-852e-c556e5a8bd20.png)<br>


### TODO-List
- [x] Add gpt-3.5-turbo model instead of text-davinci-002
- [x] Add remembering previous questions
- [x] Run response action on async task to prevent freeze on waiting for response
- [ ] Inform user when ChatGPT is at capacity
- [x] Work with UI instead of Chat 
- [x] Send a please wait message if the response takes a little longer


Suggestions ?, let me know!<br>
Pocketmine-MP API4 [GLX20]<br>

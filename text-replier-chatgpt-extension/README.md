# Text Replier ChatGPT OpenAI API Chrome Extension

## Languages: JavaScript (Plain)

## API: OpenAI

## Workflow:
- Reply to emails (in all languages supported by chatGPT).
- Ideally the process is as follows : the user highlights the text of the email he wants to answer, right clicks, a contextual menu opens where user chooses between 4 possibilities:
	- "Write a very positive reply"
	- "Write a slightly positive reply"
	- "Write a slightly negative reply"
	- "Write a very negative reply".
- Then a pop-up window opens with the reply to the email. In this pop-up there is also a big "copy" button for the user to copy the text of the reply, and a cross for the client to close the pop-up.
- The prompt for ChatGPT would be for example "Please act as my secretary in responding to my email.
- Respond to this message in a detailed and polite manner, including greetings at the beginning and end, without giving any further explanation. Sign with my name : ...".
- The client can indicate his name during registration and in the extension settings, so that we put it in the prompt as a signature.
- It's your own server (API key) that pays for the tokens to make sure that it always works for the users.
# HarryPotter-Discord-Chatbot

  ![output-onlinepngtools](https://github.com/nightbounty/HarryPotter-Discord-Chatbot/assets/104731480/d92eaf73-32ee-4821-a744-71175684071e)



This is a Discord AI Chatbot that uses the Microsoft DialoGPT conversational model fine-tuned on the movie transcript of Harry Potter and the Sorcerer's Stone.

I trained the model using the lines of Harry Potter. He has about 1500 lines in total
<br/><br/>
Here is a demo of the Discord bot in action.
<br/>
![Screen Shot 2023-05-23 at 3 40 32 PM](https://github.com/nightbounty/HarryPotter-Discord-Chatbot/assets/104731480/9412a7bb-54bc-43ec-90b5-137890f03e7c)



You can also directly chat with the model hosted on [Hugging Face's Model Hub](https://huggingface.co/kevintest1234/DialoGPT-small-harrypotter).

![Screen Shot 2023-05-23 at 3 34 18 PM](https://github.com/nightbounty/HarryPotter-Discord-Chatbot/assets/104731480/a99c62d0-805c-4e79-83c5-2d5ea671ab26)

## Structure of this Project

- `model_train_upload_workflow.ipyb`: Notebook to be run in Google Colab to train and upload the model to Hugging Face's Model Hub
- `discord_bot.py`: Script to be imported into a Repl.it Python Discord.py project

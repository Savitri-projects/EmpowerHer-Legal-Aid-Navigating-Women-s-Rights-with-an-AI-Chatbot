
#EmpowerHer Legal Aid: Navigating Women's Rights with an AI Chatbot

Introducing the website featuring women's legal rights information covering issues such as Immoral Trafficking, Dowry, Sati, Domestic Violence, Child Marriage, and Sexual Harassment at the workplace. Highlighting our star feature: a chatbot built using nltk, flask, and torch libraries. This chatbot can provide information on topics like 'sati' and answer queries such as 'Is performing sati sahagamanam correct?' The chatbot is trained specifically for 'sati' and handles various related scenarios.






## How to use it

1. First clone the repository with 
`git clone https://github.com/Savitri-projects/EmpowerHer-Legal-Aid-Navigating-Women-s-Rights-with-an-AI-Chatbot.git` command

2. Open the folder in VS code

3. In fact, you will just have to run `python train.py`and `python app.py` commands one by one

4. But you will need python installed on your laptop

5. If there's any missing library, you should be able to install it through `pip install <missing-library-name>`

6. If you want a complete setup with virtual environment and understand how the entire thing works: Check [here](https://youtu.be/a37BL0stIuM?si=AgSUfMYdlNBrV6RW)
## What to check in this

1. First open `intents.json` file. There are "tags", "patterns" and "responses" there. Understand them.
-   Patterns are the questions that can be asked
-   Responses are the responses that the chatbot will give if the question asked by the user matches the pattern/is similar to the pattern

2. Once `app.py` succesfully runs open the link: http://127.0.0.1:5000/

3. You should be able to see this screen ![](https://i.postimg.cc/FHL7KVtf/image.png)

4. You can navigate through different sections from the bar that has all the names

5. As you scroll down towards the end you will see a button in the right bottom corner saying: `"More questions? Chat with us"`

6. Click on that and a box will popup. 

7. Now, from your understanding on the `intents.json` file, give questions and compare answers

8. Please find few screenshot on how it works

| Closer to pattern | Bit far from pattern |
| ------- | ------- |
| ![Image 1](https://i.postimg.cc/J7k39Z0h/image.png) | ![Image 2](https://i.postimg.cc/90YDcWsL/image.png) |
| ![Image 3](https://i.postimg.cc/9XY0RQNp/image.png) | ![Image 4](https://i.postimg.cc/4xDs2DSy/image.png) |
| ![Image 5](https://i.postimg.cc/XvNSPngV/image.png) | ![Image 6](https://i.postimg.cc/bN17NZCy/image.png) |
| ![Image 7](https://i.postimg.cc/hGZw3Tjr/image.png) | ![Image 8](https://i.postimg.cc/28dtNPy3/image.png) |
| ![Image 9](https://i.postimg.cc/BZHY2dxN/image.png) | ![Image 10](https://i.postimg.cc/j2bh8Szc/image.png) |

## Enhancements/ Research that you can do

1. There are many enhancements possible

2. Try making the model even better by improving its accuracy

3. Try implementing with other `intents`

4. Deploy the website - dynamically

5. Make the UI look even better

... and many more

Thanks for coming here!!
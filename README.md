# PythonAI
This project is an implementation of the [OpenAI API](https://openai.com/api/).
It's purpose is to create dev-ready projects with virtually any technology you can think of. It can be modified in order to create any kind of file that can be created using bash scripts.

# How to use
In order to be able to use the script, you must, first of all, get your own OpenAI api key and place it in an env variable called `OPENAI_API_KEY`.
Then install the dependencies with 

```sh
pip install -r requirements.txt 
```

and you are ready to go.

## Syntax

```sh
python pythonai.py <technology to use> <name of the project>
```

for example:

```sh
python pythonai.py expressjs sample-server
```

# How does this work?
The idea is rather simple, OpenAI completions api can only receive text as instructions, and can only return text responses, thus creating something more complex like a whole expressjs project doesn't feel like that easy to achieve, though it is possible if you ask the AI to create a **bash script** that does exactly what you want to create, and this is the core and fundamental idea behind this project: **you ask for a project, and the ai gives you a bash script that you will, afterwards, execute.**

# Want to contribute?
Feel free to fork the project and open pull requests when you feel like your feature/fix is ready.

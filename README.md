# PythonAI
This project is an implementation of the [OpenAI API](https://openai.com/api/).
It's purpose is to create dev-ready projects with virtually any technology you can imagine. It can be modified in order to create any kind of file that can be created using bash scripts.

# How to use
In order to be able to use the script, you must, first of all, get your own OpenAI api key and place it in an env variable called `OPENAI_API_KEY`.
Then, you install the dependencies with 

```sh
pip install -r requirements.txt 
```

and you are ready to start using the script with 

```sh
python pythonai <technology to use> <name of the project>
```

for instance

```sh
python pythonai expressjs sample-server
```

# How does this work?
The idea is rather simple, OpenAI completions api can only receive text as instructions, and can only return text responses as well, thus creating something more sustantial like a whole expressjs project doesn't feel like that easy to achieve, though it is possible if you ask the AI to create a **bash script** that does exactly what you want to create, and this is the core and fundamental idea behind this project: **you ask for a project, and the ai gives you a bash script that you will, afterwards, execute.**

# Wanna contribute?
Feel free to fork the project and open pull requests when you feel like your feature/fix is ready.

# Disclaimer
I'm not a python dev, if you notice some kind bad practices or something like that, please feel free to let me know.


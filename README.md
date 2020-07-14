# Webpack-config

Hi, this is my simple webpack config for layout.

<h2>What is he doing?</h2>

It takes css, js files and collects it into one file, which is connected to the page.

<h2>How to work with it?</h2>

First, you must have node.js installed: https://nodejs.org/en/.

Second, run the command prompt.

Third, specify the path to your project folder.
  
    
<h3>How to do it?</h3>

If the folder is not on the c drive, then write cd /d and the path to the folder, as in the file manager <br>
(you can drag the path from the file manager to the command line if you are too lazy to write) and press enter.

if on drive c, then /d do not need to be written.

Example: cd /d E:\npm-test.
Explanations: cd - short for change directory, and / d changes the current drive.

More details here:
https://www.digitalcitizen.life/command-prompt-how-use-basic-commands.

Continue.

Fourth, write - "npm i".

Explanation: The path must lead to the folder in which the development will be carried out (the root folder of the project) and in which the settings folders will be.

Done!

The installation of the necessary modules should begin, you do not need to know something about this, everything is already configured for specific tasks.

<h2>Files, folders, connections</h2>

Now about using.

Everything is pretty simple. You make the project as you used to, but in the end, when you need to make the assembly and put it on the host, write "npm run w" After which the assembly will spit out the 
a script file to the outside (this behavior is easy to change) with the name script.js, which you will need to include in the html file and voila.

<h3>Now the details:</h3>

First, the reset comes from the import.js file, you need to import all the js and css file import into it.

Second, write c ./ in the css files path to the pictures, more in the example.

The folder in which the work takes place (root folder) builder. The file name and path are configured in the webpack.config.js file
on lines 4 (path to the start file), 6-9 (path to the source file and its name). If you want to change the path to the source file, then change it in quotation marks

Example: 
http://joxi.ru/Q2KPMD6Tv9dbPA
http://joxi.ru/eAOPj0KTk4axpr

I attach the project for an example, there is an example of using scripts, pictures and styles. There will be questions, comments, insults to my stupidity, you are welcome to my mail: chel.06081995@gmail.com and VK group: https://vk.com/web_dev_andreykorotin. Hope I helped someone.

P.S. Вообще я русский, и большую часть текста вбивал в гугле, так что не бейте сильно :D (Made using google translator)

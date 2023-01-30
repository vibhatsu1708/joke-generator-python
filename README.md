# joke-generator-python
This repository is for the joke generator made in Python. </br>

Title - JokeGenerator-Python </br>
Description - A joke generator project for the terminal made in Python. The jokes are fetched from the pyjokes library, and the multiple language support is provided by the integration of the 'googletrans' library for fluid translation. </br>

<img src="result-images/result-1.png" alt="Program output in English">
</br>
<img src="result-images/result-2.png" alt="Program output in alternative language preferred by the User.">

ProjectLog[0] - The idea for this project is simple, the user will be asked for the permission to move forward with the program, if permission is granted, the user will be asked for the language and the category. I have ideas for a random joke too, i'll implement it later after the first working version of the program is up and ready. </br>
ProjectLog[1] - Completed the English version for the project. Still working on the languages supported by the pyjokes library. Will release it soon.</br>
ProjectLog[2] - Completed the project. The project is now available in all the languages supported by the pyjokes library. The joke is originally fetched in English and later translated into the chosen/desired language. Throughout the process of making the project, i faced a lot of bugs, for some reason after the completion of the project, the project would get stuck in the loop, and restart with the userResponse() function. Fixed that, and now the program works better than ever. All i need is some feedback for my project from people who actually know these languages, to see if the joke is still understandable since, i am fetching the joke in English and translating it into the desired language. Also for some unknown reason the "twister" category isn't working from their (pyjokes') side. I checked everything on my side, but couldn't find any problem in my code to cause that error.</br>
ProjectLog[3] - Added the "anotherOne" function to generate more jokes as a recursive function. Keeps generating more and more until the user denies it the future. </br>

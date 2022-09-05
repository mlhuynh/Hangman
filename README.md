# Hangman Readme File


<h3> Project Description <img src="https://cdn-icons-gif.flaticon.com/6454/6454112.gif" width=30px></h3>

<img align='right' src="https://user-images.githubusercontent.com/112219182/188354709-2ed09b6e-e7a1-4d08-bbfa-0c18e423e718.jpg" width=200px>  
<p align='justify'> This is a rudimentary, traditional game of Hangman. It was written in Python without the use of any APIs or libraries. Instead, the game relies on uploading an extensive list of words in a text file named "word.txt". From there, a word from the list is chosen at random for the player to guess. 
<br><br>
To play, just guess a letter by typing your guess on your keyboard. If you guess incorrectly 9 times, you lose. If you guess the word before that happens, you win. After you win or lose, you can restart the game by pressing any key on the keyboard.</p>

<h3> User Directions </h3>
<ol>
  <li>Download or save a copy of the "word.txt" file from this repository anywhere on your local computer or laptop</li>
    <ul>
      <li>No need to define the absolute pathway or location of the "word.txt" file in the code. The open() function is written to pull  the relative path.</li>
    </ul
  <li>At the start of the game, the number of letters that the secret word contains will be revealed.</li>
  <li>Players will be allowed one guess (i.e. letter) per round (with a total of 9 rounds)
    <ul>
      <li>The user should receive feedback immediately after each guess about whether their guess appears in the secret word.</li>
      <li>After each round, the partially guessed word so far will be displayed to the user, as well as letters that have not yet been guessed.
    </ul>
</ol>


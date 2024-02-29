# Dungeon crawler web
<hr>

# **DAY 00**    <h3> February 14, 2024 </h3>

The idea of ​​this repository is to develop a web application, so that the user can play a solo adventure based on the solo RPG Berdolock Fortress

##### **Observation: I will write step by step of process in English, as way to practice and lear the language**

## THE CUSTOMER
For this project, a fiction client needs a website where the person can play a solo RPG, but the application needs to be built only with HTML, CSS and Vanilla Javascript.
In the game the player has three possibilites:
  -Movement (section,meeting,treasure or trap)
  -Battle / damage (combat initiative,)
  -Escape (after thirty (30) rounds)

*REQUIREMENTS*
<ul>
  <li>-The player need to roller a dice;
</li>
  <li>-The enemy need to roller a dice and player need a see this result
</li>
</ul>

<hr>

# **DAY 01** 
  <h3>February 15, 2024</h3>
  
  ## The Adventure Start

  The first step was to create  a layout  to test aplication 

  ![Layout version 00, created for deploy test ](./imagens/layout_v00.png)

  You can view in [RPG SOLO](https://gabrielsabreu.github.io/rpg.solo/)

<hr>

# **DAYs 02, 03, 04 and 05**
  <h3>February 20, 22, 23 and 27, 2024</h3>
  
  ## Multiple number 1s in the dice

  During these days I worked on configuring the layout.
   First I started structuring the HTML, then I thought about version 00 of the layout based on message (screen) and interaction (data) areas, but I found it more interesting to add three displays for feedback to the player.
  These displays are:
   -Life (heart)
   -Attack (Sword)
   -Defense (shield)
They are repeated for the player's encounters inside the dungeon
   This idea generated layout version 01.
   <hr>

   ![Layout version 01](./imagens/layout_v01.png)


   After a few tries using the grid layout, I chose to use flexbox layout.
  The division  in divs resulted in the next estruture:

  ![layout thinking about the structure of divs and using flexbox](./imagens/layout_v01_Estruture.png)

   




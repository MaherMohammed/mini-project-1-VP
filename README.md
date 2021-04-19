# mini-project-1-VP
This project is to convert a json file from Scratch into pseudocode

- Using Python alongwith the JSON library we opened the json file which is extracted from a Scratch project.
- We parsed the blocks object inside the second filed in the targets array.
- We used the opcode to identify each block and the inputs to get any input used for the block
- We used the parent and next fields to identy the order of the actions and indentify the top and last actions

# Blocks used to generate the project.json file from Scratch
![image](https://user-images.githubusercontent.com/30608188/115257786-b7422680-a130-11eb-8826-7a38e05c470b.png)


# Set Of Blocks
We separated the blocks to multiple sets while parsing them:
- Motion
- Event
- Looks
- Forever
- If
- If Else
- Repeat Until
- Repeat and Wait
- Wait Until

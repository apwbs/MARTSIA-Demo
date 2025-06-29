# MARTSIA-Demo

## Wiki
For a detailed documentation and step-by-step tutorial to run this version locally, check out the [Wiki](https://github.com/apwbs/MARTSIA-Demo/wiki).

## Video presentation
Below we present a step-by-step video demonstrating the local execution of this version of MARTSIA.

[![Video](https://img.youtube.com/vi/RAcifWw1_B0/maxresdefault.jpg)](https://www.youtube.com/watch?v=RAcifWw1_B0)

## Pitch presentation and poster
For a pitch presentation showcased at the CAiSE Forum 2025, check out this SlideShare [link](https://www.slideshare.net/slideshow/kryston-et-al-martsia-in-2-3minutes-pptx/280989049).

You can also find the poster at the following SlideShare [link](https://www.slideshare.net/slideshow/kryston-et-al-martsia-poster-caise-forum-2025-pptx/280989458).

## This repository
In this repository you find several folders necessary to run the framework. 
1. In the *blockchain* folder, there are all the necessary data to connect to the blockchain. For example, the smart contract code in the *contracts* folder, the JavaScript code to deploy on-chain the smart contract in the *migrations* folder, and finally the *truffle-config.js* file to connect to the blockchain via Truffle.
2. the *databases* folder contains the SQL files to build the auxiliary relational tables we use in this prototypical implementation of our system to store temporary data (yellow pages, seeds, RSA private keys, etc.).
3. The *input_files* folder is the folder where to put the files to encrypt. You can use whatever folder you desire.
4. The *json_files* folder contains the files that specify the roles of the actors involved in the process and the access policies. You can use whatever folder you desire.
5. The *output_files* folder is the folder where decrypted files are saved. You can use whatever folder you desire.
6. In the *sh_files* folder you find all the sh files to use MARTSIA. These files simplify usage and hide complex steps, making MARTSIA more user-friendly for the end user.
7. The *src* folder contains the Python scripts that are run through the sh files. 

## MARTSIA main GitHub page
For more details about MARTSIA, refer to the [main MARTSIA GitHub page](https://github.com/apwbs/MARTSIA).

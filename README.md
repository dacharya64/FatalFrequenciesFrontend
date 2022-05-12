# Fatal Frequencies Visualization

See the latest build of the project at: https://www.devi-a.com/FatalFrequenciesFrontend

## About the project
This project was started as part of my work at the Expressive Intelligence Studio at the University of California, Santa Cruz. For the project, I was interested in exploring how we can use computational tools to help better visualize and provide suggestions for game masters of tabletop roleplaying games. This allows GMs to track what has happened in the game world, and uses knowledge of the current state (as well as a Prolog knowledge database) to provide suggestions for what can happen next.

This project uses the Fatal Frequencies scenario from the Gumshoe One-2-One system for this prototype. It features the characters, information, and clues from the game, as well as a sample of Prolog queries that could be useful to GMs. 

## database.prolog
The majority of the content from the module has been extracted and rewritten in Prolog. You can access and edit this file in order to see the information in the game, and to add new Prolog queries to the website. 

## Graphs
All graphs are rendered using Mermaid (https://mermaid-js.github.io/mermaid/#/). The initial starting graphs are preset based on the module's information, but can change based on input (for instance, nodes changing color when scenes are completed). The scene nodes are also clickable links. 

## Prolog queries
The GM suggestions screen features Prolog queries that pull out patterns of characters, scenes, and clues that match specific queries. While this includes some examples here, in order to add more, you will want to write the Prolog query in the ``database.prolog`` file and add the call to that query in the ``main.js`` file. 


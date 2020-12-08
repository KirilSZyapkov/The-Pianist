# The-Pianist

You are a pianist and you like to keep a list of your favorite piano pieces. Create a program, to help you organize it and add, change, remove pieces from it! 

On the first line of the standard input you will receive an integer n – the number of pieces that you will initially have. On the next n lines the pieces themselves will follow with their composer and key, separated by "|" in the following format: 

{piece}|{composer}|{key} 

Then, you will be receiving different commands, each on a new line, separated by "|", until the "Stop" command is given: 

Add|{piece}|{composer}|{key}  

You need to add the given piece with the information about it to the other pieces 

If the piece is already in the collection, print: 

"{piece} is already in the collection!" 

If the piece is not in the collection, print:  
"{piece} by {composer} in {key} added to the collection!" 

Remove|{piece} 

If the piece is in the collection, remove it and print: 

"Successfully removed {piece}!" 

If the piece is not in the collection, print: 

"Invalid operation! {piece} does not exist in the collection." 

ChangeKey|{piece}|{new key} 

If the piece is in the collection, change its key with the given one and print: 

"Changed the key of {piece} to {new key}!" 

If the piece is not in the collection, print: 

"Invalid operation! {piece} does not exist in the collection." 

Upon receiving the "Stop" command you need to print all pieces in your collection, sorted by their name and by the name of their composer in alphabetical order, in the following format: 
"{Piece} -> Composer: {composer}, Key: {key}"

This involves creating a knowledge base (stored as a text file) storing the rules of the wumpus world, i.e., what we know about pits, monsters, breeze, and stench. Next,we create an inference engine, that given a knowledge base and a statement determines if, based on the knowledge base, the statement is definitely true, definitely false, or of unknown truth value.


To run the program use the following command:

python check_true_false.py Wampus_rules.txt a.txt b.txt

The output will be shown on result.txt file.

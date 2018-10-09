function rollDice(numSides) {
  return Math.floor(Math.random() * numSides) + 1;
}


Dice Range	Function Call
4 (4-sided)	        rollDice(4)
6 (common 6-sided)	rollDice(6)
10	                rollDice(10)
20	                rollDice(20)
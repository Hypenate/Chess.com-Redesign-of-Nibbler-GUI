# Chess.com Redesign of Nibbler GUI
I remodel the Nibbler GUI to look and act like chess.com. However, Nibbler allows for higher depth, faster analyses and better engine. I use Stockfish 15.1. By selecting upper node limit for auto-eval you can run an analysis that will then show similar game review stats as chess.com does.

Here is the required Nibbler GUI https://github.com/rooklift/nibbler/releases.

For Stockfish (don't know if lc0 would work): https://stockfishchess.org/download/.

Then download code as zip and paste into Nibblers folder resources/app/ and replace.

The Graph is very accurate and can be trusted.

The implementation of when Brilliant Move/Great Move occur needs to be added.

The implementation for Best moves needs to be optimized, since right now everything is a best move if evaluation doesn't change (For example M5 -> M6 is 0% difference in eval since it is completly winning, however Chess.com wouldn't call that the best move since there is a faster mate).

For comparison a screenshot of the Nibbler GUI:

<img src="[https://i.imgur.com/ZWnhY9T.png](https://user-images.githubusercontent.com/23149790/222598033-5ed89b16-93b7-4fc1-a47f-4fa8b2d10a45.png)" width=50% height=50%>

And here the same game in Chess.com:
Game Review             |  Analysis
:-------------------------:|:-------------------------:
![jod3ZBP](https://user-images.githubusercontent.com/23149790/222598061-c2799192-8289-4cea-bf4a-872f36135c0f.png)  |  ![uybSqIu](https://user-images.githubusercontent.com/23149790/222598082-6810fa0d-4dc4-4f0e-bf6d-5592f4a09818.png)

Move List is the same, colors will be added.

Wether it was best move and alternative move like in chess.com will be added.

Graph needs optimisation.

GUI will be increased in size, maybe dynamic sizes.

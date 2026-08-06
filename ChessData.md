# This is a data set for my chess games and personal analysis.
[^note]: this is a Prompt File created and maintained by Boyo Labs, current version .9.1 BETA

[^contextual prompt]: This file is a Contextual Data Logic (CDL) framework -- the following contains pre loaded logic in the form of prompts for you (the LLM) to complete your task.

[^persona prompt]: You are a *bullet* chess analysis tool that considers the following chess data weighting time and position equally. You value heuristical play in bullet chess -- such as "trade queens" or "defeat a queen/bishop battery by moving B or G pawns" or "castle away from the attack" or "move central knights behind B or G pawns" or "push c or f pawn opposite of king." These moves aren't always right, but for the hippo, they are generally pretty good ideas.

[^contextual prompt]: I focus on using the hippopotomous defense (as both black and white) and sometimes (rarely -- when I remember to do it when my opponent does a fianchetto opening) the kings indian.

[^conditional prompt]: If and only if the user requests for an analysis of an annotated PGN they provide, analyze the game using the below game data and analysis to provide a positional and time -- weighted equally -- analysis in terms of centipawn loss.

[^conditional prompt]: If and only if the user requests general information from the dataset below, be sure to include centipawn loss weighted equally between position and time.

[^contextual prompt]: The following document requires you to read both the Data fields as well as Analysis fields and evaluate them separately

[^note]: This analysis is different from standard analyses in that it focuses on my *heuristical* style play. Rather than looking for exact good moves, I play with standard moves that should be made in a similar position. The analysis should reflect this.

## 1+0 played as white (win) 
### Game 1 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/IIKXdWhq"]
[Date "2025.10.22"]
[White "boyo1991"]
[Black "PSIXyz"]
[Result "1-0"]
[GameId "IIKXdWhq"]
[UTCDate "2025.10.22"]
[UTCTime "22:13:52"]
[WhiteElo "1445"]
[BlackElo "1420"]
[WhiteRatingDiff "+6"]
[BlackRatingDiff "-6"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... c5 { [%clk 0:01:00] } 2. Nd2 { [%clk 0:01:00] } 2... Nc6 { [%clk 0:00:59] } 3. e3 { [%clk 0:01:00] } 3... e6 { [%clk 0:00:59] } 4. a3 { [%clk 0:01:00] } 4... d6 { [%clk 0:00:59] } 5. Ne2 { [%clk 0:00:59] } 5... g6 { [%clk 0:00:59] } 6. g3 { [%clk 0:00:59] } 6... Bg7 { [%clk 0:00:59] } 7. Bg2 { [%clk 0:00:58] } 7... Nge7 { [%clk 0:00:59] } 8. h3 { [%clk 0:00:58] } 8... O-O { [%clk 0:00:59] } 9. b3 { [%clk 0:00:57] } 9... d5 { [%clk 0:00:58] } 10. Bb2 { [%clk 0:00:57] } 10... Bxb2 { [%clk 0:00:57] } 11. Rb1 { [%clk 0:00:57] } 11... Bg7 { [%clk 0:00:56] } 12. c4 { [%clk 0:00:55] } 12... dxc4 { [%clk 0:00:55] } 13. dxc4 { [%clk 0:00:54] } 13... b6 { [%clk 0:00:50] } 14. O-O { [%clk 0:00:53] } 14... Bb7 { [%clk 0:00:50] } 15. Nf3 { [%clk 0:00:51] } 15... Ne5 { [%clk 0:00:48] } 16. Qxd8 { [%clk 0:00:50] } 16... Rfxd8 { [%clk 0:00:46] } 17. Rbd1 { [%clk 0:00:49] } 17... Nxf3+ { [%clk 0:00:44] } 18. Bxf3 { [%clk 0:00:48] } 18... Bxf3 { [%clk 0:00:43] } 19. Kh2 { [%clk 0:00:45] } 19... Bxe2 { [%clk 0:00:42] } 20. Rde1 { [%clk 0:00:43] } 20... Bxf1 { [%clk 0:00:40] } 21. Rxf1 { [%clk 0:00:43] } 21... Rd2 { [%clk 0:00:39] } 22. Kg1 { [%clk 0:00:42] } 22... Ra2 { [%clk 0:00:36] } 23. f4 { [%clk 0:00:41] } 23... Rxa3 { [%clk 0:00:35] } 24. Rf2 { [%clk 0:00:40] } 24... Rxb3 { [%clk 0:00:34] } 25. Kg2 { [%clk 0:00:40] } 25... Rxe3 { [%clk 0:00:33] } 26. g4 { [%clk 0:00:37] } 26... Bd4 { [%clk 0:00:30] } 27. Rf1 { [%clk 0:00:34] } 27... Rc3 { [%clk 0:00:25] } 28. Rd1 { [%clk 0:00:31] } 28... Rxc4 { [%clk 0:00:23] } 29. Kg3 { [%clk 0:00:30] } 29... Rd8 { [%clk 0:00:20] } 30. Rh1 { [%clk 0:00:28] } 30... Rc2 { [%clk 0:00:18] } 31. h4 { [%clk 0:00:27] } 31... Rc3+ { [%clk 0:00:16] } 32. Kg2 { [%clk 0:00:25] } 32... Be3 { [%clk 0:00:13] } 33. Kf3 { [%clk 0:00:23] } 33... Bc1+ { [%clk 0:00:09] } 34. Ke4 { [%clk 0:00:22] } 34... Bb2 { [%clk 0:00:08] } 35. Ke5 { [%clk 0:00:20] } 35... Rd4 { [%clk 0:00:08] } 36. Kf6 { [%clk 0:00:19] } 36... Rxf4+ { [%clk 0:00:06] } 37. Kg5 { [%clk 0:00:18] } 37... f6+ { [%clk 0:00:04] } 38. Kh6 { [%clk 0:00:16] } 38... Rxg4 { [%clk 0:00:03] } 39. h5 { [%clk 0:00:14] } 39... gxh5 { [%clk 0:00:01] } 40. Kxh5 { [%clk 0:00:13] } 40... Rg6 { [%clk 0:00:00] } 41. Kh4 { [%clk 0:00:12] } { White wins on time. } 1-0

### Analysis:
#### I was able to win on time because all hope was lost, and the windmill my opponent had going was killing their time.
#### I gave up on trying to win a better position and instead ran with my king
#### I had a terrible position in the end

---

## 1+0 played as black (loss)
### Game 2 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/QqDD27Ha"]
[Date "2025.10.23"]
[White "PAWGErrr"]
[Black "boyo1991"]
[Result "1-0"]
[GameId "QqDD27Ha"]
[UTCDate "2025.10.23"]
[UTCTime "00:52:06"]
[WhiteElo "1529"]
[BlackElo "1451"]
[WhiteRatingDiff "+4"]
[BlackRatingDiff "-5"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "C00"]
[Opening "French Defense: Normal Variation"]
[Termination "Normal"]
[Annotator "lichess.org"]

1. e4 { [%clk 0:01:00] } 1... e6 { [%clk 0:01:00] } 2. d4 { [%clk 0:00:59] } { C00 French Defense: Normal Variation } 2... Ne7 { [%clk 0:01:00] } 3. e5 { [%clk 0:00:58] } 3... b6 { [%clk 0:00:59] } 4. c3 { [%clk 0:00:57] } 4... Bb7 { [%clk 0:00:58] } 5. Nf3 { [%clk 0:00:56] } 5... Ng8 { [%clk 0:00:57] } 6. g3 { [%clk 0:00:55] } 6... Nc6 { [%clk 0:00:55] } 7. Bg2 { [%clk 0:00:55] } 7... h6 { [%clk 0:00:54] } 8. O-O { [%clk 0:00:54] } 8... g6 { [%clk 0:00:53] } 9. h3 { [%clk 0:00:53] } 9... Bg7 { [%clk 0:00:53] } 10. Bf4 { [%clk 0:00:50] } 10... Nge7 { [%clk 0:00:52] } 11. Nbd2 { [%clk 0:00:49] } 11... O-O { [%clk 0:00:52] } 12. Ne4 { [%clk 0:00:49] } 12... b5 { [%clk 0:00:51] } 13. Nc5 { [%clk 0:00:47] } 13... Rb8 { [%clk 0:00:49] } 14. Nxb7 { [%clk 0:00:47] } 14... Rxb7 { [%clk 0:00:47] } 15. Qd2 { [%clk 0:00:46] } 15... a6 { [%clk 0:00:45] } 16. Bxh6 { [%clk 0:00:45] } 16... Bxh6 { [%clk 0:00:44] } 17. Qxh6 { [%clk 0:00:45] } 17... Nf5 { [%clk 0:00:41] } 18. Qf4 { [%clk 0:00:40] } 18... Qc8 { [%clk 0:00:37] } 19. g4 { [%clk 0:00:40] } 19... Nd6 { [%clk 0:00:34] } 20. Qh6 { [%clk 0:00:38] } 20... Ne8 { [%clk 0:00:32] } 21. Ng5 { [%clk 0:00:37] } 21... Ng7 { [%clk 0:00:31] } 22. Qh7# { [%clk 0:00:36] } { White wins by checkmate. } 1-0

### Analysis:
#### I fed into the bait of the bishop queen battery which allowed for an easy checkmate by my opponent.
#### I held my position but got distracted
#### I felt the threat but ignored it
#### I was going for my heuristical play, but the aggressive moves took me out of my comfort zone

---

## 1+0 played as white (win)
### Game 3 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/XoXWgmvM"]
[Date "2025.10.23"]
[White "boyo1991"]
[Black "enyimmiri3442"]
[Result "1-0"]
[GameId "XoXWgmvM"]
[UTCDate "2025.10.23"]
[UTCTime "02:23:17"]
[WhiteElo "1446"]
[BlackElo "1444"]
[WhiteRatingDiff "+6"]
[BlackRatingDiff "-5"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]


1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... g6 { [%clk 0:01:00] } 2. Nd2 { [%clk 0:01:00] } 2... Bg7 { [%clk 0:00:59] } 3. e3 { [%clk 0:01:00] } 3... e6 { [%clk 0:00:59] } 4. Ne2 { [%clk 0:01:00] } 4... d6 { [%clk 0:00:59] } 5. g3 { [%clk 0:00:59] } 5... a6 { [%clk 0:00:58] } 6. Bg2 { [%clk 0:00:59] } 6... Ra7 { [%clk 0:00:58] } 7. h3 { [%clk 0:00:58] } 7... b6 { [%clk 0:00:57] } 8. O-O { [%clk 0:00:57] } 8... Bb7 { [%clk 0:00:57] } 9. c3 { [%clk 0:00:56] } 9... Bxg2 { [%clk 0:00:53] } 10. Kxg2 { [%clk 0:00:55] } 10... h6 { [%clk 0:00:53] } 11. Rb1 { [%clk 0:00:54] } 11... Nd7 { [%clk 0:00:52] } 12. b3 { [%clk 0:00:54] } 12... Qe7 { [%clk 0:00:52] } 13. Bb2 { [%clk 0:00:53] } 13... Kd8 { [%clk 0:00:51] } 14. d4 { [%clk 0:00:52] } 14... Kc8 { [%clk 0:00:50] } 15. g4 { [%clk 0:00:52] } 15... Kb8 { [%clk 0:00:49] } 16. Ng3 { [%clk 0:00:52] } 16... Ka8 { [%clk 0:00:48] } 17. h4 { [%clk 0:00:51] } 17... Rb7 { [%clk 0:00:47] } 18. h5 { [%clk 0:00:50] } 18... gxh5 { [%clk 0:00:45] } 19. gxh5 { [%clk 0:00:50] } 19... Ngf6 { [%clk 0:00:43] } 20. f4 { [%clk 0:00:48] } 20... Rg8 { [%clk 0:00:41] } 21. Rf3 { [%clk 0:00:47] } 21... Ng4 { [%clk 0:00:38] } 22. Kg1 { [%clk 0:00:43] } 22... Rbb8 { [%clk 0:00:37] } 23. Kf1 { [%clk 0:00:42] } 23... Nh2+ { [%clk 0:00:35] } 24. Ke2 { [%clk 0:00:40] } 24... Nxf3 { [%clk 0:00:35] } 25. Kxf3 { [%clk 0:00:40] } 25... Qh4 { [%clk 0:00:31] } 26. Ke2 { [%clk 0:00:38] } 26... Qxg3 { [%clk 0:00:28] } 27. Kd3 { [%clk 0:00:38] } 27... Bxd4 { [%clk 0:00:27] } 28. Kxd4 { [%clk 0:00:37] } 28... e5+ { [%clk 0:00:24] } 29. Kd3 { [%clk 0:00:36] } 29... e4+ { [%clk 0:00:21] } 30. Kc2 { [%clk 0:00:35] } 30... d5 { [%clk 0:00:20] } 31. Qf1 { [%clk 0:00:33] } 31... Nc5 { [%clk 0:00:18] } 32. Qe1 { [%clk 0:00:32] } 32... Nd3 { [%clk 0:00:17] } 33. Qxg3 { [%clk 0:00:30] } 33... Rxg3 { [%clk 0:00:15] } 34. Ba3 { [%clk 0:00:27] } 34... Rxe3 { [%clk 0:00:13] } 35. Nf1 { [%clk 0:00:25] } 35... Rf3 { [%clk 0:00:10] } 36. Nh2 { [%clk 0:00:23] } 36... Rf2+ { [%clk 0:00:09] } 37. Kd1 { [%clk 0:00:19] } 37... Rxh2 { [%clk 0:00:09] } 38. Rb2 { [%clk 0:00:17] } 38... Rh1+ { [%clk 0:00:08] } 39. Kc2 { [%clk 0:00:15] } 39... Rh2+ { [%clk 0:00:07] } 40. Kb1 { [%clk 0:00:14] } 40... Rxb2+ { [%clk 0:00:06] } 41. Bxb2 { [%clk 0:00:14] } 41... Rg8 { [%clk 0:00:04] } 42. Bc1 { [%clk 0:00:12] } 42... Rg1 { [%clk 0:00:04] } 43. Kc2 { [%clk 0:00:11] } 43... Rxc1+ { [%clk 0:00:04] } 44. Kd2 { [%clk 0:00:10] } 44... Rh1 { [%clk 0:00:02] } 45. Ke3 { [%clk 0:00:09] } 45... Rh3+ { [%clk 0:00:01] } 46. Kd4 { [%clk 0:00:09] } { White wins on time. } 1-0

### Analysis:
#### good time management
#### my opponent had a superior position
#### I dealt with a fianchetto poorly
#### I ignored threats in liue of time after a mistake which was fruitful since they decided to waste time windmilling my remaining pieces
#### I was able to start making standard heuristical plays, but they got countered pretty quickly

---

## 1+0 played as black (win)
### Game 4 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/bRHTMniD"]
[Date "2025.10.23"]
[White "Beren_23"]
[Black "boyo1991"]
[Result "0-1"]
[GameId "bRHTMniD"]
[UTCDate "2025.10.23"]
[UTCTime "17:02:06"]
[WhiteElo "1449"]
[BlackElo "1452"]
[WhiteRatingDiff "-6"]
[BlackRatingDiff "+6"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "C00"]
[Opening "French Defense: Knight Variation"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. e4 { [%clk 0:01:00] } 1... e6 { [%clk 0:01:00] } 2. Nf3 { [%clk 0:01:00] } { C00 French Defense: Knight Variation } 2... Ne7 { [%clk 0:01:00] } 3. d4 { [%clk 0:00:59] } 3... h6 { [%clk 0:01:00] } 4. c4 { [%clk 0:00:58] } 4... d6 { [%clk 0:00:59] } 5. Bd3 { [%clk 0:00:57] } 5... Nd7 { [%clk 0:00:59] } 6. Nc3 { [%clk 0:00:57] } 6... a6 { [%clk 0:00:58] } 7. O-O { [%clk 0:00:56] } 7... g6 { [%clk 0:00:58] } 8. Re1 { [%clk 0:00:55] } 8... Bg7 { [%clk 0:00:57] } 9. h3 { [%clk 0:00:55] } 9... b6 { [%clk 0:00:57] } 10. Rb1 { [%clk 0:00:53] } 10... Bb7 { [%clk 0:00:57] } 11. b3 { [%clk 0:00:52] } 11... O-O { [%clk 0:00:56] } 12. d5 { [%clk 0:00:51] } 12... e5 { [%clk 0:00:55] } 13. Ne2 { [%clk 0:00:48] } 13... g5 { [%clk 0:00:54] } 14. Bc2 { [%clk 0:00:47] } 14... Ng6 { [%clk 0:00:54] } 15. Nc3 { [%clk 0:00:46] } 15... a5 { [%clk 0:00:53] } 16. Na4 { [%clk 0:00:44] } 16... Ba6 { [%clk 0:00:51] } 17. Nb2 { [%clk 0:00:44] } 17... a4 { [%clk 0:00:50] } 18. b4 { [%clk 0:00:42] } 18... a3 { [%clk 0:00:49] } 19. Nd3 { [%clk 0:00:37] } 19... Bb7 { [%clk 0:00:47] } 20. Bb3 { [%clk 0:00:34] } 20... Qb8 { [%clk 0:00:46] } 21. c5 { [%clk 0:00:31] } 21... bxc5 { [%clk 0:00:45] } 22. bxc5 { [%clk 0:00:31] } 22... Qa7 { [%clk 0:00:41] } 23. c6 { [%clk 0:00:30] } 23... Ba6 { [%clk 0:00:40] } 24. cxd7 { [%clk 0:00:27] } 24... Bxd3 { [%clk 0:00:39] } 25. Qxd3 { [%clk 0:00:25] } 25... Rfd8 { [%clk 0:00:37] } 26. Be3 { [%clk 0:00:25] } 26... Rxd7 { [%clk 0:00:36] } 27. Bxa7 { [%clk 0:00:23] } 27... Rxa7 { [%clk 0:00:36] } 28. Rec1 { [%clk 0:00:23] } 28... Ra8 { [%clk 0:00:35] } 29. Rc6 { [%clk 0:00:21] } 29... Rad8 { [%clk 0:00:35] } 30. Rbc1 { [%clk 0:00:21] } 30... Rc8 { [%clk 0:00:34] } 31. Qb5 { [%clk 0:00:20] } 31... Bf8 { [%clk 0:00:33] } 32. Qb7 { [%clk 0:00:19] } 32... Rcd8 { [%clk 0:00:30] } 33. Rxc7 { [%clk 0:00:18] } 33... Be7 { [%clk 0:00:28] } 34. Rxd7 { [%clk 0:00:17] } 34... Rf8 { [%clk 0:00:26] } 35. Rc8 { [%clk 0:00:14] } 35... Kg7 { [%clk 0:00:25] } 36. Rxf8 { [%clk 0:00:12] } 36... Kxf8 { [%clk 0:00:24] } 37. Qc8+ { [%clk 0:00:07] } 37... Kg7 { [%clk 0:00:23] } 38. Qc7 { [%clk 0:00:03] } 38... h5 { [%clk 0:00:22] } 39. Rxe7 { [%clk 0:00:02] } 39... Nxe7 { [%clk 0:00:22] } 40. Qxe7 { [%clk 0:00:01] } 40... Kg6 { [%clk 0:00:20] } 41. Qxd6+ { [%clk 0:00:01] } 41... Kg7 { [%clk 0:00:19] } 42. Qxe5+ { [%clk 0:00:01] } 42... Kf8 { [%clk 0:00:19] } 43. Qxg5 { [%clk 0:00:00] } 43... Ke8 { [%clk 0:00:17] } { Black wins on time. } 0-1

### Analysis:
#### good steady opening -- well protected no quick blunders
#### Held an equal position for a while
#### good time management
#### still had worse position at the end, but this is still okay as long as my middle game was stable and winning on the clock.
#### I did blunder my queen away, which was the turning point positionally.
#### I was able to make standard heuristical plays -- the queen blunder is what really flipped the tides

---

## 1+0 played as white (win)
### Game 5 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/sK2gQPjl"]
[Date "2025.10.23"]
[White "boyo1991"]
[Black "carpetis"]
[Result "1-0"]
[GameId "sK2gQPjl"]
[UTCDate "2025.10.23"]
[UTCTime "22:32:00"]
[WhiteElo "1458"]
[BlackElo "1505"]
[WhiteRatingDiff "+6"]
[BlackRatingDiff "-6"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Normal"]
[Annotator "lichess.org"]

1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... d5 { [%clk 0:01:00] } 2. Nd2 { [%clk 0:01:00] } 2... f6 { [%clk 0:00:59] } 3. e3 { [%clk 0:00:59] } 3... c5 { [%clk 0:00:58] } 4. Ne2 { [%clk 0:00:59] } 4... e5 { [%clk 0:00:57] } 5. b3 { [%clk 0:00:59] } 5... d4 { [%clk 0:00:56] } 6. e4 { [%clk 0:00:58] } 6... g6 { [%clk 0:00:54] } 7. Bb2 { [%clk 0:00:57] } 7... f5 { [%clk 0:00:53] } 8. a3 { [%clk 0:00:57] } 8... fxe4 { [%clk 0:00:52] } 9. Nxe4 { [%clk 0:00:57] } 9... Bf5 { [%clk 0:00:51] } 10. f3 { [%clk 0:00:55] } 10... Bxe4 { [%clk 0:00:50] } 11. fxe4 { [%clk 0:00:54] } 11... Nc6 { [%clk 0:00:50] } 12. g3 { [%clk 0:00:52] } 12... Nf6 { [%clk 0:00:50] } 13. Bg2 { [%clk 0:00:52] } 13... Bd6 { [%clk 0:00:49] } 14. h3 { [%clk 0:00:51] } 14... O-O { [%clk 0:00:49] } 15. O-O { [%clk 0:00:51] } 15... Be7 { [%clk 0:00:48] } 16. g4 { [%clk 0:00:50] } 16... Qd7 { [%clk 0:00:46] } 17. Ng3 { [%clk 0:00:47] } 17... Bd8 { [%clk 0:00:42] } 18. c4 { [%clk 0:00:45] } 18... Ne7 { [%clk 0:00:41] } 19. Bc1 { [%clk 0:00:42] } 19... b6 { [%clk 0:00:39] } 20. Bg5 { [%clk 0:00:42] } 20... Bc7 { [%clk 0:00:36] } 21. Bxf6 { [%clk 0:00:40] } 21... Rxf6 { [%clk 0:00:35] } 22. Rxf6 { [%clk 0:00:39] } 22... Kg7 { [%clk 0:00:32] } 23. Qf1 { [%clk 0:00:38] } 23... Nc6 { [%clk 0:00:26] } 24. Nh5+ { [%clk 0:00:34] } 24... gxh5 { [%clk 0:00:24] } 25. gxh5 { [%clk 0:00:31] } 25... h6 { [%clk 0:00:23] } 26. Bh1 { [%clk 0:00:30] } 26... Qe8 { [%clk 0:00:18] } 27. Qg2+ { [%clk 0:00:29] } 27... Kh8 { [%clk 0:00:16] } 28. Rxh6# { [%clk 0:00:28] } { White wins by checkmate. } 1-0

## Analysis:
### I thought it was strange how my opponent kept pushing pawns -- it gave them a poor position.
### I did make a bit of a mistake in my pawn structure, I don't think it was too bad because I forced it into a more even trade.
### My time management seemed good, winning on time as well as checkmate.

---

## 1+0 played as white (win)
### Game 6 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/Ro4Bc2mb"]
[Date "2025.10.24"]
[White "boyo1991"]
[Black "ghost77377"]
[Result "1-0"]
[GameId "Ro4Bc2mb"]
[UTCDate "2025.10.24"]
[UTCTime "01:13:50"]
[WhiteElo "1464"]
[BlackElo "1430"]
[WhiteRatingDiff "+6"]
[BlackRatingDiff "-10"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... Nf6 { [%clk 0:01:00] } 2. Nd2 { [%clk 0:01:00] } 2... g6 { [%clk 0:01:00] } 3. h3 { [%clk 0:01:00] } 3... Bg7 { [%clk 0:00:59] } 4. e3 { [%clk 0:00:59] } 4... O-O { [%clk 0:00:59] } 5. Ne2 { [%clk 0:00:59] } 5... c6 { [%clk 0:00:58] } 6. g3 { [%clk 0:00:58] } 6... b6 { [%clk 0:00:58] } 7. b3 { [%clk 0:00:58] } 7... Bb7 { [%clk 0:00:58] } 8. Bb2 { [%clk 0:00:57] } 8... d6 { [%clk 0:00:57] } 9. Rb1 { [%clk 0:00:57] } 9... c5 { [%clk 0:00:57] } 10. Bg2 { [%clk 0:00:56] } 10... Nc6 { [%clk 0:00:56] } 11. O-O { [%clk 0:00:55] } 11... Nb4 { [%clk 0:00:54] } 12. c4 { [%clk 0:00:53] } 12... Bxg2 { [%clk 0:00:53] } 13. Kxg2 { [%clk 0:00:52] } 13... Qb8 { [%clk 0:00:51] } 14. Kh2 { [%clk 0:00:51] } 14... Qb7 { [%clk 0:00:48] } 15. e4 { [%clk 0:00:50] } 15... e6 { [%clk 0:00:45] } 16. g4 { [%clk 0:00:49] } 16... Qd7 { [%clk 0:00:43] } 17. f3 { [%clk 0:00:48] } 17... e5 { [%clk 0:00:43] } 18. Ng3 { [%clk 0:00:47] } 18... Bh6 { [%clk 0:00:41] } 19. Qe1 { [%clk 0:00:45] } 19... Nxd3 { [%clk 0:00:38] } 20. Qd1 { [%clk 0:00:43] } 20... Nxb2 { [%clk 0:00:35] } 21. Rxb2 { [%clk 0:00:39] } 21... Qc6 { [%clk 0:00:33] } 22. Qe2 { [%clk 0:00:37] } 22... Rfe8 { [%clk 0:00:32] } 23. Qf2 { [%clk 0:00:36] } 23... Qc7 { [%clk 0:00:27] } 24. Rbb1 { [%clk 0:00:36] } 24... Rad8 { [%clk 0:00:27] } 25. Rbd1 { [%clk 0:00:35] } 25... d5 { [%clk 0:00:26] } 26. Nb1 { [%clk 0:00:33] } 26... dxc4 { [%clk 0:00:25] } 27. bxc4 { [%clk 0:00:31] } 27... Rxd1 { [%clk 0:00:24] } 28. Rxd1 { [%clk 0:00:30] } 28... Rd8 { [%clk 0:00:24] } 29. Nc3 { [%clk 0:00:27] } 29... Rxd1 { [%clk 0:00:22] } 30. Nxd1 { [%clk 0:00:27] } 30... a6 { [%clk 0:00:21] } 31. Qg2 { [%clk 0:00:27] } 31... Qc6 { [%clk 0:00:20] } 32. Nf2 { [%clk 0:00:26] } 32... Be3 { [%clk 0:00:19] } 33. Qf1 { [%clk 0:00:25] } 33... Qa4 { [%clk 0:00:18] } 34. Ne2 { [%clk 0:00:22] } 34... Qxa2 { [%clk 0:00:16] } 35. Nd1 { [%clk 0:00:21] } 35... Qd2 { [%clk 0:00:13] } 36. Nxe3 { [%clk 0:00:19] } 36... Qxe3 { [%clk 0:00:12] } 37. Qe1 { [%clk 0:00:18] } 37... Nd7 { [%clk 0:00:09] } 38. Qh1 { [%clk 0:00:17] } 38... Qd2 { [%clk 0:00:08] } 39. Qf1 { [%clk 0:00:15] } 39... Qc2 { [%clk 0:00:07] } 40. Kg2 { [%clk 0:00:14] } 40... Qd2 { [%clk 0:00:06] } 41. Kf2 { [%clk 0:00:13] } 41... b5 { [%clk 0:00:06] } 42. Qe1 { [%clk 0:00:13] } 42... bxc4 { [%clk 0:00:05] } 43. Qxd2 { [%clk 0:00:11] } 43... c3 { [%clk 0:00:04] } 44. Qxd7 { [%clk 0:00:08] } 44... a5 { [%clk 0:00:04] } 45. Qd8+ { [%clk 0:00:08] } 45... Kg7 { [%clk 0:00:04] } 46. Nf4 { [%clk 0:00:07] } 46... a4 { [%clk 0:00:04] } 47. Nd5 { [%clk 0:00:05] } 47... c2 { [%clk 0:00:04] } 48. Ne7 { [%clk 0:00:05] } 48... c1=Q { [%clk 0:00:03] } 49. Qg8+ { [%clk 0:00:05] } 49... Kf6 { [%clk 0:00:02] } 50. Nd5+ { [%clk 0:00:03] } 50... Kg5 { [%clk 0:00:01] } 51. Qd8+ { [%clk 0:00:01] } { White wins on time. } 1-0

### Analysis:
#### I was playing well, but I traded a lot and the time became a real problem
#### I had a misclick which didn't result in a loss, obviously, but it did kill a bit of my clock
#### I ended with the better position, but it was definitely a chaotic game and could have gone either way

---

## 1+0 played as white (win)
### Game 7 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/C3VDqUnk"]
[Date "2025.10.24"]
[White "boyo1991"]
[Black "Chessvi31"]
[Result "1-0"]
[GameId "C3VDqUnk"]
[UTCDate "2025.10.24"]
[UTCTime "18:40:11"]
[WhiteElo "1470"]
[BlackElo "1437"]
[WhiteRatingDiff "+5"]
[BlackRatingDiff "-5"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Normal"]
[Annotator "lichess.org"]

1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... d6 { [%clk 0:01:00] } 2. Nd2 { [%clk 0:01:00] } 2... g6 { [%clk 0:00:59] } 3. e3 { [%clk 0:01:00] } 3... Bg7 { [%clk 0:00:59] } 4. Ne2 { [%clk 0:01:00] } 4... Nf6 { [%clk 0:00:58] } 5. g3 { [%clk 0:01:00] } 5... O-O { [%clk 0:00:57] } 6. h3 { [%clk 0:00:59] } 6... e5 { [%clk 0:00:57] } 7. b3 { [%clk 0:00:58] } 7... Be6 { [%clk 0:00:56] } 8. Bb2 { [%clk 0:00:58] } 8... Nc6 { [%clk 0:00:55] } 9. a3 { [%clk 0:00:57] } 9... Na5 { [%clk 0:00:54] } 10. Rb1 { [%clk 0:00:55] } 10... c5 { [%clk 0:00:53] } 11. Bg2 { [%clk 0:00:55] } 11... Rb8 { [%clk 0:00:47] } 12. O-O { [%clk 0:00:54] } 12... b5 { [%clk 0:00:46] } 13. c4 { [%clk 0:00:54] } 13... bxc4 { [%clk 0:00:44] } 14. dxc4 { [%clk 0:00:53] } 14... Nxc4 { [%clk 0:00:43] } 15. Nxc4 { [%clk 0:00:52] } 15... Bxc4 { [%clk 0:00:41] } 16. bxc4 { [%clk 0:00:52] } 16... Qa5 { [%clk 0:00:39] } 17. Qc2 { [%clk 0:00:49] } 17... Nd7 { [%clk 0:00:36] } 18. Bc3 { [%clk 0:00:46] } 18... f5 { [%clk 0:00:35] } 19. Bxa5 { [%clk 0:00:45] } 19... Rxb1 { [%clk 0:00:34] } 20. Qxb1 { [%clk 0:00:44] } 20... Rb8 { [%clk 0:00:31] } 21. Qc1 { [%clk 0:00:41] } 21... Rb3 { [%clk 0:00:28] } 22. Nc3 { [%clk 0:00:40] } 22... e4 { [%clk 0:00:27] } 23. Nd5 { [%clk 0:00:37] } 23... Nf6 { [%clk 0:00:23] } 24. Ne7+ { [%clk 0:00:35] } 24... Kf7 { [%clk 0:00:21] } 25. Qc2 { [%clk 0:00:33] } 25... Rb2 { [%clk 0:00:15] } 26. Qxb2 { [%clk 0:00:31] } 26... Ng4 { [%clk 0:00:14] } 27. Qb7 { [%clk 0:00:30] } 27... Nxf2 { [%clk 0:00:10] } 28. Nxg6+ { [%clk 0:00:26] } { Black resigns. } 1-0

### Analysis:
#### while I had good use of time, my opponent blundered their queen and I spotted it
#### once I had a better position, I really wasn't exactly sure what to do with it -- there didn't seem to be many tactical motifs

---

## 1+0 played as black (loss)
### Game 8 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/iAsu00ay"]
[Date "2025.10.24"]
[White "emdadhavaii"]
[Black "boyo1991"]
[Result "1-0"]
[GameId "iAsu00ay"]
[UTCDate "2025.10.24"]
[UTCTime "22:26:19"]
[WhiteElo "1589"]
[BlackElo "1475"]
[WhiteRatingDiff "+4"]
[BlackRatingDiff "-4"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Saragossa Opening"]
[Termination "Normal"]
[Annotator "lichess.org"]

1. c3 { [%clk 0:01:00] } { A00 Saragossa Opening } 1... e6 { [%clk 0:01:00] } 2. Qb3 { [%clk 0:01:00] } 2... Ne7 { [%clk 0:01:00] } 3. Nf3 { [%clk 0:00:59] } 3... d6 { [%clk 0:01:00] } 4. h4 { [%clk 0:00:58] } 4... h6 { [%clk 0:00:59] } 5. c4 { [%clk 0:00:57] } 5... Nd7 { [%clk 0:00:59] } 6. e4 { [%clk 0:00:56] } 6... g6 { [%clk 0:00:58] } 7. c5 { [%clk 0:00:55] } 7... Bg7 { [%clk 0:00:58] } 8. g4 { [%clk 0:00:53] } 8... d5 { [%clk 0:00:56] } 9. g5 { [%clk 0:00:51] } 9... h5 { [%clk 0:00:52] } 10. exd5 { [%clk 0:00:49] } 10... Nxd5 { [%clk 0:00:51] } 11. Bc4 { [%clk 0:00:48] } 11... c6 { [%clk 0:00:49] } 12. Bxd5 { [%clk 0:00:46] } 12... cxd5 { [%clk 0:00:48] } 13. O-O { [%clk 0:00:46] } 13... b6 { [%clk 0:00:43] } 14. c6 { [%clk 0:00:42] } 14... Nc5 { [%clk 0:00:42] } 15. Qc2 { [%clk 0:00:40] } 15... Qd6 { [%clk 0:00:39] } 16. b4 { [%clk 0:00:39] } 16... Na4 { [%clk 0:00:36] } 17. Qxa4 { [%clk 0:00:37] } 17... Qxc6 { [%clk 0:00:33] } 18. Qxc6+ { [%clk 0:00:35] } 18... Ke7 { [%clk 0:00:30] } 19. Qxa8 { [%clk 0:00:34] } 19... Bd7 { [%clk 0:00:28] } 20. Qxa7 { [%clk 0:00:34] } 20... Ke8 { [%clk 0:00:26] } 21. Qb8+ { [%clk 0:00:31] } 21... Ke7 { [%clk 0:00:24] } 22. Qxb6 { [%clk 0:00:30] } 22... Rd8 { [%clk 0:00:21] } 23. a4 { [%clk 0:00:28] } 23... Ke8 { [%clk 0:00:20] } 24. a5 { [%clk 0:00:26] } 24... e5 { [%clk 0:00:20] } 25. a6 { [%clk 0:00:25] } 25... Ra8 { [%clk 0:00:19] } 26. Na3 { [%clk 0:00:23] } 26... Ke7 { [%clk 0:00:16] } 27. Nb5 { [%clk 0:00:21] } 27... Bxb5 { [%clk 0:00:14] } 28. Qxb5 { [%clk 0:00:20] } 28... Ke6 { [%clk 0:00:13] } 29. Qc6+ { [%clk 0:00:19] } 29... Kf5 { [%clk 0:00:12] } 30. Qxa8 { [%clk 0:00:19] } 30... Kg4 { [%clk 0:00:10] } 31. Qc8+ { [%clk 0:00:18] } { Black resigns. } 1-0

### Analysis:
#### I was incredibly distracted this game (annoyingly so) and playing against a strong opponent.
#### I was wasting time on poor moves
#### this is a good instructional game to remember to play without distractions.

---

## 1+0 played as white (win)

### Game 9 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/gXDIzHMt"]
[Date "2025.10.25"]
[White "boyo1991"]
[Black "baqueta2b"]
[Result "1-0"]
[GameId "gXDIzHMt"]
[UTCDate "2025.10.25"]
[UTCTime "15:12:26"]
[WhiteElo "1471"]
[BlackElo "1512"]
[WhiteRatingDiff "+6"]
[BlackRatingDiff "-7"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... e6 { [%clk 0:01:00] } 2. Nd2 { [%clk 0:01:00] } 2... Nf6 { [%clk 0:00:59] } 3. e3 { [%clk 0:01:00] } 3... d5 { [%clk 0:00:58] } 4. h3 { [%clk 0:01:00] } 4... b5 { [%clk 0:00:54] } 5. Ne2 { [%clk 0:00:59] } 5... a6 { [%clk 0:00:53] } 6. a3 { [%clk 0:00:59] } 6... Nbd7 { [%clk 0:00:51] } 7. b3 { [%clk 0:00:58] } 7... Nb6 { [%clk 0:00:50] } 8. Bb2 { [%clk 0:00:57] } 8... Bd6 { [%clk 0:00:47] } 9. g3 { [%clk 0:00:56] } 9... Nfd7 { [%clk 0:00:46] } 10. Bg2 { [%clk 0:00:56] } 10... h5 { [%clk 0:00:43] } 11. c4 { [%clk 0:00:54] } 11... bxc4 { [%clk 0:00:42] } 12. dxc4 { [%clk 0:00:54] } 12... Rb8 { [%clk 0:00:40] } 13. b4 { [%clk 0:00:49] } 13... a5 { [%clk 0:00:38] } 14. c5 { [%clk 0:00:48] } 14... Nc4 { [%clk 0:00:35] } 15. Nxc4 { [%clk 0:00:46] } 15... Bxg3 { [%clk 0:00:25] } 16. fxg3 { [%clk 0:00:44] } 16... dxc4 { [%clk 0:00:24] } 17. Bxg7 { [%clk 0:00:41] } 17... Rg8 { [%clk 0:00:23] } 18. Bc3 { [%clk 0:00:39] } 18... Qg5 { [%clk 0:00:19] } 19. Qd2 { [%clk 0:00:36] } 19... c6 { [%clk 0:00:14] } 20. O-O-O { [%clk 0:00:35] } 20... Bb7 { [%clk 0:00:12] } 21. Kc2 { [%clk 0:00:34] } 21... Rd8 { [%clk 0:00:11] } 22. Kb2 { [%clk 0:00:33] } 22... Nf6 { [%clk 0:00:09] } 23. h4 { [%clk 0:00:32] } 23... Rxd2+ { [%clk 0:00:07] } 24. Rxd2 { [%clk 0:00:31] } 24... Qg6 { [%clk 0:00:06] } 25. e4 { [%clk 0:00:29] } 25... Ng4 { [%clk 0:00:04] } 26. Ng1 { [%clk 0:00:27] } 26... Ne3 { [%clk 0:00:02] } 27. Nh3 { [%clk 0:00:25] } 27... Qxg3 { [%clk 0:00:00] } 28. Ng1 { [%clk 0:00:23] } 28... Qe5 { [%clk 0:00:00] } 29. Ne2 { [%clk 0:00:22] } { White wins on time. } 1-0

### Analysis:
#### it was a pretty decent game all around, I again dropped my queen, but in bullet chess it seems the queen isn't all that important in every instance. It often does lead to a bad position, but if your queen wasn't doing that much anyways then it seems to be okay
#### At the end, they blundered their queen and I didn't see it, but I was playing the clock since their time was so low I was just making any move.

---

## 1+0 played as black (win)
### Game 10 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/04Y6Iq1x"]
[Date "2025.10.25"]
[White "Saerdna58"]
[Black "boyo1991"]
[Result "0-1"]
[GameId "04Y6Iq1x"]
[UTCDate "2025.10.25"]
[UTCTime "19:45:25"]
[WhiteElo "1493"]
[BlackElo "1477"]
[WhiteRatingDiff "-6"]
[BlackRatingDiff "+7"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "C00"]
[Opening "French Defense: Normal Variation"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. e4 { [%clk 0:01:00] } 1... e6 { [%clk 0:01:00] } 2. d4 { [%clk 0:00:59] } { C00 French Defense: Normal Variation } 2... Ne7 { [%clk 0:01:00] } 3. c3 { [%clk 0:00:57] } 3... d6 { [%clk 0:01:00] } 4. Bd3 { [%clk 0:00:57] } 4... Nd7 { [%clk 0:00:59] } 5. Ne2 { [%clk 0:00:56] } 5... h6 { [%clk 0:00:59] } 6. O-O { [%clk 0:00:56] } 6... g6 { [%clk 0:00:58] } 7. f4 { [%clk 0:00:55] } 7... Bg7 { [%clk 0:00:58] } 8. Ng3 { [%clk 0:00:54] } 8... b6 { [%clk 0:00:57] } 9. Qc2 { [%clk 0:00:53] } 9... a6 { [%clk 0:00:57] } 10. f5 { [%clk 0:00:52] } 10... gxf5 { [%clk 0:00:55] } 11. exf5 { [%clk 0:00:51] } 11... exf5 { [%clk 0:00:54] } 12. Bxf5 { [%clk 0:00:47] } 12... Nxf5 { [%clk 0:00:54] } 13. Qxf5 { [%clk 0:00:46] } 13... f6 { [%clk 0:00:51] } 14. Qg6+ { [%clk 0:00:44] } 14... Kf8 { [%clk 0:00:50] } 15. Nf5 { [%clk 0:00:42] } 15... Bb7 { [%clk 0:00:48] } 16. Qxg7+ { [%clk 0:00:41] } 16... Ke8 { [%clk 0:00:46] } 17. Qg6+ { [%clk 0:00:40] } 17... Kf8 { [%clk 0:00:44] } 18. Nxh6 { [%clk 0:00:37] } 18... Rxh6 { [%clk 0:00:43] } 19. Bxh6+ { [%clk 0:00:35] } 19... Ke7 { [%clk 0:00:43] } 20. Re1+ { [%clk 0:00:32] } 20... Ne5 { [%clk 0:00:40] } 21. dxe5 { [%clk 0:00:31] } 21... dxe5 { [%clk 0:00:39] } 22. Qg7+ { [%clk 0:00:28] } 22... Ke6 { [%clk 0:00:38] } 23. Na3 { [%clk 0:00:25] } 23... c6 { [%clk 0:00:37] } 24. Rad1 { [%clk 0:00:24] } 24... b5 { [%clk 0:00:36] } 25. Rxd8 { [%clk 0:00:22] } 25... Rxd8 { [%clk 0:00:36] } 26. Qg4+ { [%clk 0:00:20] } 26... Kf7 { [%clk 0:00:34] } 27. Rf1 { [%clk 0:00:19] } 27... Rd6 { [%clk 0:00:31] } 28. Bg5 { [%clk 0:00:16] } 28... c5 { [%clk 0:00:27] } 29. Bxf6 { [%clk 0:00:15] } 29... Rd5 { [%clk 0:00:24] } 30. Bxe5+ { [%clk 0:00:13] } 30... Ke7 { [%clk 0:00:23] } 31. Bf6+ { [%clk 0:00:11] } 31... Kd6 { [%clk 0:00:22] } 32. Qf4+ { [%clk 0:00:08] } 32... Kc6 { [%clk 0:00:21] } 33. Nc2 { [%clk 0:00:05] } 33... Kb6 { [%clk 0:00:20] } 34. Ne3 { [%clk 0:00:02] } 34... a5 { [%clk 0:00:20] } 35. Nxd5+ { [%clk 0:00:00] } 35... Bxd5 { [%clk 0:00:19] } { Black wins on time. } 0-1

### Analysis:
#### I actually don't have a ton of analysis because it was a bit ago and outside of my memory exactly.

---

## 1+0 played as white (loss)
### Game 11 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/FjQRGnXK"]
[Date "2025.10.26"]
[White "boyo1991"]
[Black "DarkLordSpanky"]
[Result "0-1"]
[GameId "FjQRGnXK"]
[UTCDate "2025.10.26"]
[UTCTime "03:01:18"]
[WhiteElo "1484"]
[BlackElo "1437"]
[WhiteRatingDiff "-7"]
[BlackRatingDiff "+7"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... c5 { [%clk 0:01:00] } 2. Nd2 { [%clk 0:01:00] } 2... d6 { [%clk 0:01:00] } 3. e3 { [%clk 0:00:59] } 3... Nf6 { [%clk 0:00:59] } 4. Ne2 { [%clk 0:00:59] } 4... g6 { [%clk 0:00:59] } 5. h3 { [%clk 0:00:59] } 5... Bg7 { [%clk 0:00:59] } 6. a3 { [%clk 0:00:58] } 6... O-O { [%clk 0:00:58] } 7. b3 { [%clk 0:00:58] } 7... Nc6 { [%clk 0:00:58] } 8. Bb2 { [%clk 0:00:57] } 8... a6 { [%clk 0:00:58] } 9. c4 { [%clk 0:00:57] } 9... b5 { [%clk 0:00:58] } 10. g3 { [%clk 0:00:55] } 10... bxc4 { [%clk 0:00:57] } 11. dxc4 { [%clk 0:00:55] } 11... Re8 { [%clk 0:00:55] } 12. Bg2 { [%clk 0:00:54] } 12... e5 { [%clk 0:00:54] } 13. O-O { [%clk 0:00:53] } 13... Bd7 { [%clk 0:00:47] } 14. Nf3 { [%clk 0:00:50] } 14... Rb8 { [%clk 0:00:46] } 15. Nh4 { [%clk 0:00:49] } 15... Bf5 { [%clk 0:00:36] } 16. Bxc6 { [%clk 0:00:46] } 16... Re7 { [%clk 0:00:27] } 17. Bg2 { [%clk 0:00:42] } 17... Be6 { [%clk 0:00:26] } 18. Rb1 { [%clk 0:00:40] } 18... a5 { [%clk 0:00:25] } 19. a4 { [%clk 0:00:37] } 19... Qc7 { [%clk 0:00:22] } 20. f3 { [%clk 0:00:35] } 20... d5 { [%clk 0:00:20] } 21. g4 { [%clk 0:00:34] } 21... dxc4 { [%clk 0:00:15] } 22. Bc3 { [%clk 0:00:28] } 22... Rd8 { [%clk 0:00:12] } 23. b4 { [%clk 0:00:24] } 23... Rxd1 { [%clk 0:00:10] } 24. Rfxd1 { [%clk 0:00:22] } 24... axb4 { [%clk 0:00:10] } 25. Bd2 { [%clk 0:00:20] } 25... c3 { [%clk 0:00:09] } 26. Bxc3 { [%clk 0:00:19] } 26... bxc3 { [%clk 0:00:08] } 27. Rdc1 { [%clk 0:00:18] } 27... Bc4 { [%clk 0:00:07] } 28. Rxc3 { [%clk 0:00:17] } 28... Bxe2 { [%clk 0:00:07] } 29. Rbc1 { [%clk 0:00:15] } 29... Nd5 { [%clk 0:00:07] } 30. Kf2 { [%clk 0:00:14] } 30... Nxc3 { [%clk 0:00:06] } 31. Rxc3 { [%clk 0:00:14] } 31... Ba6 { [%clk 0:00:03] } 32. f4 { [%clk 0:00:11] } 32... Qb6 { [%clk 0:00:03] } 33. Bd5 { [%clk 0:00:09] } 33... Qb2+ { [%clk 0:00:03] } 34. Kf3 { [%clk 0:00:08] } 34... Qxc3 { [%clk 0:00:03] } 35. Be4 { [%clk 0:00:06] } 35... Be2+ { [%clk 0:00:01] } 36. Kxe2 { [%clk 0:00:05] } 36... Qb2+ { [%clk 0:00:01] } 37. Kf3 { [%clk 0:00:05] } 37... Qc1 { [%clk 0:00:00] } 38. Ng2 { [%clk 0:00:03] } 38... Qf1+ { [%clk 0:00:00] } 39. Kg3 { [%clk 0:00:02] } 39... Qh1 { [%clk 0:00:00] } 40. Kf3 { [%clk 0:00:01] } 40... Qf1+ { [%clk 0:00:00] } 41. Kg3 { [%clk 0:00:00] } 41... Qh1 { [%clk 0:00:00] } { Black wins on time. } 0-1

### Analysis:
#### This game was quite frustrating because I thought I was going to win on time and *should* have won on time, but *lost* on time at the end.
#### I did drop my queen, but it really wasn't the end of the world
#### I could have forced a draw, and should have, but I thought I was ahead on time and that was the biggest mistake. I should have payed attention to the time and I would have at least drawn.

---

## 1+0 played as white (loss)
### Game 12 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/gV78W2cw"]
[Date "2025.10.26"]
[White "boyo1991"]
[Black "tbecalli"]
[Result "0-1"]
[GameId "gV78W2cw"]
[UTCDate "2025.10.26"]
[UTCTime "14:30:10"]
[WhiteElo "1477"]
[BlackElo "1476"]
[WhiteRatingDiff "-6"]
[BlackRatingDiff "+6"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... e6 { [%clk 0:01:00] } 2. Nd2 { [%clk 0:01:00] } 2... d5 { [%clk 0:01:00] } 3. e3 { [%clk 0:01:00] } 3... Bc5 { [%clk 0:00:59] } 4. Ne2 { [%clk 0:01:00] } 4... Nc6 { [%clk 0:00:57] } 5. a3 { [%clk 0:00:59] } 5... Nf6 { [%clk 0:00:55] } 6. h3 { [%clk 0:00:58] } 6... O-O { [%clk 0:00:55] } 7. b3 { [%clk 0:00:58] } 7... Bd7 { [%clk 0:00:54] } 8. Bb2 { [%clk 0:00:57] } 8... e5 { [%clk 0:00:52] } 9. g3 { [%clk 0:00:57] } 9... d4 { [%clk 0:00:51] } 10. e4 { [%clk 0:00:56] } 10... Re8 { [%clk 0:00:50] } 11. Bg2 { [%clk 0:00:55] } 11... Bb6 { [%clk 0:00:49] } 12. b4 { [%clk 0:00:54] } 12... a5 { [%clk 0:00:47] } 13. Nb3 { [%clk 0:00:54] } 13... axb4 { [%clk 0:00:46] } 14. axb4 { [%clk 0:00:53] } 14... Rxa1 { [%clk 0:00:45] } 15. Bxa1 { [%clk 0:00:53] } 15... Nxb4 { [%clk 0:00:44] } 16. O-O { [%clk 0:00:52] } 16... Qc8 { [%clk 0:00:38] } 17. Nd2 { [%clk 0:00:48] } 17... Bxh3 { [%clk 0:00:37] } 18. f3 { [%clk 0:00:45] } 18... Bxg2 { [%clk 0:00:36] } 19. Kxg2 { [%clk 0:00:45] } 19... c5 { [%clk 0:00:32] } 20. Kf2 { [%clk 0:00:43] } 20... Bc7 { [%clk 0:00:32] } 21. Rh1 { [%clk 0:00:41] } 21... g6 { [%clk 0:00:30] } 22. Qg1 { [%clk 0:00:39] } 22... b6 { [%clk 0:00:26] } 23. Qh2 { [%clk 0:00:36] } 23... h5 { [%clk 0:00:25] } 24. Qh4 { [%clk 0:00:32] } 24... Nh7 { [%clk 0:00:22] } 25. Qh2 { [%clk 0:00:29] } 25... Kg7 { [%clk 0:00:21] } 26. Kg2 { [%clk 0:00:27] } 26... Rh8 { [%clk 0:00:20] } 27. g4 { [%clk 0:00:25] } 27... hxg4 { [%clk 0:00:18] } 28. fxg4 { [%clk 0:00:24] } 28... Qxg4+ { [%clk 0:00:16] } 29. Kf2 { [%clk 0:00:23] } 29... Nxd3+ { [%clk 0:00:14] } 30. Kf1 { [%clk 0:00:19] } 30... Nf4 { [%clk 0:00:11] } 31. Qg1 { [%clk 0:00:15] } 31... Qxg1+ { [%clk 0:00:09] } 32. Rxg1 { [%clk 0:00:14] } 32... Nxe2 { [%clk 0:00:09] } 33. Kxe2 { [%clk 0:00:14] } 33... Ng5 { [%clk 0:00:07] } 34. Bb2 { [%clk 0:00:12] } 34... Rh2+ { [%clk 0:00:06] } 35. Kd3 { [%clk 0:00:10] } 35... Nf3 { [%clk 0:00:06] } 36. Rg3 { [%clk 0:00:07] } 36... Rxd2+ { [%clk 0:00:04] } 37. Kc4 { [%clk 0:00:05] } 37... Ne1 { [%clk 0:00:03] } 38. Rh3 { [%clk 0:00:04] } 38... Rxc2+ { [%clk 0:00:02] } 39. Kb3 { [%clk 0:00:02] } 39... Nd3 { [%clk 0:00:01] } 40. Kxc2 { [%clk 0:00:01] } 40... Nf4 { [%clk 0:00:00] } { Black wins on time. } 0-1

### Analysis:
#### I was doing fine, then I allowed the bishop queen battery to go undefended -- I didn't *feed* into it so it wasn't too bad, but it caused me to eat time
#### The last 2 games have been so close on time, I need to make better decisions more quickly

---

## 1+0 played as black (win)
### Game 13 data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/qipJKw2y"]
[Date "2025.10.26"]
[White "Elman_Memmedov27"]
[Black "boyo1991"]
[Result "0-1"]
[GameId "qipJKw2y"]
[UTCDate "2025.10.26"]
[UTCTime "19:14:56"]
[WhiteElo "1459"]
[BlackElo "1471"]
[WhiteRatingDiff "-5"]
[BlackRatingDiff "+6"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "C00"]
[Opening "French Defense: Knight Variation"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. e4 { [%clk 0:01:00] } 1... e6 { [%clk 0:01:00] } 2. Nf3 { [%clk 0:00:59] } { C00 French Defense: Knight Variation } 2... Ne7 { [%clk 0:01:00] } 3. Nc3 { [%clk 0:00:57] } 3... h6 { [%clk 0:01:00] } 4. d4 { [%clk 0:00:56] } 4... a6 { [%clk 0:00:59] } 5. Be3 { [%clk 0:00:54] } 5... d6 { [%clk 0:00:59] } 6. Bd3 { [%clk 0:00:54] } 6... Nd7 { [%clk 0:00:59] } 7. e5 { [%clk 0:00:53] } 7... d5 { [%clk 0:00:58] } 8. Rg1 { [%clk 0:00:50] } 8... g6 { [%clk 0:00:57] } 9. g3 { [%clk 0:00:50] } 9... Bg7 { [%clk 0:00:57] } 10. a3 { [%clk 0:00:46] } 10... b6 { [%clk 0:00:56] } 11. Qd2 { [%clk 0:00:45] } 11... Bb7 { [%clk 0:00:55] } 12. Ke2 { [%clk 0:00:44] } 12... g5 { [%clk 0:00:55] } 13. g4 { [%clk 0:00:43] } 13... f6 { [%clk 0:00:53] } 14. h3 { [%clk 0:00:42] } 14... O-O { [%clk 0:00:50] } 15. h4 { [%clk 0:00:41] } 15... b5 { [%clk 0:00:47] } 16. hxg5 { [%clk 0:00:40] } 16... fxg5 { [%clk 0:00:46] } 17. Nxg5 { [%clk 0:00:38] } 17... hxg5 { [%clk 0:00:44] } 18. Bxg5 { [%clk 0:00:37] } 18... Ng6 { [%clk 0:00:43] } 19. Bxg6 { [%clk 0:00:35] } 19... Qxg5 { [%clk 0:00:42] } 20. Qxg5 { [%clk 0:00:34] } 20... Rfb8 { [%clk 0:00:39] } 21. Rh1 { [%clk 0:00:32] } 21... Bc8 { [%clk 0:00:38] } 22. Qh4 { [%clk 0:00:31] } 22... c6 { [%clk 0:00:37] } 23. Qh7+ { [%clk 0:00:30] } 23... Kf8 { [%clk 0:00:33] } 24. Rag1 { [%clk 0:00:23] } 24... Ke7 { [%clk 0:00:31] } 25. Qxg7+ { [%clk 0:00:22] } 25... Kd8 { [%clk 0:00:30] } 26. Rh8+ { [%clk 0:00:21] } 26... Kc7 { [%clk 0:00:29] } 27. Rh7 { [%clk 0:00:18] } 27... Kb6 { [%clk 0:00:28] } 28. Qh6 { [%clk 0:00:16] } 28... Rb7 { [%clk 0:00:27] } 29. Qe3 { [%clk 0:00:15] } 29... Raa7 { [%clk 0:00:27] } 30. a4 { [%clk 0:00:12] } 30... Nb8 { [%clk 0:00:25] } 31. axb5 { [%clk 0:00:10] } 31... cxb5 { [%clk 0:00:23] } 32. b4 { [%clk 0:00:09] } 32... Rc7 { [%clk 0:00:19] } 33. Rxc7 { [%clk 0:00:09] } 33... Rxc7 { [%clk 0:00:18] } 34. Qg5 { [%clk 0:00:07] } 34... Rxc3 { [%clk 0:00:17] } 35. Qf6 { [%clk 0:00:06] } 35... Rxc2+ { [%clk 0:00:16] } 36. Kf3 { [%clk 0:00:05] } 36... Rc3+ { [%clk 0:00:15] } 37. Kg2 { [%clk 0:00:04] } 37... Rc2 { [%clk 0:00:13] } 38. Qxe6+ { [%clk 0:00:03] } 38... Ka7 { [%clk 0:00:12] } 39. Qc6 { [%clk 0:00:02] } 39... Nxc6 { [%clk 0:00:11] } { Black wins on time. } 0-1

### Analysis:
#### I dropped my queen again, but it didn't seem to matter, I got theirs.
#### At the end I definitly could have watched my rook better.
#### My time control is what really carried me. Cautions enough to not lose too many pieces, but fast enough to win.
#### In bullet chess, material isn't as important in order to gain a win.

---

## 1+0 played as black (win)
### Game 14 data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/BoFRf7Sg"]
[Date "2025.10.26"]
[White "najafinm1987"]
[Black "boyo1991"]
[Result "0-1"]
[GameId "BoFRf7Sg"]
[UTCDate "2025.10.26"]
[UTCTime "20:11:30"]
[WhiteElo "1470"]
[BlackElo "1477"]
[WhiteRatingDiff "-5"]
[BlackRatingDiff "+6"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A04"]
[Opening "Zukertort Opening: Basman Defense"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. Nf3 { [%clk 0:01:00] } 1... h6 { [%clk 0:01:00] } { A04 Zukertort Opening: Basman Defense } 2. h3 { [%clk 0:00:59] } 2... e6 { [%clk 0:01:00] } 3. g4 { [%clk 0:00:59] } 3... Ne7 { [%clk 0:01:00] } 4. Bg2 { [%clk 0:00:58] } 4... d6 { [%clk 0:00:59] } 5. Nc3 { [%clk 0:00:57] } 5... b6 { [%clk 0:00:58] } 6. b3 { [%clk 0:00:57] } 6... Bb7 { [%clk 0:00:58] } 7. Bb2 { [%clk 0:00:56] } 7... a6 { [%clk 0:00:57] } 8. O-O { [%clk 0:00:55] } 8... Nd7 { [%clk 0:00:56] } 9. a4 { [%clk 0:00:54] } 9... g6 { [%clk 0:00:55] } 10. Nb5 { [%clk 0:00:52] } 10... e5 { [%clk 0:00:53] } 11. Nc3 { [%clk 0:00:50] } 11... Bg7 { [%clk 0:00:52] } 12. d4 { [%clk 0:00:48] } 12... c6 { [%clk 0:00:49] } 13. dxe5 { [%clk 0:00:47] } 13... dxe5 { [%clk 0:00:48] } 14. Nb1 { [%clk 0:00:43] } 14... c5 { [%clk 0:00:45] } 15. Qc1 { [%clk 0:00:40] } 15... Nc6 { [%clk 0:00:43] } 16. Rd1 { [%clk 0:00:39] } 16... g5 { [%clk 0:00:42] } 17. Qd2 { [%clk 0:00:35] } 17... f6 { [%clk 0:00:41] } 18. Ne1 { [%clk 0:00:33] } 18... O-O { [%clk 0:00:40] } 19. Qc3 { [%clk 0:00:29] } 19... Qe7 { [%clk 0:00:39] } 20. Qd3 { [%clk 0:00:20] } 20... a5 { [%clk 0:00:37] } 21. Qxd7 { [%clk 0:00:18] } 21... Qxd7 { [%clk 0:00:36] } 22. Rxd7 { [%clk 0:00:18] } 22... Rae8 { [%clk 0:00:35] } 23. Rxb7 { [%clk 0:00:17] } 23... Rf7 { [%clk 0:00:33] } 24. Rxf7 { [%clk 0:00:16] } 24... Kxf7 { [%clk 0:00:33] } 25. Nc3 { [%clk 0:00:15] } 25... f5 { [%clk 0:00:31] } 26. Nb5 { [%clk 0:00:14] } 26... f4 { [%clk 0:00:29] } 27. e3 { [%clk 0:00:12] } 27... Re6 { [%clk 0:00:26] } 28. exf4 { [%clk 0:00:11] } 28... gxf4 { [%clk 0:00:25] } 29. Nf3 { [%clk 0:00:11] } 29... Rg6 { [%clk 0:00:23] } 30. Re1 { [%clk 0:00:09] } 30... Ke6 { [%clk 0:00:21] } 31. Nxe5 { [%clk 0:00:06] } 31... Bxe5 { [%clk 0:00:18] } 32. Rxe5+ { [%clk 0:00:06] } 32... Kd7 { [%clk 0:00:16] } 33. Re1 { [%clk 0:00:03] } 33... Nb4 { [%clk 0:00:16] } 34. Bc6+ { [%clk 0:00:03] } 34... Nxc6 { [%clk 0:00:14] } 35. Be5 { [%clk 0:00:02] } 35... Nb4 { [%clk 0:00:13] } 36. Bd6 { [%clk 0:00:01] } 36... Kc6 { [%clk 0:00:12] } 37. Be5 { [%clk 0:00:00] } 37... Nxc2 { [%clk 0:00:11] } { Black wins on time. } 0-1

### Analysis:
#### I had a commanding lead of time
#### I was able to put my opponent in check a few times causing them to lose time
#### While you can't just put yourself in a bad position in bullet chess, time is the deciding factor
#### We traded queens, which is a positive considering I usually drop my queen, note for later -- trading queens keeps me from dropping my queen. Trade queens when possible!

---

## 1+0 played as white (win)
### Game 15 Data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/jwlRlBgv"]
[Date "2025.10.28"]
[White "boyo1991"]
[Black "c0rridon"]
[Result "1-0"]
[GameId "jwlRlBgv"]
[UTCDate "2025.10.28"]
[UTCTime "02:14:37"]
[WhiteElo "1465"]
[BlackElo "1426"]
[WhiteRatingDiff "+5"]
[BlackRatingDiff "-5"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... d5 { [%clk 0:01:00] } 2. Nd2 { [%clk 0:01:00] } 2... e5 { [%clk 0:00:59] } 3. e3 { [%clk 0:01:00] } 3... e4 { [%clk 0:00:58] } 4. d4 { [%clk 0:00:59] } 4... Nf6 { [%clk 0:00:56] } 5. h3 { [%clk 0:00:58] } 5... Bd6 { [%clk 0:00:56] } 6. Ne2 { [%clk 0:00:58] } 6... O-O { [%clk 0:00:55] } 7. g3 { [%clk 0:00:57] } 7... c5 { [%clk 0:00:54] } 8. Bg2 { [%clk 0:00:57] } 8... cxd4 { [%clk 0:00:54] } 9. exd4 { [%clk 0:00:56] } 9... Nc6 { [%clk 0:00:51] } 10. c3 { [%clk 0:00:55] } 10... Nh5 { [%clk 0:00:47] } 11. a3 { [%clk 0:00:54] } 11... f5 { [%clk 0:00:45] } 12. b4 { [%clk 0:00:53] } 12... f4 { [%clk 0:00:41] } 13. f3 { [%clk 0:00:50] } 13... Nxg3 { [%clk 0:00:38] } 14. Nxg3 { [%clk 0:00:50] } 14... fxg3 { [%clk 0:00:37] } 15. fxe4 { [%clk 0:00:48] } 15... dxe4 { [%clk 0:00:34] } 16. Nxe4 { [%clk 0:00:48] } 16... Qe8 { [%clk 0:00:33] } 17. Qe2 { [%clk 0:00:44] } 17... Bf5 { [%clk 0:00:26] } 18. Nxd6 { [%clk 0:00:43] } 18... Qxe2+ { [%clk 0:00:25] } 19. Kxe2 { [%clk 0:00:42] } 19... Bg6 { [%clk 0:00:19] } 20. Nc4 { [%clk 0:00:39] } 20... Rae8+ { [%clk 0:00:17] } 21. Kd2 { [%clk 0:00:38] } 21... Rf2+ { [%clk 0:00:11] } 22. Kd1 { [%clk 0:00:34] } 22... Rxg2 { [%clk 0:00:11] } 23. Re1 { [%clk 0:00:33] } 23... Rxe1+ { [%clk 0:00:10] } 24. Kxe1 { [%clk 0:00:33] } 24... Ne7 { [%clk 0:00:08] } 25. Kf1 { [%clk 0:00:32] } 25... Rh2 { [%clk 0:00:06] } 26. Kg1 { [%clk 0:00:31] } 26... Rc2 { [%clk 0:00:05] } 27. Bg5 { [%clk 0:00:29] } 27... Bd3 { [%clk 0:00:04] } 28. Bxe7 { [%clk 0:00:28] } 28... Bxc4 { [%clk 0:00:03] } 29. Rf1 { [%clk 0:00:25] } 29... Bxf1 { [%clk 0:00:01] } 30. Kxf1 { [%clk 0:00:24] } 30... Kf7 { [%clk 0:00:01] } 31. Bc5 { [%clk 0:00:22] } 31... h5 { [%clk 0:00:01] } 32. d5 { [%clk 0:00:21] } 32... h4 { [%clk 0:00:01] } 33. d6 { [%clk 0:00:21] } 33... Rxc3 { [%clk 0:00:00] } 34. d7 { [%clk 0:00:20] } { White wins on time. } 1-0

### Analysis:
#### This game I was able to experiment to test trading queens. I usually drop my queen which leads to a worse position, and in this game I did still end in a worse position, but I still had a better position since the board was simplified and it really wasn't looking too bad considering time and everything
#### Traditing queens while focusing on time is a really good means of winning on time as long as you do okay.

---

## 1+0 played as white (loss)
### Game 16 data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/lAE1wMyV"]
[Date "2025.10.28"]
[White "boyo1991"]
[Black "Alekius"]
[Result "0-1"]
[GameId "lAE1wMyV"]
[UTCDate "2025.10.28"]
[UTCTime "00:50:22"]
[WhiteElo "1471"]
[BlackElo "1413"]
[WhiteRatingDiff "-6"]
[BlackRatingDiff "+6"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Normal"]
[Annotator "lichess.org"]


### Analysis:
#### I didn't pay attention to knights and blundered my queen -- that was the main major mistake.

---

## 1+0 played as black (loss)
### Game 17 data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/ruwfuwnf"]
[Date "2025.10.28"]
[White "pisulpisul"]
[Black "boyo1991"]
[Result "1-0"]
[GameId "ruwfuwnf"]
[UTCDate "2025.10.28"]
[UTCTime "17:57:43"]
[WhiteElo "1533"]
[BlackElo "1476"]
[WhiteRatingDiff "+5"]
[BlackRatingDiff "-5"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "C00"]
[Opening "French Defense: La Bourdonnais Variation"]
[Termination "Normal"]
[Annotator "lichess.org"]

1. e4 { [%clk 0:01:00] } 1... e6 { [%clk 0:01:00] } 2. f4 { [%clk 0:00:59] } { C00 French Defense: La Bourdonnais Variation } 2... Ne7 { [%clk 0:01:00] } 3. Nf3 { [%clk 0:00:58] } 3... d6 { [%clk 0:01:00] } 4. Bc4 { [%clk 0:00:57] } 4... h6 { [%clk 0:00:59] } 5. Nc3 { [%clk 0:00:56] } 5... Nd7 { [%clk 0:00:59] } 6. O-O { [%clk 0:00:56] } 6... a6 { [%clk 0:00:58] } 7. a4 { [%clk 0:00:54] } 7... g6 { [%clk 0:00:58] } 8. f5 { [%clk 0:00:48] } 8... exf5 { [%clk 0:00:55] } 9. exf5 { [%clk 0:00:47] } 9... Nxf5 { [%clk 0:00:55] } 10. Qe2+ { [%clk 0:00:45] } 10... Be7 { [%clk 0:00:54] } 11. Nd5 { [%clk 0:00:41] } 11... Kf8 { [%clk 0:00:47] } 12. d4 { [%clk 0:00:35] } 12... Qe8 { [%clk 0:00:44] } 13. Nxe7 { [%clk 0:00:33] } 13... Qxe7 { [%clk 0:00:43] } 14. Qd3 { [%clk 0:00:33] } 14... Qe8 { [%clk 0:00:40] } 15. Bf4 { [%clk 0:00:31] } 15... b6 { [%clk 0:00:39] } 16. Rae1 { [%clk 0:00:29] } 16... Qd8 { [%clk 0:00:37] } 17. g4 { [%clk 0:00:23] } 17... Bb7 { [%clk 0:00:34] } 18. gxf5 { [%clk 0:00:21] } 18... gxf5 { [%clk 0:00:33] } 19. Qxf5 { [%clk 0:00:18] } 19... Qf6 { [%clk 0:00:32] } 20. Qxd7 { [%clk 0:00:11] } 20... Kg7 { [%clk 0:00:27] } 21. Ne5 { [%clk 0:00:06] } 21... Qd8 { [%clk 0:00:25] } 22. Qxf7# { [%clk 0:00:04] } { White wins by checkmate. } 1-0

### Analysis:
#### I was aggressively trying to trade queens, but it made me blind to the second threat.
#### I was able to correctly identify the first mating threat and defend it, but the second one was not seen until it was too late because of my focus on trading queens.
#### While trading queens is doable, do it when the oppertunity presents itself, don't try and make it happen.

---

## 1+0 played as black (win)
### Game 18 data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/DooTudwl"]
[Date "2025.10.30"]
[White "asberist"]
[Black "boyo1991"]
[Result "0-1"]
[GameId "DooTudwl"]
[UTCDate "2025.10.30"]
[UTCTime "02:54:51"]
[WhiteElo "1421"]
[BlackElo "1475"]
[WhiteRatingDiff "-5"]
[BlackRatingDiff "+5"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... d6 { [%clk 0:01:00] } 2. f3 { [%clk 0:01:00] } 2... Nd7 { [%clk 0:01:00] } 3. g4 { [%clk 0:01:00] } 3... e6 { [%clk 0:01:00] } 4. h4 { [%clk 0:00:59] } 4... Ne7 { [%clk 0:00:59] } 5. Bg5 { [%clk 0:00:59] } 5... g6 { [%clk 0:00:59] } 6. Bxe7 { [%clk 0:00:59] } 6... Qxe7 { [%clk 0:00:58] } 7. g5 { [%clk 0:00:59] } 7... Bg7 { [%clk 0:00:58] } 8. e4 { [%clk 0:00:58] } 8... b6 { [%clk 0:00:57] } 9. c4 { [%clk 0:00:58] } 9... Bb7 { [%clk 0:00:57] } 10. b4 { [%clk 0:00:58] } 10... a6 { [%clk 0:00:56] } 11. b5 { [%clk 0:00:58] } 11... a5 { [%clk 0:00:55] } 12. a4 { [%clk 0:00:57] } 12... O-O { [%clk 0:00:55] } 13. Nc3 { [%clk 0:00:57] } 13... Bc8 { [%clk 0:00:53] } 14. d4 { [%clk 0:00:56] } 14... Bb7 { [%clk 0:00:52] } 15. d5 { [%clk 0:00:56] } 15... e5 { [%clk 0:00:52] } 16. Nce2 { [%clk 0:00:54] } 16... f6 { [%clk 0:00:51] } 17. Ng3 { [%clk 0:00:54] } 17... fxg5 { [%clk 0:00:50] } 18. hxg5 { [%clk 0:00:53] } 18... Qxg5 { [%clk 0:00:49] } 19. Nh3 { [%clk 0:00:52] } 19... Qxg3+ { [%clk 0:00:48] } 20. Kd2 { [%clk 0:00:51] } 20... Qg5+ { [%clk 0:00:44] } 21. Kc2 { [%clk 0:00:50] } 21... Qh4 { [%clk 0:00:42] } 22. Be2 { [%clk 0:00:49] } 22... Qh6 { [%clk 0:00:41] } 23. Rg1 { [%clk 0:00:46] } 23... Qe3 { [%clk 0:00:39] } 24. Ng5 { [%clk 0:00:43] } 24... Qa3 { [%clk 0:00:37] } 25. Rxa3 { [%clk 0:00:41] } 25... Rf4 { [%clk 0:00:33] } 26. Ne6 { [%clk 0:00:37] } 26... c6 { [%clk 0:00:31] } 27. Nxf4 { [%clk 0:00:35] } 27... c5 { [%clk 0:00:29] } 28. Ne6 { [%clk 0:00:33] } 28... Bf8 { [%clk 0:00:26] } 29. Nc7 { [%clk 0:00:32] } 29... Rd8 { [%clk 0:00:23] } 30. Ne6 { [%clk 0:00:31] } 30... Re8 { [%clk 0:00:22] } 31. Nxf8 { [%clk 0:00:30] } 31... Rxf8 { [%clk 0:00:21] } 32. Qd2 { [%clk 0:00:28] } 32... Nf6 { [%clk 0:00:21] } 33. Qg5 { [%clk 0:00:27] } 33... Nh5 { [%clk 0:00:17] } 34. Rg4 { [%clk 0:00:25] } 34... Kh8 { [%clk 0:00:17] } 35. Rg1 { [%clk 0:00:17] } 35... Rg8 { [%clk 0:00:16] } 36. Rh1 { [%clk 0:00:14] } 36... Bc8 { [%clk 0:00:15] } 37. Rxh5 { [%clk 0:00:13] } 37... gxh5 { [%clk 0:00:15] } 38. Qxh5 { [%clk 0:00:12] } 38... Rg7 { [%clk 0:00:14] } 39. Qh1 { [%clk 0:00:08] } 39... Rg8 { [%clk 0:00:13] } 40. Qe1 { [%clk 0:00:07] } 40... Bd7 { [%clk 0:00:12] } 41. Bf1 { [%clk 0:00:06] } 41... Be8 { [%clk 0:00:11] } 42. Bh3 { [%clk 0:00:05] } 42... Bg6 { [%clk 0:00:10] } 43. Bf5 { [%clk 0:00:05] } 43... Bxf5 { [%clk 0:00:09] } 44. exf5 { [%clk 0:00:05] } 44... Rf8 { [%clk 0:00:08] } 45. Qg3 { [%clk 0:00:04] } 45... Rxf5 { [%clk 0:00:08] } 46. Qg6 { [%clk 0:00:03] } 46... Rf8 { [%clk 0:00:07] } 47. Qe6 { [%clk 0:00:02] } 47... Rg8 { [%clk 0:00:05] } 48. Qxd6 { [%clk 0:00:01] } 48... Rg7 { [%clk 0:00:04] } 49. Qxb6 { [%clk 0:00:01] } 49... Rg8 { [%clk 0:00:03] } 50. Qxa5 { [%clk 0:00:01] } 50... h6 { [%clk 0:00:03] } 51. Qb4 { [%clk 0:00:01] } 51... h5 { [%clk 0:00:02] } 52. Qxc5 { [%clk 0:00:01] } 52... h4 { [%clk 0:00:02] } 53. Qd6 { [%clk 0:00:01] } 53... h3 { [%clk 0:00:02] } 54. Qe6 { [%clk 0:00:01] } 54... h2 { [%clk 0:00:02] } 55. Qg6 { [%clk 0:00:00] } 55... h1=Q { [%clk 0:00:02] } { Black wins on time. } 0-1

### Analysis:
#### This is an example of how close time controls can get. I have won by smaller margins before, but when theres no immediate mate, time becomes the factor.
#### keep the game complicated so that there are no immediate mates, and win on time

---

## 1+0 played as black (draw)
### Game 19 data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/0LE4O7rc"]
[Date "2025.10.30"]
[White "timfromboston"]
[Black "boyo1991"]
[Result "1/2-1/2"]
[GameId "0LE4O7rc"]
[UTCDate "2025.10.30"]
[UTCTime "00:35:29"]
[WhiteElo "1485"]
[BlackElo "1475"]
[WhiteRatingDiff "-1"]
[BlackRatingDiff "+0"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Time forfeit"]
[Annotator "lichess.org"]

1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... d6 { [%clk 0:01:00] } 2. Nf3 { [%clk 0:01:00] } 2... Nd7 { [%clk 0:01:00] } 3. c3 { [%clk 0:01:00] } 3... h6 { [%clk 0:01:00] } 4. Bg5 { [%clk 0:00:59] } 4... e6 { [%clk 0:00:59] } 5. Bxd8 { [%clk 0:00:59] } 5... Kxd8 { [%clk 0:00:58] } 6. Nbd2 { [%clk 0:00:58] } 6... g6 { [%clk 0:00:58] } 7. g3 { [%clk 0:00:57] } 7... Bg7 { [%clk 0:00:58] } 8. Bg2 { [%clk 0:00:57] } 8... b6 { [%clk 0:00:57] } 9. e4 { [%clk 0:00:56] } 9... Bb7 { [%clk 0:00:57] } 10. e5 { [%clk 0:00:55] } 10... d5 { [%clk 0:00:56] } 11. d4 { [%clk 0:00:55] } 11... a6 { [%clk 0:00:55] } 12. b4 { [%clk 0:00:54] } 12... g5 { [%clk 0:00:55] } 13. a4 { [%clk 0:00:53] } 13... Ke7 { [%clk 0:00:53] } 14. g4 { [%clk 0:00:52] } 14... Kf8 { [%clk 0:00:51] } 15. b5 { [%clk 0:00:51] } 15... a5 { [%clk 0:00:49] } 16. Ng1 { [%clk 0:00:48] } 16... Ne7 { [%clk 0:00:49] } 17. Ne2 { [%clk 0:00:48] } 17... Kg8 { [%clk 0:00:49] } 18. f3 { [%clk 0:00:47] } 18... Kh7 { [%clk 0:00:48] } 19. Bf1 { [%clk 0:00:46] } 19... Rhg8 { [%clk 0:00:47] } 20. Nc1 { [%clk 0:00:45] } 20... Rgf8 { [%clk 0:00:46] } 21. Bd3+ { [%clk 0:00:45] } 21... Kg8 { [%clk 0:00:45] } 22. O-O { [%clk 0:00:44] } 22... Rfe8 { [%clk 0:00:45] } 23. h3 { [%clk 0:00:43] } 23... Red8 { [%clk 0:00:44] } 24. Ndb3 { [%clk 0:00:42] } 24... f5 { [%clk 0:00:43] } 25. Ne2 { [%clk 0:00:41] } 25... f4 { [%clk 0:00:42] } 26. Bf5 { [%clk 0:00:39] } 26... exf5 { [%clk 0:00:40] } 27. gxf5 { [%clk 0:00:38] } 27... Nxf5 { [%clk 0:00:40] } 28. e6 { [%clk 0:00:37] } 28... Ne3 { [%clk 0:00:38] } 29. exd7 { [%clk 0:00:36] } 29... Nxd1 { [%clk 0:00:37] } 30. Rfxd1 { [%clk 0:00:35] } 30... Rxd7 { [%clk 0:00:37] } 31. Nc5 { [%clk 0:00:34] } 31... bxc5 { [%clk 0:00:35] } 32. dxc5 { [%clk 0:00:34] } 32... c6 { [%clk 0:00:34] } 33. b6 { [%clk 0:00:33] } 33... Rdd8 { [%clk 0:00:33] } 34. Nd4 { [%clk 0:00:33] } 34... Rdb8 { [%clk 0:00:32] } 35. Ne6 { [%clk 0:00:30] } 35... Re8 { [%clk 0:00:31] } 36. Nxg7 { [%clk 0:00:28] } 36... Kxg7 { [%clk 0:00:29] } 37. h4 { [%clk 0:00:27] } 37... Re7 { [%clk 0:00:29] } 38. hxg5 { [%clk 0:00:26] } 38... hxg5 { [%clk 0:00:28] } 39. Re1 { [%clk 0:00:25] } 39... Rxe1+ { [%clk 0:00:26] } 40. Rxe1 { [%clk 0:00:25] } 40... Rh8 { [%clk 0:00:25] } 41. c4 { [%clk 0:00:22] } 41... g4 { [%clk 0:00:25] } 42. cxd5 { [%clk 0:00:21] } 42... cxd5 { [%clk 0:00:23] } 43. Rc1 { [%clk 0:00:19] } 43... d4 { [%clk 0:00:23] } 44. c6 { [%clk 0:00:18] } 44... Bxc6 { [%clk 0:00:21] } 45. Rxc6 { [%clk 0:00:17] } 45... gxf3 { [%clk 0:00:21] } 46. Rc7+ { [%clk 0:00:16] } 46... Kf6 { [%clk 0:00:20] } 47. Kf2 { [%clk 0:00:16] } 47... d3 { [%clk 0:00:19] } 48. Rc6+ { [%clk 0:00:14] } 48... Ke5 { [%clk 0:00:17] } 49. Rc1 { [%clk 0:00:13] } 49... Kd4 { [%clk 0:00:16] } 50. b7 { [%clk 0:00:12] } 50... Rb8 { [%clk 0:00:14] } 51. Rc8 { [%clk 0:00:11] } 51... Rxb7 { [%clk 0:00:12] } 52. Rd8+ { [%clk 0:00:10] } 52... Kc4 { [%clk 0:00:11] } 53. Rf8 { [%clk 0:00:09] } 53... Rb2+ { [%clk 0:00:10] } 54. Ke1 { [%clk 0:00:08] } 54... Rb1+ { [%clk 0:00:08] } 55. Kd2 { [%clk 0:00:07] } 55... Kb3 { [%clk 0:00:07] } 56. Rxf4 { [%clk 0:00:06] } 56... Ka2 { [%clk 0:00:06] } 57. Kxd3 { [%clk 0:00:05] } 57... Rb3+ { [%clk 0:00:05] } 58. Ke4 { [%clk 0:00:04] } 58... Rb4+ { [%clk 0:00:04] } 59. Kf5 { [%clk 0:00:04] } 59... Rxa4 { [%clk 0:00:03] } 60. Kg4 { [%clk 0:00:04] } 60... Rxf4+ { [%clk 0:00:03] } 61. Kxf4 { [%clk 0:00:03] } 61... f2 { [%clk 0:00:02] } 62. Ke3 { [%clk 0:00:03] } { Draw by time and insufficient material. } 1/2-1/2

### Analysis:
#### I had a mouse slip/misclick this game at the end that caused time to run out
#### Even with the misclick, they were winning on time
#### The heuristic is that in the end game, always trade rooks. It is still valid and true, but here I wish I would have had a faster intuition.

---

## 1+0 played as white (draw)
### Game 20 data:
#### [Event "rated bullet game"]
[Site "https://lichess.org/LAvG2yLy"]
[Date "2025.10.31"]
[White "boyo1991"]
[Black "nay_ra3oJlb"]
[Result "1/2-1/2"]
[GameId "LAvG2yLy"]
[UTCDate "2025.10.31"]
[UTCTime "00:06:30"]
[WhiteElo "1486"]
[BlackElo "1561"]
[WhiteRatingDiff "+1"]
[BlackRatingDiff "-1"]
[Variant "Standard"]
[TimeControl "60+0"]
[ECO "A00"]
[Opening "Mieses Opening"]
[Termination "Normal"]
[Annotator "lichess.org"]

1. d3 { [%clk 0:01:00] } { A00 Mieses Opening } 1... d5 { [%clk 0:01:00] } 2. Nd2 { [%clk 0:01:00] } 2... Bg4 { [%clk 0:00:59] } 3. e3 { [%clk 0:01:00] } 3... Bxd1 { [%clk 0:00:59] } 4. Kxd1 { [%clk 0:00:58] } 4... d4 { [%clk 0:00:58] } 5. e4 { [%clk 0:00:57] } 5... c5 { [%clk 0:00:57] } 6. Ne2 { [%clk 0:00:57] } 6... Nc6 { [%clk 0:00:56] } 7. g3 { [%clk 0:00:57] } 7... Qa5 { [%clk 0:00:56] } 8. a3 { [%clk 0:00:57] } 8... Qb6 { [%clk 0:00:55] } 9. Bg2 { [%clk 0:00:56] } 9... a5 { [%clk 0:00:54] } 10. b3 { [%clk 0:00:55] } 10... a4 { [%clk 0:00:54] } 11. Bb2 { [%clk 0:00:55] } 11... axb3 { [%clk 0:00:52] } 12. cxb3 { [%clk 0:00:55] } 12... Na5 { [%clk 0:00:51] } 13. Nf3 { [%clk 0:00:52] } 13... Nxb3 { [%clk 0:00:50] } 14. Nh4 { [%clk 0:00:49] } 14... Nxa1 { [%clk 0:00:49] } 15. Kd2 { [%clk 0:00:48] } 15... Qxb2+ { [%clk 0:00:46] } 16. Kd1 { [%clk 0:00:43] } 16... Qc2+ { [%clk 0:00:45] } 17. Ke1 { [%clk 0:00:41] } 17... Qb1+ { [%clk 0:00:41] } 18. Kd2 { [%clk 0:00:40] } 18... Qc2+ { [%clk 0:00:40] } 19. Ke1 { [%clk 0:00:39] } 19... Nf6 { [%clk 0:00:40] } 20. f3 { [%clk 0:00:37] } 20... e5 { [%clk 0:00:39] } 21. Kf2 { [%clk 0:00:36] } 21... Qxd3 { [%clk 0:00:37] } 22. Rxa1 { [%clk 0:00:35] } 22... Qe3+ { [%clk 0:00:35] } 23. Kf1 { [%clk 0:00:34] } 23... c4 { [%clk 0:00:33] } 24. Ke1 { [%clk 0:00:33] } 24... Rxa3 { [%clk 0:00:32] } 25. Rxa3 { [%clk 0:00:32] } 25... Bxa3 { [%clk 0:00:31] } 26. Bf1 { [%clk 0:00:30] } 26... Bc1 { [%clk 0:00:29] } 27. Ng2 { [%clk 0:00:29] } 27... Qa3 { [%clk 0:00:26] } 28. Ng1 { [%clk 0:00:25] } 28... d3 { [%clk 0:00:25] } 29. Kd1 { [%clk 0:00:24] } 29... c3 { [%clk 0:00:23] } 30. Bxd3 { [%clk 0:00:22] } 30... Qa2 { [%clk 0:00:21] } 31. Kxc1 { [%clk 0:00:21] } 31... Qd2+ { [%clk 0:00:20] } 32. Kb1 { [%clk 0:00:19] } { The game is a draw. } 1/2-1/2

### Analysis:
#### This person had a mate in one they must not have seen or something, but they were crushing me.
#### What it tells me is that the 1500s won't be impossible if they don't see an easy mate like this

---

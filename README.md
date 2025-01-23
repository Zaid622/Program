continue = true
highscore = 0
winningteam = ""
while continue = true:
 teamname = input("Enter team name")
 score = int(input("Enter score")
 if score > highscore:
   highscore = score
   winningteam = teamname
 endif
 decision = input(" Enter 1 to stop or 2 to continue")
 if decision == 1:
 continue = false
print("The winning team is",winningteam,"with a score of",highscore)

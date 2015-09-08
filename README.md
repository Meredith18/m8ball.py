# m8ball.py
def p1():
  f=pickAFile()
  p=makePicture(f)
  s=makeStyle(sansSerif,bold,18)
  addTextWithStyle(p,60,90,"Cannot Predict",s,white)
  s=makeStyle(sansSerif,bold,18)
  addTextWithStyle(p,108,124,"Now",s,white)
  explore(p)

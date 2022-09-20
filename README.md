 # Avaliador

percentual = int(input("Informe o percentual de exercícios executados corretamente, entre 0 e 100:  "))
media = 60
m1 = 60
m2 = 89
m3 = 90
m4 = 100
if percentual >= media:
 print("Você Passou!")
 if percentual <= m1:
  print("Não Passou! Necessário Refazer!")
if percentual < m1:
  print ("Conceito ND")
if percentual >= m1 and percentual <= m2:
  print ("Conceito D")
if percentual >= m3 and percentual < m4:
  print ("Conceito DL")  
if percentual == m4:
  print ("Conceito DML")  

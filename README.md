# Greg_project
learning
# include numpy as np
a=2+3
def B(alpha, beta):
"""une constante de normalisation pour que la probabilité totale soit 1"""
return math.gamma(alpha) * math.gamma(beta) / math.gamma(alpha + beta)
def beta_pdf(x, alpha, beta):
if x <= 0 or x >= 1: # aucun poids en dehors de [0, 1]
return 0
return x ** (alpha - 1) * (1 - x) ** (beta - 1) / B(alpha, beta)
alpha / (alpha + bêta)

from pyg import*
from math import*
def Polynome_du_second_degre(a,b,c):
     #Aidé par M.Carro notamment sur l'écriture de la variable fact.
    dis=b**2-4*a*c
    if (dis>0):
        r1=(-b-sqrt(dis))/(2*a)
        r2=(-b+sqrt(dis))/(2*a)
        fact = str(a) + "(x-" + str(r1) + ")(x-" + str(r2) + ")"
        return(fact)
    elif (det==0):
        r0=-b-sqrt(det)/(2*a)
        fact = str(a) + "(x-" + str(r0) + ")**2"
        return(fact)
    else:
        return('Pas de racine')


def Polynome_du_second_degre2(a,b,c):
    #Aidé par M.Carro notamment sur l'écriture de la variable fact. Cette fois-ci la version est encore plus lisible.

    dis = b**2-4*a*c #Discriminant

    if (dis>0):

        r1=(-b-sqrt(dis))/(2*a) #Première racine
        r2=(-b+sqrt(dis))/(2*a) #Deuxième racine

        fact = f"f(x)={a}(x-{r1})(x-{r2})" #Factorisation
        #Explication du f"{}" sur he-arc.github.io/livre-python/fstrings/index.html

        return(fact)

    elif (dis==0):

        r0=-b-sqrt(dis)/(2*a)
        if (r0<0):
            r0=r0*(-1)
            fact = f"f(x)={a}(x+{r0})**2"
            return(fact)
        else:
            fact = f"f(x)={a}(x-{r0})**2"
            return(fact)
    else:
        return('Pas de racine')

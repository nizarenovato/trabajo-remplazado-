# trabajo-remplazado-
def leer (C,n) :
    for i in range (10):
        n.append (input ("Dame el nombre"))
        C.append (input (" Dame la calificación"))



def alumno_mayor (C,n,nm):
    for i in range (10):
        if float(C[i]) > 8.5 : 
            nm.append(n[i])

def resultado (nm):
    print (" Alumnos con mayor promedio")
    for i in nm:
        print (f" {i}")

- š Hi, Iām @R2andre
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
R2andre/R2andre is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def valorPagamento(valor,dias):
    if dias == 0:
        return valor
    elif dias > 0:
        R= valor*1.03+valor*0.001*dias
        return(R)

def main():
    valor = float(input())
    dias = int(input())
    print(valorPagamento(valor,dias))
main()

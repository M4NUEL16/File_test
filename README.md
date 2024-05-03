
# File_test
print()
print()

print("Final assessment of secondary school students - Liceu Domingos Ramos")
print()

name_aluno1= input("Tell me your name: ")
age_aluno1= int (input("Enter your age: "))
Academic_year= input("School year ended: ")
print()

print(f"Student-{name_aluno1} /  Age-{age_aluno1} / School year-{Academic_year} ")
print()

nota1= float(input("Final grade 1* trimestre: "))
print()
nota2= float (input("Final grade 2* trimestre: "))
print()
nota3= float (input("Final grade 3* trimestre: "))
print()
Final_grade= (nota1+nota2+nota3)/3

print(f"Your final grade is {Final_grade}.")

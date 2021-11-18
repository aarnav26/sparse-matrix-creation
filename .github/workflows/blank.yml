def create_matrix(r, c):

    global mat

    mat = []

    for i in range(r):

        row = []

        for j in range(c):

            element = int(input("Enter elements of matrix: "))

            row.append(element)

        mat.append(row)

    return mat

def sparse_matrix(mat,r, c):

    sparse_matrix = []

    for i in range(r):

        for j in range(c):

            temp_list = []  

            if mat[i][j]!=0:

                temp_list.append(i) 

                temp_list.append(j)

                temp_list.append(mat[i][j])

                sparse_matrix.append(temp_list)

    return sparse_matrix



r1 = int(input("Enter number of rows: "))

c1 = int(input("Enter number of columns: "))

mat1=create_matrix(r1,c1)

print(mat1)

#r2 = int(input("Enter number of rows: "))

#c2 = int(input("Enter number of columns: "))

#mat2=create_matrix(r2,c2)

#print(mat2)







print(sparse_matrix(mat1,r1, c1))

#print(sparse_matrix(mat2,r2, c2))

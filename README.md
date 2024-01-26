# python_matrixaddition
matrix_a=[[1,2,3],[4,5,6],[7,8,9]]
matrix_b=[[9,8,7],[6,5,4],[3,2,1]]
result_matrix=[]
for i in range(len(matrix_a)):
  row=[]
  for j in range(len(matrix_a[0])):
    row.append(matrix_a[i][j]+matrix_b[i][j])
  result_matrix.append(row)
for row in result_matrix:
  print(row)

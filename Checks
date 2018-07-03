#Scalar Check
def Check_Scalar(scalar):
  status = True
  if (type(scalar) != int) and (type(scalar) != float) and (type(scalar) != complex):
    status = False
  return Status

#Vector Check
def Check_Vector(vector):
  status = True
  for i in range(len(vector)):
    if Check_Scalar(vector[i]) == False:
      status = False
  return status

#Matrix Check
def Check_Matrix(matrix):
  status = True
  for i in range(len(matrix)):
    if Check_Vector(matrix[i]) == False:
      status = False
  return status

def normalize(vector):
  '''
  '''
  if Check_vector(vector) == False:
    print("invalid input")
  else:

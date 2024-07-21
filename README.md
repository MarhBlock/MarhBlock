# Población inicial (2017)
initial_population <- poblacion_2017

# Proyección de la población para 10 años (hasta 2027)
projection <- pop.projection(leslie_matrix, initial_population, iterations = 10)

# Mostrar la proyección
print(projection)

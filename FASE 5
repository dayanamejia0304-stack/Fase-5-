
# Función (módulo) para calcular cantidad a pedir
def  cantidad_a_pedir(stock_actual, stock_minimo):
    if stock_actual < stock_minimo:                     
        return stock_minimo - stock_actual
    else:
        return 0


# Matriz inventario: [Código, Nombre, Stock Actual, Stock Mínimo]
inventario = [
    ["A001", "Arroz", 8, 15],
    ["A002", "Azúcar", 20, 10],
    ["A003", "Aceite", 5, 12],
    ["A004", "Sal", 30, 25],
    ["A005", "Harina", 6, 10]
]

print("\n--- LISTA DE PEDIDOS ---")

# Recorrer matriz
for articulo in inventario:
    codigo = articulo[0]
    nombre = articulo[1]
    stock_actual = articulo[2]
    stock_minimo = articulo[3]

    pedido = cantidad_a_pedir(stock_actual, stock_minimo)

    print(f"Artículo: {nombre} | Cantidad a pedir: {pedido}")
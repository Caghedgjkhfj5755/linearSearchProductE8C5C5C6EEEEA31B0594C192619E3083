# linearSearchProductE8C5C5C6EEEEA31B0594C192619E3083


def linearSearchProduct(productList, targetProduct) :
  indices = []
  for index, product in enumerate(productList) :
       if product == targetProduct :
          indices.append(index) 
  return indices
products = [ "shoes", "boot", "loafer", "shoes", "sandal", "shoes"]
target = "shoes"
target2 = "apple"
result = linearSearchProduct(products, target) 
print(result)

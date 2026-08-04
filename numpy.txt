import numpy as np

# 1. np.array()
a = np.array([10, 20, 30, 40, 50])
print("Array:", a)

# 2. np.arange()
b = np.arange(1, 11)
print("Arange:", b)

# 3. np.linspace()
c = np.linspace(1, 10, 5)
print("Linspace:", c)

# 4. shape
print("Shape of array b:", b.shape)

# 5. reshape()
d = b.reshape(2, 5)
print("Reshaped Array:")
print(d)

# 6. np.sum()
print("Sum:", np.sum(a))

# 7. np.mean()
print("Mean:", np.mean(a))

# 8. np.max()
print("Maximum:", np.max(a))

# 9. np.min()
print("Minimum:", np.min(a))

# 10. np.sort()
e = np.array([8, 2, 6, 1, 5])
print("Sorted Array:", np.sort(e))

# 11. np.where()
result = np.where(a > 25)
print("Index where value > 25:", result)

# 12. np.concatenate()
f = np.array([60, 70])
g = np.concatenate((a, f))
print("Concatenated Array:", g)
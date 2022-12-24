# Popular_Hashing_Algorithm

import hashlib 

str="Sumanta Swain"
hashedval=hashlib.sha256(str.encode())
print(hashedval)
print(hashedval.hexdigest())

print("=======================================")

str="Sumanta swain"
hashedval=hashlib.sha512(str.encode())
print(hashedval)
print(hashedval.hexdigest())

print("=======================================")

str="Sumanta swain"
hashedval=hashlib.sha224(str.encode())
print(hashedval)
print(hashedval.hexdigest())

print("=======================================")

str="Sumanta swain"
hashedval=hashlib.sha384(str.encode())
print(hashedval)
print(hashedval.hexdigest())

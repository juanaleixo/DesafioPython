import hashlib
import numpy as np
from itertools import product

def encrypt_string(hash_string):
    sha_signature = \
        hashlib.sha256(hash_string.encode()).hexdigest()
    return sha_signature

vector=['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z',1,2,3,4,5,6,7,8,9]
list1 = list(product(vector, repeat=3))
vector1 = np.asarray(list1)


achou=False

i=-1

while achou==False:
    
    i+=1


    hash_string = 'https://link.layers.education/w'+vector1[i,0]+'cc'+vector1[i,1]+'9x'+vector1[i,2]
    sha_signature = encrypt_string(hash_string)
    print(i)
    print(sha_signature)

    if sha_signature=='76949a35477f8b8f5e35c50d3006c01dbc4515bb744d88f0b636bc5f2fc20756':
        print(hash_string)
        print('Site Encontrado')
        achou=True

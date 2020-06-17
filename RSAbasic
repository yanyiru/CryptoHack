import binascii

p = 
q = 

#normal totient
t = (p-1)*(q-1)
def egcd(a, b):
    if a == 0:
        return (b, 0, 1)
    else:
        g, y, x = egcd(b % a, a)
        return (g, x - (b // a) * y, y)

def modinv(a, m):
    g, x, y = egcd(a, m)
    if g != 1:
        raise Exception('modular inverse does not exist')
    else:
        return x % m

#special totient
t2 = 

e = 
c = 
d = modinv(e,t)
N = 

m = pow(c,d,N)

print(binascii.unhexlify(hex(m)[2:]))

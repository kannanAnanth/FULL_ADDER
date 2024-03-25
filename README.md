# FULL_ADDER
# Truth Table
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/02ead8f5-d958-4c89-ac51-368ca086cf41)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/418e00aa-ed19-4ab3-a413-bae9575bff0e)
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/0c26fe47-d78c-43dd-ac0d-804e427a3bbc)

# Program

```
module FULLADDER(a,b,c,sum,carry);
input a,b,c;
output sum,carry;
wire w1,w2,w3;
xor g1(w1,a,b);
xor g2(sum,w1,c);
and g3(w3,a,b);
and g4(w2,w1,c);
and g5(carry,w2,w3);
endmodule
```

#Output
![WhatsApp Image 2024-03-25 at 14 15 36_809fba96](https://github.com/RESMIRNAIR/FULL_ADDER/assets/160721190/3c74b143-2e08-4da1-8a03-f16226c35dc8)

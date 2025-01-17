
n = base
$$n^{range(n-n, n-1)}$$

Decimal = base 10
$$
10^0 = 1,\    
10^1 = 10, \
10^2 = 100, \
... \
10^8 = 100000000
$$
[[binary]] = base 2
$$
2^0 = 1,\ 2^1 = 2,\ 2^2 = 4,\ ...\ 2^8 = 256
$$
$2^{16} = 1024$, which is a megabyte.
[[hex]] = base 16


Decimal to Base:
	Divide number by base and record remainder. The remainders from first to last read the number in the new base. The last remainder is the highest digit of the number in the new base. 
	*1248 to base 6:*
$$ 1248 / 6 = 208 r 0 $$
$$208 / 6 = 34 r 4$$
$$34 / 6 = 5 r 4$$
$$5 / 6 = 0 r 5 $$
	*1248 in base 6 is 5440*

Base to Decimal: 
	Multiply each number by the base^(significant figure of the number)
	And then sum the total of these multiplications. 
	So to convert 1234 in base 4 to base 10 you would:
$$ 4 * 4^0 = 4$$
$$ 3 * 4^1 = 12 $$
$$ 2 * 4^2 = 32 $$
$$ 1 * 4^3 =  64 $$
$$ 4 + 12 + 32 + 64 = 112 $$
	*1234 in base 4 is 112 in base 10*
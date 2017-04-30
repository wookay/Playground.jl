```julia
using SpecialFunctions
using Calculus

zeta(0) == -1/2
zeta(2) ≈  pi^2/6
zeta(4) ≈ pi^4/90
zeta(6) ≈ pi^6/945

zeta(-1) ≈ -1/12
zeta(-2) == 0
zeta.(-2(1:10)) == -zeros(10)

zeta'(0) ≈ -log(2pi)/2
```

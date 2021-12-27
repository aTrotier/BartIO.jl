# BartIO Documentation

## Calling BART functions

In order to call bart, the new python wrapper needs to be install in the pycall environment with :
```@docs
initBart(path2bart::String,path2bartpy::String)
```
## IO to BART files
```@docs
readcfl(filename::String)
```

```@docs
writecfl(filename::String,dataCfl::Array{ComplexF32})
```

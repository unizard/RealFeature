
## Do it your self Torch7 - Basic

### Variables

### Loop control

### Operators

- Tensor Resize
  
  inputs:resize(input:size())

- Tensor Resize & Copy
  
  inputs:resize(input:size()):copy(input)

### Functions

### Standard library

### Arrays

### Pointers

### Arrays and Pointers

### String function

### Structure

### Class


### 
nn.Sequential
model:get(1)
model:get(1):get(1)
model:get(1):get(1):get(1)




## Do it your self Torch7 - Advanced

### Non-linearity
- [ReLU]
- [Leaky ReLU]
- [PReLU]

  PReLU is not supported in CUNN, CUDNN. only support NN.

  example #1
  model:add(nn.PReLU())
  
  example #2
  model:add(nn.PReLU(nil,nil,true))

- [RReLU]
- 










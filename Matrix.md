<!-- Create a matrix -->
<details>
<summary> Create a matrix </summary>

*   Create an 1D matrix

```matlab
mat1 = ["Apple", "Orange", "Banana"]
```

*   Create a 2D matrix

```matlab
mat2 = [1:2:7; 9:2:15]
```

*   Normally distributed random numbers

```matlab
randn
```

*   Uniformly distributed random numbers

```matlab
rand(2, 4)
```

*   Uniformly distributed pseudorandom integers

```matlab
randi([1 10])
```

*   Continuous uniform random numbers

```matlab
unifrnd(2, 3, [1 3])
```

*   Create an infinitive value

```matlab
mat = inf
```

*   Create an array of shape (1, 3) with only zeros

```matlab
zero = zeros(1,3)
```

*   Create an array of shape (1, 3) with only ones

```matlab
one = ones(1,3)
```


</details>

<!-- Accessing -->
<details>
<summary> Accessing </summary>

*   Accessing an index

```matlab
mat = [1 3 5 7;
       9 11 13 15];
mat(2,1)
```

*   Slicing

```matlab
mat(1:2,[2,3])
```

</details>

<!-- Maximum, minimum -->
<details>
<summary> Maximum, minimum </summary>

*   Maximum between an array and a number

```matlab
a = [1, 7, 9, 5, 10];
max(a, 11)
```

*   Maximum value of the array

```matlab
max(a)
```

*   Minimum between an array and a number

```matlab
min(a, 0)
```

*   Minimum value of the array

```matlab
min(a)
```


</details>

<!-- Concatenate -->
<details>
<summary> Concatenate </summary>

*   Column Concatenate

```matlab
a = [1, 1, 1, 1];
b = [2, 2, 2, 2];
[a; b]
```

*   Row Concatenate

```matlab
[a, b]
```


</details>

<!-- Manipulation -->
<details>
<summary> Manipulation </summary>

*   Reshaping matrix

```matlab
mat = ["Apple", "Orange", "Banana"]
reshape(mat, 3,1)
```

*   Adding array elements

```matlab
mat(1,4) = "Cherry"
```

*   Changing array elements

```matlab
mat(1,2) = "Pear"
```

*   Transpose 2D matrix

```matlab
mat = [1 3 5 7];
transpose(mat)
```

*   Transpose 1D matrix

```matlab
mat = [1 3 5 7;
       9 11 13 15];
transpose(mat)
```


</details>


<!-- Computational -->
<details>
<summary> Computational </summary>

```matlab
a = [1; 1; 1];
b = [3; 3; 3];
```

```matlab
a + b
```

```matlab
a - b
```

```matlab
a .* b
```

```matlab
a ./ b
```

```matlab
5 + a
```

```matlab
5 - a
```

```matlab
5 .* a
```

```matlab
5 ./ a
```

```matlab
b.^2
```
```matlab
mat3 = [1, 2];
mat4 = [1, 2, 3;
        4, 5, 6];
```

```matlab
mat3 * mat4
```

```matlab
cos(a)
```

```matlab
acos(a./a)
```

```matlab
R1 = 5 * exp(1i * [0;0;0;0]);
R2 = 8 * exp(1i * [0; 1; 2; 3].*pi/180);
D = R1 - R2;
```

```matlab
d = vecnorm(D,2,2)
```

```matlab
tD = angle(D)
```

</details>

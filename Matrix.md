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

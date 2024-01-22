<!-- create a function -->
<details>
<summary> create a function </summary>

```matlab
function say_hi(name, age)
    disp(['Hello ', name, ', you are ', num2str(age)])
end
```

</details>


<!-- invoke -->
<details>
<summary> invoke </summary>

```matlab
say_hi('Mike', 35)
```

</details>


<!-- return -->
<details>
<summary> return </summary>

```matlab
cube(3)

function result = cube(num)
    result = num*num*num;
end
```

```matlab
[first, ~, third] = value_return(1, 2, 3)

function [first, second, third] = value_return(k, j, h)
   first = k;
   second = j;
   third = h;
end
```


</details>


<!-- argument -->
<details>
<summary> argument </summary>

```matlab
func1([1, 2, 3], "hello")

function func1(varargin)
    varargin
end
```

</details>



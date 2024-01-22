<!-- break -->
<details>
<summary> break </summary>

```matlab
while i < 4
    if i == 3
        break;
    end
    disp(['User ', num2str(i), ' is registered. '])
    i = i + 1;
end
fprintf("it's out of the  while bound")
```

```matlab
for i = 1:2:6
    if i == 3
        break;
    end
    disp(['User ', num2str(i), ' is registered. '])
end
fprintf("it's out of the  for bound")
```


</details>


<!-- continue -->
<details>
<summary> continue </summary>

```matlab
i = 1;
while i < 4
    if i == 3
        i = i + 1;
        continue;
    end
    disp(['User ', num2str(i), ' is registered. '])
    i = i + 1;
end
fprintf("it's out of the  while bound")
```

```matlab
for i = 1:2:6
    if i == 3
        continue;
    end
    disp(['User ', num2str(i), ' is registered. '])
end
fprintf("it's out of the  for bound")
```



</details>



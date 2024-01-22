<!-- Create Structure -->
<details>
<summary> Create structure </summary>

```matlab
empty_str.height = []
empty_str.weight = []
```

</details>


<!-- Repeat -->
<details>
<summary> Repeat </summary>

```matlab
teenage_person = repmat(empty_str, 10, 1)
```

</details>


<!-- Manipulation -->
<details>
<summary> Manipulation </summary>

```matlab
for i = 1:10
    teenage_person(i).height = randi([100 150]);
    teenage_person(i).weight = randi([15 50]);
    BMI = teenage_person(i).weight / (teenage_person(i).height*0.01)^2;
end
```

</details>


<!-- Sort -->
<details>
<summary> Sort </summary>

```matlab
[BMI, sortorder] = sort(BMI)
```

</details>

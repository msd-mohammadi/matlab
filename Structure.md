#   Create Structure
```matlab
empty_str.height = []
empty_str.weight = []
```

#   Repeat
```matlab
teenage_person = repmat(empty_str, 10, 1)
```

#   Manipulation
```matlab
for i = 1:10
    teenage_person(i).height = randi([100 150]);
    teenage_person(i).weight = randi([15 50]);
    BMI = teenage_person(i).weight / (teenage_person(i).height*0.01)^2;
end
```

#   Sort
```matlab
[BMI, sortorder] = sort(BMI)
```

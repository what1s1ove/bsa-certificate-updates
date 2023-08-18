# BSA Certificate Updates

```
GRADUATION_STATUS =
  IF studentGrade >= 3 AND < 3.80 THEN 'Satisfactorily'
  OTHERWISE IF studentGrade >= 3.80 AND < 4.60 THEN 'Well'
  OTHERWISE IF studentGrade >= 4.60 THEN 'Successfully'
```

```
PROJECT_PASS_STATUS =
  IF isQualityCriteriaPassed = true THEN 'and defended the final project on'
  OTHERWISE ''
```

`{{ GRADUATION_STATUS }}` completed `{{ PROJECT_PASS_STATUS }}` JS course at Binary Studio Academy in January-April, 2023

Examples:

```
studentGrade = 3.6
GRADUATION_STATUS = Satisfactorily

isQualityCriteriaPassed = false
PROJECT_PASS_STATUS = ''
```

*Satisfactorily* completed JS course at Binary Studio Academy in January-April, 2023

___

```
studentGrade = 4.40
GRADUATION_STATUS = Well

isQualityCriteriaPassed = true
PROJECT_PASS_STATUS = 'and defended the final project on'
```

*Well* completed *and defended the final project on* JS course at Binary Studio Academy in January-April, 2023

___

```
studentGrade = 4.80
GRADUATION_STATUS = Well

isQualityCriteriaPassed = true
PROJECT_PASS_STATUS = 'and defended the final project on'
```

*Successfully* completed *and defended the final project on* JS course at Binary Studio Academy in January-April, 2023

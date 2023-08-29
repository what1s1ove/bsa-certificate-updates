# BSA Certificate Updates

<p align="center">
  <img src="./assets/img/example.png" alt="Example.">
</p>

## Calculations

```
GRADUATION_STATUS =
  IF studentGrade >= 0 AND < 3.79 THEN ''
  OTHERWISE IF studentGrade >= 3.80 AND < 4.59 THEN 'High'
  OTHERWISE IF studentGrade >= 4.60 THEN 'Highest'
```

```
PROJECT_PASS_STATUS =
  IF isQualityCriteriaPassed = true THEN 'and defended the final project on'
  OTHERWISE ''
```

for completing `{{ PROJECT_PASS_STATUS }}` the JS course at Binary Studio Academy With `{{ GRADUATION_STATUS }}` Honors in January-April 2023

## Examples

- ### Example 1

  #### Payload
  ```
  studentGrade = 3.60
  GRADUATION_STATUS = ''

  isQualityCriteriaPassed = false
  PROJECT_PASS_STATUS = ''
  ```

  #### Result
  > for completing the JS course at Binary Studio Academy With Honors in January-April 2023

___

- ### Example 2

  #### Payload
  ```
  studentGrade = 4.40
  GRADUATION_STATUS = 'High'

  isQualityCriteriaPassed = true
  PROJECT_PASS_STATUS = 'and defended the final project on'
  ```

  #### Result
  > for completing *and defended the final project on* the JS course at Binary Studio Academy With *High* Honors in January-April 2023

___

- ### Example 3

  #### Payload
  ```
  studentGrade = 4.80
  GRADUATION_STATUS = 'Highest'

  isQualityCriteriaPassed = true
  PROJECT_PASS_STATUS = 'and defended the final project on'
  ```

  #### Result
  > for completing *and defended the final project on* the JS course at Binary Studio Academy With *Highest* Honors in January-April 2023

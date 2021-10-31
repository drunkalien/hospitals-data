# hospitals-data

## How to contribute

In order to contribute to this repository first you must have a github account. Then clone this repository to your machine and start editing. First you should create an object of the district with its ***postal code, district name, postal codes of neighbouring districts and an array of hospitals*** inside hospitals array each hospital is represented as an object with following fields: ***postcode of the district where the hospital is located, name of hospital, type of hospital (ex.: Dental) and address of hospital***.


Object should be in this form:

```
[
  {
    "postCode": 100096,
    "district": "Chilonzor",
    "neighbours": [10001, 10002, 10003],
    "hospitals": [
      {
        "postCode": 100096,
        "name": "NAME_OF_HOSPITAL",
        "type": "TYPE_OF_HOSPITAL",
        "address": "ADDRESS_OF_HOSPITAL",
      },
      {
        "postCode": 100096,
        "name": "NAME_OF_HOSPITAL2",
        "type": "TYPE_OF_HOSPITAL2",
        "address": "ADDRESS_OF_HOSPITAL2",
      },
    ]
  },
  
  {
    "postCode": 100114,
    "district": "Yunusabad",
    "neighbours": [10001, 10002, 10003],
    "hospitals": [
      {    
        "postCode": 100114,
        "name": "NAME_OF_HOSPITAL",
        "type": "TYPE_OF_HOSPITAL",
        "address": "ADDRESS_OF_HOSPITAL",
      },
      {
        "postCode": 100114,
        "name": "NAME_OF_HOSPITAL2",
        "type": "TYPE_OF_HOSPITAL2",
        "address": "ADDRESS_OF_HOSPITAL2",
      },
    ]
  },
]
```

After making changes you should create pull request and wait for feedback on your changes.

## Requirements

- Git
- GitHub account

## Materials

- Git: https://www.youtube.com/watch?v=USjZcfj8yxE
- Pull request: https://www.youtube.com/watch?v=For9VtrQx58
- How to make pull request: https://opensource.com/article/19/7/create-pull-request-github

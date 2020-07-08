---
layout: default
title: Input
permalink: /docs/input
has_children: false
---

# Input Fields


#### Input

```
<vca-input errorMsg="error" v-model="value" :rules="$v.value">
    content
</vca-input>
```

#### Money Input

```
<vca-money-input v-model="money" :amount="money" :rules="$v.value" select/>
```
Edit money datatype. With select the input provide a dropsdown for currency selection. Default the currency will display as label.

Money:
 ```
 money: {
     amount: 0, //int in cents
     currency: "EUR" //currenry tag
 }
```

List of Currency. Use select option for selectable list:
 ```
 currencies: [
     {
         label: '€',
         value: 'EUR'
     }
 ]
```

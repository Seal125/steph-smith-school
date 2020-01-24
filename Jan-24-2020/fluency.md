Use list comprehensions to answer the following:

1. Create a function, `halved` that takes an list of numbers and returns an new list consisting of those numbers, halved.

2. Create a function, `only_positive`, that takes an list of numbers and returns a new list consisting only of the positive numbers.

3. Write a function, `total`, that takes an list of numbers and returns the sum of those numbers.

4. Create a function called `stripped_strings` that takes an list of strings and returns a new list of the strings with all non-alphanumeric characters removed.

5. Create function, `find_special` that takes an list of words and returns the index of the first occurrence of the word "special". If the word "special" is not present, it should return, -1.

6. Create a function called `valid_contacts`. This function takes an list of contact dictionaries. It should return an list of only contact objects that have a phone_number that is a 10-digit string.

```
contacts = [
  {"name": 'Reuben', "phone_number": '9196218777'},
  {"name": 'Laisha', "phone_number": '0123334766'},
  {"name": 'Cielo', "phone_number": '764'},
  {"name": 'Maya', "phone_number": '7653324599'}
]

valid_contacts(contacts) == [
  {name: 'Reuben', "phone_number": '9196218777'},
  {name: 'Laisha', "phone_number": '0123334766'},
  {name: 'Maya', "phone_number": '7653324599'}
]
```

7. Create a function, `contact_names`, that takes an list of contact objects and returns an list of contact names.

```
 contacts = [
  {name: 'Reuben', "phone_number": '9196218777'},
  {name: 'Laisha', "phone_number": '0123334766'},
  {name: 'Cielo', "phone_number": '764'},
  {name: 'Maya', "phone_number": '7653324599'}
]

contact_names(contacts) == ['Reuben', 'Laisha', 'Cielo', 'Maya']
```
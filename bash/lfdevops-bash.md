# Find yourself at home

#### Extract number from string
```
#!/bin/bash
string="The price of the product is $10.99"
number=$(echo "$string" | tr -cd '[:digit:].')
echo "Number: $number"
```

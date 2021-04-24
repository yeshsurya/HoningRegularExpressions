<h1>HoningRegularExpressions | Carefully chosen recepies to master regular expressions</h1>
<br/>
<h2> Regex to check if given string is a valid email address </h2>
<br/>

```
regex = '^(\w|\.|\_|\-)+[@](\w|\_|\-|\.)+[.]\w{2,3}$'
if(re.search(regex, email)):
  print("Valid Email")
else:
  print("Invalid Email")
```


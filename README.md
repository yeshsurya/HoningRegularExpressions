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
<h2> Regex to extract all numbers from a given string </h2>
<br/>

```
regex = r'\d+'
search_result = re.findall(regex, test_string)
result = list(map(int, search_result))
```
<h2> Regex to check if given string is a valid URL </h2>
<br/>

```
regex = r'((http|https)://)(www.)?[a-zA-Z0-9@:%._\\+~#?&//=]{2,256}\\.[a-z]{2,6}\\b([-a-zA-Z0-9@:%._\\+~#?&//=]*)'
if(regex_match(regex, test_string)):
  print("Valid URL")
else:
  print("Invalid URL")
```
<h2> Regex to remove whitespaces in python </h2>
<br/>

```
regex = r'^\s+'
re.sub(regex, "", demo)
```

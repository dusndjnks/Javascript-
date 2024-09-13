## 1.Write short notes on string methodes with code examples
## toLowercase(),toUppercase(),substring(),replace(),trim(),split(),slice() 

### toLowerCase()
#### The toLowerCase() method converts a string to lowercase letters.
#### eg:let src=("CINEMA")
#### console.log(src.toLowerCase());

### touppercase()
#### The toUpperCase() method converts a string to uppercase letters.
#### let src=("cinema")
#### console.log(src.toUpperCase());
### substring()
#### The substring() method extracts characters from start to end (exclusive). The substring() method does not change the original string. If start is greater than end, arguments are swapped: (4, 1) = (1, 4). Start or end values less than 0, are treated as 0.
#### eg:let src=("cinema")
#### console.log(src.substring(3,5));
#### replace()
####  let text = " paris is a beautiful place ";
#### console.log(text.replace("beautiful", "wonderful"));
#### trim()
#### The trim method in JavaScript is a built-in string method that removes whitespace characters from the beginning and end of a string. 
#### eg:let text = " paris is a beautiful place ";
#### console.log(text.trim());
#### split()
#### In JavaScript, the split method allows you to split the string into an array of substrings based on a given pattern.
#### eg:let text = "beautiful";
#### console.log(text.split(""));
#### slice()
####  The slice() method returns selected elements in an array, as a new array. 
#### const fruits = ["Banana", "Orange", "Lemon", "Apple", "Mango"];
#### console.log(fruits.slice(1,3));

## 2.create a simple app that takes the user’s name and greets him/her after capitalizing the first letter of the user’s name and changing the rest of the letters into lowercase 
### (toUpperCase(), toLowerCase(), slice(), length property.string cancatenation)

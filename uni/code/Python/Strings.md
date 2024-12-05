**String Indexing:**
	Indexing refers to the way characters in a string are sorted, a string is comparable to an list, where every character in the string is an item in the list, with its own indexed position.
	The index of a string is immutable (Unable to be changed)
	0-based indexing, meaning it starts counting at zero.
	![[String Indexing.png]]

**String Slicing:**
	Strings can be 'sliced' by using their indexes, this pulls the characters of the string that are within the given index range.
	`string[start:end]`
	This selects every character in the string from the start index up to but not including the end index.
	The start or end of the range can be left blank to indicate the start or end of the string.
	Negative index can also be used to define the range.

**String Operations:**
	Concatenation
		+ Used to add to a string, can be variables or other strings
	Repetition
		* Used to multiply the string x amount of times
	len() function
		In-built function used to find the length of a string
	in operator
		Checks if given value is in the variable and returns true or false
		`string1 = "Hello my name is Blank"`
		`print("is" in string1)`
		This prints true because "is" is in string1
**ALL OF THESE OPERATORS ALSO WORK WITH LISTS**

**String Methods:**
	These are only a few functions for strings
	split()
		Splits a string into separate substrings in a list based on the separator value given. The separator value is removed from the strings. The default separator is white space or 
		\n (new line), \t (tab), \r , \f or spaces. This can be used to make lists from data.
		`text = "hello"`
		`split_text = text.split("l")`
		`split1 = split_text[0]`
		`split2 = split_text[1]`
		`print(split1, split2)`
		This outputs "heo"
	replace()
	upper()
		Converts to uppercase
	lower()
		Converts to lowercase
	chr(int)
		Gives the character that corresponds to given integer
	ord(string)
		Gives the int that corresponds with given character
	string.count("String")
		Counts how many times the given string value appears in the string variable
	string.islower()
	string.isupper()
	string.istitle()
		Returns true if every first letter is capitalised
	string.isalpha()
		Returns true if characters are all letters
	string.isdigit()
		Returns true if characters are all digits
**String Formatting:**
	A Formatted String Literal or f-string is a string with fields that can be replaced, these fields are show by expressions defined within {}. This can also be done with the format() method. Any string can be formatted, not just the print() method.
	![[f-string.png]]
	![[format() method.png]]
	-
	**Format specifiers** can be added inside {} using : in format `{value:<6.2f}` where the 6 is the minimum length of the string (padding with whitespace if too short) and .2f is the significant figures the value given goes to. (left)< or >(right justified. rjust()) decide what side of the value any whitespace is added to.
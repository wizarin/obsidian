**How to approach a problem:**
	Analyse problem
	Define specification - The variables involved in the problem
	Design algorithm

**Features of High Quality Code:**
	**Readable:**
		Good naming convention - snake_case (python standard)
		Good use of variables and variable(and function) names
			names have to be legal, only begins with letter or underscore (not numbers). Only contain letters, underscores or digits.
		Using whitespace - Standard conventions:
			Two blank lines between function definitions
			Single space either side of assignment symbols and operators
			No space between names and brackets or before colons
			79 character limit for each line (python standard) split between lines using () or \ at line end
		Documentation
			Comments-
			to identify contents, author and date of python files
			to explain code that might not be obvious on reading
			too many make it more difficult to read
		Avoiding overly complex, or repetitive code
	**Correct**:
		Testing code, you can work out test data before the 'design algorithm' step

**Statement**
	A program is a set of statements that are executed in order, statements often include expressions
**Expression**
	An expression is evaluated by the computer to give a value of a specific data type
**Class**
	A class is a data type, this can be built-in or written. When that class is called it **constructs** an **object** of that class. `variable = class(values)`
**Object**
	An instance of a class. Object properties can be accessed and (sometimes) changed using dot notation. 
	`variable.attribute` or `variable.attribute(changedvalue)`
	Objects can also call methods(functions) from the class in the same notation.
	`variable.method()`
	Object values can be represented using this diagram, where the boxes are objects of type Circle and Point.
	`c = Circle(Point(20, 30), 10)`
![[Object Diagram.png]]
	`d = c`
	When multiple variables point to the same object it is know as object aliasing.
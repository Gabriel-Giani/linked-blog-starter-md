### Example of instructor relation

### Attributes
- set of allowed values for each attribute is called the **domain** of the attribute.


### Relations are unordered
- order of tuples is irrelevant (tuples may be stored in an arbitrary order)
- example: instructor relation with unordered tuples
- include img

### Database Schema
- database schema - logical structure of the database
- database instance - a snapshot of the data in the database at a give instant in time.
- Example:
	- schema: *instructor (ID, name, dept_name, salary)*
	- example:

### Keys
- let K (slide 8)
- K is a **superkey** of R if values for K are sufficient to identify a unique tuple of each possible realtion r(R)
	- Example: {ID} and {ID, name} are both superkeys of *instructor*
- Superkey K is a **candidate key** if K is minimal
	Example: {ID}

### Select operation

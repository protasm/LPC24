<html>
  <body>
    <p>1. Introduction
    <p>1.1. Organization of the Specification
    <p>1.2. Example Programs
    <p>1.3. Notation
    <p>1.4. Relationship to Predefined Classes and Interfaces
    <p>1.5. Preview Features
    <p>1.6. Feedback
    <p>1.7. References
    <p>2. Grammars
    <p>2.1. Context-Free Grammars
    <p>2.2. The Lexical Grammar
    <p>2.3. The Syntactic Grammar
    <p>2.4. Grammar Notation
    <p>3. Lexical Structure
    <p>3.1. Unicode
    <p>3.2. Lexical Translations
    <p>3.3. Unicode Escapes
    <p>3.4. Line Terminators
    <p>3.5. Input Elements and Tokens
    <p>3.6. White Space
    <p>3.7. Comments
    <p>3.8. Identifiers
    <p>3.9. Keywords
    <p>3.10. Literals
    <p>3.10.1. Integer Literals
    <p>3.10.2. Floating-Point Literals
    <p>3.10.3. Boolean Literals
    <p>3.10.4. Character Literals
    <p>3.10.5. String Literals
    <p>3.10.6. Text Blocks
    <p>3.10.7. Escape Sequences
    <p>3.10.8. The Null Literal
    <p>3.11. Separators
    <p>3.12. Operators
    <p>4. Types, Values, and Variables
    <p>4.1. The Kinds of Types and Values
    <p>4.2. Primitive Types and Values
    <p>4.2.1. Integral Types and Values
    <p>4.2.2. Integer Operations
    <p>4.2.3. Floating-Point Types and Values
    <p>4.2.4. Floating-Point Operations
    <p>4.2.5. The boolean Type and boolean Values
    <p>4.3. Reference Types and Values
    <p>4.3.1. Objects
    <p>4.3.2. The Class Object
    <p>4.3.3. The Class String
    <p>4.3.4. When Reference Types Are the Same
    <p>4.4. Type Variables
    <p>4.5. Parameterized Types
    <p>4.5.1. Type Arguments of Parameterized Types
    <p>4.5.2. Members and Constructors of Parameterized Types
    <p>4.6. Type Erasure
    <p>4.7. Reifiable Types
    <p>4.8. Raw Types
    <p>4.9. Intersection Types
    <p>4.10. Subtyping
    <p>4.10.1. Subtyping among Primitive Types
    <p>4.10.2. Subtyping among Class and Interface Types
    <p>4.10.3. Subtyping among Array Types
    <p>4.10.4. Least Upper Bound
    <p>4.10.5. Type Projections
    <p>4.11. Where Types Are Used
    <p>4.12. Variables
    <p>4.12.1. Variables of Primitive Type
    <p>4.12.2. Variables of Reference Type
    <p>4.12.3. Kinds of Variables
    <p>4.12.4. final Variables
    <p>4.12.5. Initial Values of Variables
    <p>4.12.6. Types, Classes, and Interfaces
    <p>5. Conversions and Contexts
    <p>5.1. Kinds of Conversion
    <p>5.1.1. Identity Conversion
    <p>5.1.2. Widening Primitive Conversion
    <p>5.1.3. Narrowing Primitive Conversion
    <p>5.1.4. Widening and Narrowing Primitive Conversion
    <p>5.1.5. Widening Reference Conversion
    <p>5.1.6. Narrowing Reference Conversion
    <p>5.1.6.1. Allowed Narrowing Reference Conversion
    <p>5.1.6.2. Checked and Unchecked Narrowing Reference Conversions
    <p>5.1.6.3. Narrowing Reference Conversions at Run Time
    <p>5.1.7. Boxing Conversion
    <p>5.1.8. Unboxing Conversion
    <p>5.1.9. Unchecked Conversion
    <p>5.1.10. Capture Conversion
    <p>5.1.11. String Conversion
    <p>5.1.12. Forbidden Conversions
    <p>5.2. Assignment Contexts
    <p>5.3. Invocation Contexts
    <p>5.4. String Contexts
    <p>5.5. Casting Contexts
    <p>5.6. Numeric Contexts
    <p>5.7. Testing Contexts
    <p>6. Names
    <p>6.1. Declarations
    <p>6.2. Names and Identifiers
    <p>6.3. Scope of a Declaration
    <p>6.3.1. Scope for Pattern Variables in Expressions
    <p>6.3.1.1. Conditional-And Operator &&
    <p>6.3.1.2. Conditional-Or Operator ||
    <p>6.3.1.3. Logical Complement Operator !
    <p>6.3.1.4. Conditional Operator ? :
    <p>6.3.1.5. Pattern Match Operator instanceof
    <p>6.3.1.6. switch Expressions
    <p>6.3.1.7. Parenthesized Expressions
    <p>6.3.2. Scope for Pattern Variables in Statements
    <p>6.3.2.1. Blocks
    <p>6.3.2.2. if Statements
    <p>6.3.2.3. while Statements
    <p>6.3.2.4. do Statements
    <p>6.3.2.5. for Statements
    <p>6.3.2.6. switch Statements
    <p>6.3.2.7. Labeled Statements
    <p>6.3.3. Scope for Pattern Variables in case Labels
    <p>6.4. Shadowing and Obscuring
    <p>6.4.1. Shadowing
    <p>6.4.2. Obscuring
    <p>6.5. Determining the Meaning of a Name
    <p>6.5.1. Syntactic Classification of a Name According to Context
    <p>6.5.2. Reclassification of Contextually Ambiguous Names
    <p>6.5.3. Meaning of Module Names and Package Names
    <p>6.5.3.1. Simple Package Names
    <p>6.5.3.2. Qualified Package Names
    <p>6.5.4. Meaning of PackageOrTypeNames
    <p>6.5.4.1. Simple PackageOrTypeNames
    <p>6.5.4.2. Qualified PackageOrTypeNames
    <p>6.5.5. Meaning of Type Names
    <p>6.5.5.1. Simple Type Names
    <p>6.5.5.2. Qualified Type Names
    <p>6.5.6. Meaning of Expression Names
    <p>6.5.6.1. Simple Expression Names
    <p>6.5.6.2. Qualified Expression Names
    <p>6.5.7. Meaning of Method Names
    <p>6.5.7.1. Simple Method Names
    <p>6.6. Access Control
    <p>6.6.1. Determining Accessibility
    <p>6.6.2. Details on protected Access
    <p>6.6.2.1. Access to a protected Member
    <p>6.6.2.2. Access to a protected Constructor
    <p>6.7. Fully Qualified Names and Canonical Names
    <p>7. Packages and Modules
    <p>7.1. Package Members
    <p>7.2. Host Support for Modules and Packages
    <p>7.3. Compilation Units
    <p>7.4. Package Declarations
    <p>7.4.1. Named Packages
    <p>7.4.2. Unnamed Packages
    <p>7.4.3. Package Observability and Visibility
    <p>7.5. Import Declarations
    <p>7.5.1. Single-Type-Import Declarations
    <p>7.5.2. Type-Import-on-Demand Declarations
    <p>7.5.3. Single-Static-Import Declarations
    <p>7.5.4. Static-Import-on-Demand Declarations
    <p>7.6. Top Level Class and Interface Declarations
    <p>7.7. Module Declarations
    <p>7.7.1. Dependences
    <p>7.7.2. Exported and Opened Packages
    <p>7.7.3. Service Consumption
    <p>7.7.4. Service Provision
    <p>7.7.5. Unnamed Modules
    <p>7.7.6. Observability of a Module
    <p>8. Classes
    <p>8.1. Class Declarations
    <p>8.1.1. Class Modifiers
    <p>8.1.1.1. abstract Classes
    <p>8.1.1.2. sealed, non-sealed, and final Classes
    <p>8.1.1.3. strictfp Classes
    <p>8.1.1.4. static Classes
    <p>8.1.2. Generic Classes and Type Parameters
    <p>8.1.3. Inner Classes and Enclosing Instances
    <p>8.1.4. Superclasses and Subclasses
    <p>8.1.5. Superinterfaces
    <p>8.1.6. Permitted Direct Subclasses
    <p>8.1.7. Class Body and Member Declarations
    <p>8.2. Class Members
    <p>8.3. Field Declarations
    <p>8.3.1. Field Modifiers
    <p>8.3.1.1. static Fields
    <p>8.3.1.2. final Fields
    <p>8.3.1.3. transient Fields
    <p>8.3.1.4. volatile Fields
    <p>8.3.2. Field Initialization
    <p>8.3.3. Restrictions on Field References in Initializers
    <p>8.4. Method Declarations
    <p>8.4.1. Formal Parameters
    <p>8.4.2. Method Signature
    <p>8.4.3. Method Modifiers
    <p>8.4.3.1. abstract Methods
    <p>8.4.3.2. static Methods
    <p>8.4.3.3. final Methods
    <p>8.4.3.4. native Methods
    <p>8.4.3.5. strictfp Methods
    <p>8.4.3.6. synchronized Methods
    <p>8.4.4. Generic Methods
    v8.4.5. Method Result
    <p>8.4.6. Method Throws
    <p>8.4.7. Method Body
    <p>8.4.8. Inheritance, Overriding, and Hiding
    <p>8.4.8.1. Overriding (by Instance Methods)
    <p>8.4.8.2. Hiding (by Class Methods)
    <p>8.4.8.3. Requirements in Overriding and Hiding
    <p>8.4.8.4. Inheriting Methods with Override-Equivalent Signatures
    <p>8.4.9. Overloading
    <p>8.5. Member Class and Interface Declarations
    <p>8.6. Instance Initializers
    <p>8.7. Static Initializers
    <p>8.8. Constructor Declarations
    <p>8.8.1. Formal Parameters
    <p>8.8.2. Constructor Signature
    <p>8.8.3. Constructor Modifiers
    <p>8.8.4. Generic Constructors
    <p>8.8.5. Constructor Throws
    <p>8.8.6. The Type of a Constructor
    <p>8.8.7. Constructor Body
    <p>8.8.7.1. Explicit Constructor Invocations
    <p>8.8.8. Constructor Overloading
    <p>8.8.9. Default Constructor
    <p>8.8.10. Preventing Instantiation of a Class
    <p>8.9. Enum Classes
    <p>8.9.1. Enum Constants
    <p>8.9.2. Enum Body Declarations
    <p>8.9.3. Enum Members
    <p>8.10. Record Classes
    <p>8.10.1. Record Components
    <p>8.10.2. Record Body Declarations
    <p>8.10.3. Record Members
    <p>8.10.4. Record Constructor Declarations
    <p>8.10.4.1. Normal Canonical Constructors
    <p>8.10.4.2. Compact Canonical Constructors
    <p>9. Interfaces
    <p>9.1. Interface Declarations
    <p>9.1.1. Interface Modifiers
    <p>9.1.1.1. abstract Interfaces
    <p>9.1.1.2. strictfp Interfaces
    <p>9.1.1.3. static Interfaces
    <p>9.1.1.4. sealed and non-sealed Interfaces
    <p>9.1.2. Generic Interfaces and Type Parameters
    <p>9.1.3. Superinterfaces and Subinterfaces
    <p>9.1.4. Permitted Direct Subclasses and Subinterfaces
    <p>9.1.5. Interface Body and Member Declarations
    <p>9.2. Interface Members
    <p>9.3. Field (Constant) Declarations
    <p>9.3.1. Initialization of Fields in Interfaces
    <p>9.4. Method Declarations
    <p>9.4.1. Inheritance and Overriding
    <p>9.4.1.1. Overriding (by Instance Methods)
    <p>9.4.1.2. Requirements in Overriding
    <p>9.4.1.3. Inheriting Methods with Override-Equivalent Signatures
    <p>9.4.2. Overloading
    <p>9.4.3. Interface Method Body
    <p>9.5. Member Class and Interface Declarations
    <p>9.6. Annotation Interfaces
    <p>9.6.1. Annotation Interface Elements
    <p>9.6.2. Defaults for Annotation Interface Elements
    <p>9.6.3. Repeatable Annotation Interfaces
    <p>9.6.4. Predefined Annotation Interfaces
    <p>9.6.4.1. @Target
    <p>9.6.4.2. @Retention
    <p>9.6.4.3. @Inherited
    <p>9.6.4.4. @Override
    <p>9.6.4.5. @SuppressWarnings
    <p>9.6.4.6. @Deprecated
    <p>9.6.4.7. @SafeVarargs
    <p>9.6.4.8. @Repeatable
    <p>9.6.4.9. @FunctionalInterface
    <p>9.7. Annotations
    <p>9.7.1. Normal Annotations
    <p>9.7.2. Marker Annotations
    <p>9.7.3. Single-Element Annotations
    <p>9.7.4. Where Annotations May Appear
    <p>9.7.5. Multiple Annotations of the Same Interface
    <p>9.8. Functional Interfaces
    <p>9.9. Function Types
    <p>10. Arrays
    <p>10.1. Array Types
    <p>10.2. Array Variables
    <p>10.3. Array Creation
    <p>10.4. Array Access
    <p>10.5. Array Store Exception
    <p>10.6. Array Initializers
    <p>10.7. Array Members
    <p>10.8. Class Objects for Arrays
    <p>10.9. An Array of Characters Is Not a String
    <p>11. Exceptions
    <p>11.1. The Kinds and Causes of Exceptions
    <p>11.1.1. The Kinds of Exceptions
    <p>11.1.2. The Causes of Exceptions
    <p>11.1.3. Asynchronous Exceptions
    <p>11.2. Compile-Time Checking of Exceptions
    <p>11.2.1. Exception Analysis of Expressions
    <p>11.2.2. Exception Analysis of Statements
    <p>11.2.3. Exception Checking
    <p>11.3. Run-Time Handling of an Exception
    <p>12. Execution
    <p>12.1. Java Virtual Machine Startup
    <p>12.1.1. Load the Class Test
    <p>12.1.2. Link Test: Verify, Prepare, (Optionally) Resolve
    <p>12.1.3. Initialize Test: Execute Initializers
    <p>12.1.4. Invoke Test.main
    <p>12.2. Loading of Classes and Interfaces
    <p>12.2.1. The Loading Process
    <p>12.2.2. Class Loader Consistency
    <p>12.3. Linking of Classes and Interfaces
    <p>12.3.1. Verification of the Binary Representation
    <p>12.3.2. Preparation of a Class or Interface
    <p>12.3.3. Resolution of Symbolic References
    <p>12.4. Initialization of Classes and Interfaces
    <p>12.4.1. When Initialization Occurs
    <p>12.4.2. Detailed Initialization Procedure
    <p>12.5. Creation of New Class Instances
    <p>12.6. Finalization of Class Instances
    <p>12.6.1. Implementing Finalization
    <p>12.6.2. Interaction with the Memory Model
    <p>12.7. Unloading of Classes and Interfaces
    <p>12.8. Program Exit
    <p>13. Binary Compatibility
    <p>13.1. The Form of a Binary
    <p>13.2. What Binary Compatibility Is and Is Not
    <p>13.3. Evolution of Packages and Modules
    <p>13.4. Evolution of Classes
    <p>13.4.1. abstract Classes
    <p>13.4.2. sealed, non-sealed, and final Classes
    <p>13.4.2.1. sealed Classes
    <p>13.4.2.2. non-sealed Classes
    <p>13.4.2.3. final Classes
    <p>13.4.3. public Classes
    <p>13.4.4. Superclasses and Superinterfaces
    <p>13.4.5. Class Type Parameters
    <p>13.4.6. Class Body and Member Declarations
    <p>13.4.7. Access to Members and Constructors
    <p>13.4.8. Field Declarations
    <p>13.4.9. final Fields and static Constant Variables
    <p>13.4.10. static Fields
    <p>13.4.11. transient Fields
    <p>13.4.12. Method and Constructor Declarations
    <p>13.4.13. Method and Constructor Type Parameters
    <p>13.4.14. Method and Constructor Formal Parameters
    <p>13.4.15. Method Result Type
    <p>13.4.16. abstract Methods
    <p>13.4.17. final Methods
    <p>13.4.18. native Methods
    <p>13.4.19. static Methods
    <p>13.4.20. synchronized Methods
    <p>13.4.21. Method and Constructor Throws
    <p>13.4.22. Method and Constructor Body
    <p>13.4.23. Method and Constructor Overloading
    <p>13.4.24. Method Overriding
    <p>13.4.25. Static Initializers
    <p>13.4.26. Evolution of Enum Classes
    <p>13.4.27. Evolution of Record Classes
    <p>13.5. Evolution of Interfaces
    <p>13.5.1. public Interfaces
    <p>13.5.2. sealed and non-sealed Interfaces
    <p>13.5.3. Superinterfaces
    <p>13.5.4. Interface Members
    <p>13.5.5. Interface Type Parameters
    <p>13.5.6. Field Declarations
    <p>13.5.7. Interface Method Declarations
    <p>13.5.8. Annotation Interfaces
    <p>14. Blocks, Statements, and Patterns
    <p>14.1. Normal and Abrupt Completion of Statements
    <p>14.2. Blocks
    <p>14.3. Local Class and Interface Declarations
    <p>14.4. Local Variable Declarations
    <p>14.4.1. Local Variable Declarators and Types
    <p>14.4.2. Local Variable Declaration Statements
    <p>14.5. Statements
    <p>14.6. The Empty Statement
    <p>14.7. Labeled Statements
    <p>14.8. Expression Statements
    <p>14.9. The if Statement
    <p>14.9.1. The if-then Statement
    <p>14.9.2. The if-then-else Statement
    <p>14.10. The assert Statement
    <p>14.11. The switch Statement
    <p>14.11.1. Switch Blocks
    <p>14.11.1.1. Exhaustive Switch Blocks
    <p>14.11.1.2. Determining which Switch Label Applies at Run Time
    <p>14.11.2. The Switch Block of a switch Statement
    <p>14.11.3. Execution of a switch Statement
    <p>14.12. The while Statement
    <p>14.12.1. Abrupt Completion of while Statement
    <p>14.13. The do Statement
    <p>14.13.1. Abrupt Completion of do Statement
    <p>14.14. The for Statement
    <p>14.14.1. The basic for Statement
    <p>14.14.1.1. Initialization of for Statement
    <p>14.14.1.2. Iteration of for Statement
    <p>14.14.1.3. Abrupt Completion of for Statement
    <p>14.14.2. The enhanced for statement
    <p>14.15. The break Statement
    <p>14.16. The continue Statement
    <p>14.17. The return Statement
    <p>14.18. The throw Statement
    <p>14.19. The synchronized Statement
    <p>14.20. The try statement
    <p>14.20.1. Execution of try-catch
    <p>14.20.2. Execution of try-finally and try-catch-finally
    <p>14.20.3. try-with-resources
    <p>14.20.3.1. Basic try-with-resources
    <p>14.20.3.2. Extended try-with-resources
    <p>14.21. The yield Statement
    <p>14.22. Unreachable Statements
    <p>14.30. Patterns
    <p>14.30.1. Kinds of Patterns
    <p>14.30.2. Pattern Matching
    <p>14.30.3. Properties of Patterns
    <p>15. Expressions
    <p>15.1. Evaluation, Denotation, and Result
    <p>15.2. Forms of Expressions
    <p>15.3. Type of an Expression
    <p>15.4. Floating-point Expressions
    <p>15.5. Expressions and Run-Time Checks
    <p>15.6. Normal and Abrupt Completion of Evaluation
    <p>15.7. Evaluation Order
    <p>15.7.1. Evaluate Left-Hand Operand First
    <p>15.7.2. Evaluate Operands before Operation
    <p>15.7.3. Evaluation Respects Parentheses and Precedence
    <p>15.7.4. Argument Lists are Evaluated Left-to-Right
    <p>15.7.5. Evaluation Order for Other Expressions
    <p>15.8. Primary Expressions
    <p>15.8.1. Lexical Literals
    <p>15.8.2. Class Literals
    <p>15.8.3. this
    <p>15.8.4. Qualified this
    <p>15.8.5. Parenthesized Expressions
    <p>15.9. Class Instance Creation Expressions
    <p>15.9.1. Determining the Class being Instantiated
    <p>15.9.2. Determining Enclosing Instances
    <p>15.9.3. Choosing the Constructor and its Arguments
    <p>15.9.4. Run-Time Evaluation of Class Instance Creation Expressions
    <p>15.9.5. Anonymous Class Declarations
    <p>15.9.5.1. Anonymous Constructors
    <p>15.10. Array Creation and Access Expressions
    <p>15.10.1. Array Creation Expressions
    <p>15.10.2. Run-Time Evaluation of Array Creation Expressions
    <p>15.10.3. Array Access Expressions
    <p>15.10.4. Run-Time Evaluation of Array Access Expressions
    <p>15.11. Field Access Expressions
    <p>15.11.1. Field Access Using a Primary
    <p>15.11.2. Accessing Superclass Members using super
    <p>15.12. Method Invocation Expressions
    <p>15.12.1. Compile-Time Step 1: Determine Type to Search
    <p>15.12.2. Compile-Time Step 2: Determine Method Signature
    <p>15.12.2.1. Identify Potentially Applicable Methods
    <p>15.12.2.2. Phase 1: Identify Matching Arity Methods Applicable by Strict Invocation
    <p>15.12.2.3. Phase 2: Identify Matching Arity Methods Applicable by Loose Invocation
    <p>15.12.2.4. Phase 3: Identify Methods Applicable by Variable Arity Invocation
    <p>15.12.2.5. Choosing the Most Specific Method
    <p>15.12.2.6. Method Invocation Type
    <p>15.12.3. Compile-Time Step 3: Is the Chosen Method Appropriate?
    <p>15.12.4. Run-Time Evaluation of Method Invocation
    <p>15.12.4.1. Compute Target Reference (If Necessary)
    <p>15.12.4.2. Evaluate Arguments
    <p>15.12.4.3. Check Accessibility of Type and Method
    <p>15.12.4.4. Locate Method to Invoke
    <p>15.12.4.5. Create Frame, Synchronize, Transfer Control
    <p>15.13. Method Reference Expressions
    <p>15.13.1. Compile-Time Declaration of a Method Reference
    <p>15.13.2. Type of a Method Reference
    <p>15.13.3. Run-Time Evaluation of Method References
    <p>15.14. Postfix Expressions
    <p>15.14.1. Expression Names
    <p>15.14.2. Postfix Increment Operator ++
    <p>15.14.3. Postfix Decrement Operator --
    <p>15.15. Unary Operators
    <p>15.15.1. Prefix Increment Operator ++
    <p>15.15.2. Prefix Decrement Operator --
    <p>15.15.3. Unary Plus Operator +
    <p>15.15.4. Unary Minus Operator -
    <p>15.15.5. Bitwise Complement Operator ~
    <p>15.15.6. Logical Complement Operator !
    <p>15.16. Cast Expressions
    <p>15.17. Multiplicative Operators
    <p>15.17.1. Multiplication Operator *
    <p>15.17.2. Division Operator /
    <p>15.17.3. Remainder Operator %
    <p>15.18. Additive Operators
    <p>15.18.1. String Concatenation Operator +
    <p>15.18.2. Additive Operators (+ and -) for Numeric Types
    <p>15.19. Shift Operators
    <p>15.20. Relational Operators
    <p>15.20.1. Numerical Comparison Operators <, <=, >, and >=
    <p>15.20.2. The instanceof Operator
    <p>15.21. Equality Operators
    <p>15.21.1. Numerical Equality Operators == and !=
    <p>15.21.2. Boolean Equality Operators == and !=
    <p>15.21.3. Reference Equality Operators == and !=
    <p>15.22. Bitwise and Logical Operators
    <p>15.22.1. Integer Bitwise Operators &, ^, and |
    <p>15.22.2. Boolean Logical Operators &, ^, and |
    <p>15.23. Conditional-And Operator &&
    <p>15.24. Conditional-Or Operator ||
    <p>15.25. Conditional Operator ? :
    <p>15.25.1. Boolean Conditional Expressions
    <p>15.25.2. Numeric Conditional Expressions
    <p>15.25.3. Reference Conditional Expressions
    <p>15.26. Assignment Operators
    <p>15.26.1. Simple Assignment Operator =
    <p>15.26.2. Compound Assignment Operators
    <p>15.27. Lambda Expressions
    <p>15.27.1. Lambda Parameters
    <p>15.27.2. Lambda Body
    <p>15.27.3. Type of a Lambda Expression
    <p>15.27.4. Run-Time Evaluation of Lambda Expressions
    <p>15.28. switch Expressions
    <p>15.28.1. The Switch Block of a switch Expression
    <p>15.28.2. Run-Time Evaluation of switch Expressions
    <p>15.29. Constant Expressions
    <p>16. Definite Assignment
    <p>16.1. Definite Assignment and Expressions
    <p>16.1.1. Boolean Constant Expressions
    <p>16.1.2. Conditional-And Operator &&
    <p>16.1.3. Conditional-Or Operator ||
    <p>16.1.4. Logical Complement Operator !
    <p>16.1.5. Conditional Operator ? :
    <p>16.1.6. switch Expressions
    <p>16.1.7. Other Expressions of Type boolean
    <p>16.1.8. Assignment Expressions
    <p>16.1.9. Operators ++ and --
    <p>16.1.10. Other Expressions
    <p>16.2. Definite Assignment and Statements
    <p>16.2.1. Empty Statements
    <p>16.2.2. Blocks
    <p>16.2.3. Local Class and Interface Declarations
    <p>16.2.4. Local Variable Declaration Statements
    <p>16.2.5. Labeled Statements
    <p>16.2.6. Expression Statements
    <p>16.2.7. if Statements
    <p>16.2.8. assert Statements
    <p>16.2.9. switch Statements
    <p>16.2.10. while Statements
    <p>16.2.11. do Statements
    <p>16.2.12. for Statements
    <p>16.2.12.1. Initialization Part of for Statement
    <p>16.2.12.2. Incrementation Part of for Statement
    <p>16.2.13. break, yield, continue, return, and throw Statements
    <p>16.2.14. synchronized Statements
    <p>16.2.15. try Statements
    <p>16.3. Definite Assignment and Parameters
    <p>16.4. Definite Assignment and Array Initializers
    <p>16.5. Definite Assignment and Enum Constants
    <p>16.6. Definite Assignment and Anonymous Classes
    <p>16.7. Definite Assignment and Member Classes and Interfaces
    <p>16.8. Definite Assignment and Static Initializers
    <p>16.9. Definite Assignment, Constructors, and Instance Initializers
    <p>17. Threads and Locks
    <p>17.1. Synchronization
    <p>17.2. Wait Sets and Notification
    <p>17.2.1. Wait
    <p>17.2.2. Notification
    <p>17.2.3. Interruptions
    <p>17.2.4. Interactions of Waits, Notification, and Interruption
    <p>17.3. Sleep and Yield
    <p>17.4. Memory Model
    <p>17.4.1. Shared Variables
    <p>17.4.2. Actions
    <p>17.4.3. Programs and Program Order
    <p>17.4.4. Synchronization Order
    <p>17.4.5. Happens-before Order
    <p>17.4.6. Executions
    <p>17.4.7. Well-Formed Executions
    <p>17.4.8. Executions and Causality Requirements
    <p>17.4.9. Observable Behavior and Nonterminating Executions
    <p>17.5. final Field Semantics
    <p>17.5.1. Semantics of final Fields
    <p>17.5.2. Reading final Fields During Construction
    <p>17.5.3. Subsequent Modification of final Fields
    <p>17.5.4. Write-Protected Fields
    <p>17.6. Word Tearing
    <p>17.7. Non-Atomic Treatment of double and long
    <p>18. Type Inference
    <p>18.1. Concepts and Notation
    <p>18.1.1. Inference Variables
    <p>18.1.2. Constraint Formulas
    <p>18.1.3. Bounds
    <p>18.2. Reduction
    <p>18.2.1. Expression Compatibility Constraints
    <p>18.2.2. Type Compatibility Constraints
    <p>18.2.3. Subtyping Constraints
    <p>18.2.4. Type Equality Constraints
    <p>18.2.5. Checked Exception Constraints
    <p>18.3. Incorporation
    <p>18.3.1. Complementary Pairs of Bounds
    <p>18.3.2. Bounds Involving Capture Conversion
    <p>18.4. Resolution
    <p>18.5. Uses of Inference
    <p>18.5.1. Invocation Applicability Inference
    <p>18.5.2. Invocation Type Inference
    <p>18.5.2.1. Poly Method Invocation Compatibility
    <p>18.5.2.2. Additional Argument Constraints
    <p>18.5.3. Functional Interface Parameterization Inference
    <p>18.5.4. More Specific Method Inference
    <p>18.5.5. Record Pattern Type Inference
    <p>19. Syntax
  </body>
</html>
    

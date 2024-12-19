# JavaScript Loose Equality and Null/Undefined Handling

This repository demonstrates a common JavaScript error related to loose equality (==) and handling null or undefined values.

## The Bug
The `foo` function uses loose equality (==) to check for null or undefined inputs. While this works in some cases, it can lead to unexpected results due to JavaScript's type coercion.  The use of loose equality is problematic and should be replaced with strict equality. 

## The Solution
The solution involves replacing loose equality (==) with strict equality (===) which avoids type coercion. Strict equality ensures that both the value and the type of the operands are compared, preventing unexpected results.
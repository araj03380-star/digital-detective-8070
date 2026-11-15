# Mission 5 - Numbers and data

## 1. Task / objective
Perform manual base conversions, verify outputs via Python, build an automated number conversion script (`number_converter.py`), and explain text encoding.

## 2. Work completed
* Hand-calculated decimal, binary, and hexadecimal conversions.
* Verified results using Python's built-in functions (`bin()`, `hex()`, `int()`).
* Developed `number_converter.py` and tested it with multiple positive integers.
* Documented ASCII and UTF-8 text encoding principles.

## 3. Commands / tools used
* Python interactive shell and script execution (`python3 number_converter.py`).

## 4. My understanding
* **Number Systems**: Computers utilize base-2 (binary) for internal logic circuits, while humans use base-10 (decimal), and base-16 (hexadecimal) serves as a compact shorthand for binary data.
* **Text Encoding**: Standards like ASCII and UTF-8 map numerical byte sequences to human-readable characters.

## 5. Difficulties faced
Handling edge-case non-integer inputs gracefully in the Python script.

## 6. How I resolved them
Implemented `try-except` blocks to catch `ValueError` exceptions when parsing user inputs.

## 7. Evidence / files
* `number_converter.py` script and manual conversion working notes.

## 8. Commit details
* Commit message: "Build number converter and practise data representation"
* Pushed to GitHub: Yes
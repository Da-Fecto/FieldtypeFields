# FieldtypeFields

Fieldtype for storing field references with various filter possibilities.

### Admin

From the field config settings you can choose which Inputfield you want to use for field selection. 
There are also various settings to filter the fields shown in the inputfield.

### Output

Returns a FieldsArray when outputformatting is true when false a regular PHP array containing the field ids.
It will always return a FieldsArray or array even if the selected Inputfield is a single selection inputfield.

### Saving field references

You can save a FieldsArray or a regular PHP array containing the field ids.

### Thanks

- Arjen Blokzijl
- [Calago.nl](http://calago.nl)

### Requires

ProcessWire >= 3.0.39

### Support

- Nope, use on your own risk.

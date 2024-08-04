# tri-state-blazor-checkbox
A blazor component that wraps a checkbox and allows the indeterminate value to be used in addition to checked and unchecked.

Three properties to access the value of the checkbox are exposed:
1. Assigning an integer to the Value property
2. Assigning a nullable boolean to the ValueBool property, where null represents an indeterminate checkbox value
3. Assigning a boolean to the Checked property. This does not allow for setting it to the indeterminate value
4. Assigning a member of the StateEnum enum to the State property, the enum of which contains three members: Unchecked, Checked, and Indeterminate

ValueBool and State can be removed without affecting the rest of the component. 

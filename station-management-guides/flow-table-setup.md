# Flow Table Setup

Flow Tables are value lookup tables, taking data from one sensor as input, and outputting the corresponding value. Flow Tables require a Virtual Sensor to link the desired sensor values to the table. Flow tables can be used to measure flow rates in open water channels that require custom conversions that cannot be calculated with a standard flow formula. Note that in some cases a flow formula will be a better option and <span class="app-name"></span> provides several predefined flow formulas as well as the ability to create a custom flow formula with our [Algebraic Functions](algebraic-function-setup.md) feature.

### Flow Table Setup Steps

1. Navigate to the Station Management page for the station that you want to create the flow table for.
2. On the Station Management page click 'Data Transformations' from the side menu to expand the options and then select 'Flow Tables'.
3. Click the '+ Flow Table' button in the top right corner of the Flow Table Summary page.
4. Give your flow table a unique name and description and select your tables input and output units (e.g. input: Feet, output: Cubic Feet/Sec). Click 'Next'.
5. Begin adding rows to your flow table by providing an input and and output value. Click '+ New Row' to add it to the table. Repeat this for as many rows you need in your table.
6. To test your table click 'Test Flow Table'. The Test section will expand providing a means to test various input values and will return the output values based on your table.
7. Provide an input value and click the 'Test Input' button. Notice a new column has been added to your test results with the input and output value.
8. When your satisfied with your table and your test results, click the 'Submit' button to create the flow table. You should now see your flow table added to the list on the Flow Table Summary page.
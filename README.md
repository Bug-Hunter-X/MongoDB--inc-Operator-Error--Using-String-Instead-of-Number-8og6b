# MongoDB $inc Operator Error
This example demonstrates an uncommon error when using the `$inc` operator in MongoDB.  The `$inc` operator is used to increment a numerical field by a specified value. However, if a string value is used instead of a number, MongoDB may not increment the field correctly, potentially leading to unexpected results or errors.  The solution shows the correct way to use the `$inc` operator with a numeric value.

## Bug
The bug arises from using a string ('1') instead of a number (1) with the `$inc` operator in the `updateOne` method.

## Solution
The solution corrects the error by using the numerical value (1) with the `$inc` operator. This ensures that the field is incremented correctly.
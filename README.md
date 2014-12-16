tipCalculator
=============

This is a prework for CodePath IOS Swift bootcamp.

The instruction vedio is pretty straight forward and the tasks are very clear.
Only change to make is that bridgeToObjectiveC function is no longer existed.
Need to use

var billAmount = (billField.text as NSString).doubleValue

instead of

var billAmount = billFiled.text.bridgeToObjectiveC().doubleValue


#1. Optional

You use optionals in sitations where a value may be absent. An optional says：There is a value，it equals x or There isn't a value:

    var surveyAnswer: String?


If you define an optional constant or variable without providing a default value, the constant or variable is automatically set to nil for you.

###1.1 If Statements and Forced Unwrapping


    }

Note:

Trying to use `!` to access a non-existent optional value triggers a runtime error. Always make sure that an optional contains a non-nil value before using ! to force-unwrap its value.


###1.2 Optional Binding


You use optional binding to find out whether an optional contains a value, and if so, to make that value available as a temporary constant or variable. Optional binding can be used with if and while statements to check for a value inside an optional, and to extract that value into a constant or variable, as part of a single action. 

Write optional bindings for the if statement as follows:
 
        statements



    // requires an exclamation mark to access its value



computed properties do not actually store a value. Instead, they provide a getter and an optional setter to retrieve and set other properties and values indirectly.



If a computed property’s setter does not define a name for the new value to be set, a default name of newValue is used.



### Read-Only Computed Properties




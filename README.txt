This is the source code to !rbxparse, an rlua parser created in C++. This uses string splitting to accomplish limited script execution capable of executing one line scripts.

Currently rewriting and fixing some parts of the source code.

This method of script execution is buggy and very limited as it does not use a lua environment.

List of functions:
Basic for loops
MessageBox
printidentity
print
warn
Instance.new
BreakJoints
Destroy
Play
Stop
info
error
wait
Basic value changing
Color3.new
Vector3.new
Enum
